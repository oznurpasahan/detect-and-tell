# Detect and Tell 📖🤖

**Detect and Tell** is a simple AI project that combines computer vision and language generation.  
The project takes an image, finds objects inside it, and then writes a short story using those objects.

It is useful for fun experiments, basic AI learning, and small creative applications.  
It can help understand how object detection and language models work together.

---

## 🧠 What does it do?

This project:

1. Loads an image from your folder (for example, `1.jpg` or `10.jpg`)
2. Detects the objects inside the image using Hugging Face models like `DETR` and `YOLOS`
3. Takes the object names (like "book", "cup", "laptop") and sends them to a text generation model
4. Generates a short story using the detected objects
5. Draws red boxes on the image to show the detected objects

---

## 🧪 Technologies Used

- **Python 3**
- **Hugging Face Transformers**
- **Pretrained Vision and Language Models**
- `facebook/detr-resnet-50` for object detection
- `hustvl/yolos-tiny` for object detection
- `mistralai/Mistral-7B-Instruct-v0.3` for story generation
- `Pillow` and `Matplotlib` for image drawing

---

## 💻 How to Use

### 1. Install required libraries
You can install them using pip:

```bash
pip install -r requirements.txt
