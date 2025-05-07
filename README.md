# 🖼️ Image Captioning App

This is a simple web application that generates captions for images using a pretrained BLIP (Bootstrapped Language Image Pretraining) model from Hugging Face.

## 🚀 Demo

Try it live: [Hugging Face Spaces Link](https://huggingface.co/spaces/anubhavv1/image-captioning-demo)

## 📌 Features

- Upload an image and get a natural language caption
- Based on the BLIP image captioning model
- Lightweight and easy to use via Gradio UI
- Hosted online with no setup needed

## 🧠 Model Used

- [`Salesforce/blip-image-captioning-base`](https://huggingface.co/Salesforce/blip-image-captioning-base)
- BLIP is a vision-language model trained on large-scale image-text data

## 🛠️ Tech Stack

- Python
- Transformers (Hugging Face)
- Gradio
- PIL (Pillow)
- NumPy

## 🧪 Testing

Basic test script is included to validate output on a sample image using `pytest`.

## 📦 Installation

```bash
git clone https://github.com/anubhavwalia999/image-captioning-app.git
cd image-captioning-app
pip install -r requirements.txt
python app.py
