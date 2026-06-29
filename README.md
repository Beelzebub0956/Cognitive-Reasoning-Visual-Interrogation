# Cognitive Reasoning by Visual Interrogation (CRVI)

A deep learning-based Visual Question Answering (VQA) system capable of answering natural language questions about cartoon images.

## Features
- Image upload and question answering
- Multimodal learning using image and text features
- CLIP ViT-B/32 + ResNet-50 feature extraction
- LSTM for question encoding
- Image-Guided Attention mechanism
- Flask web interface

## Tech Stack
- Python
- PyTorch
- CLIP
- ResNet-50
- LSTM
- Flask

## Dataset
VQA Abstract Scenes v2

## Results
- Validation Accuracy: **69.83%**
- CPU inference in under **2 seconds**

## Installation
```bash
pip install -r requirements.txt
```

## Run
```bash
python app.py
```

## Project Structure
```
CRVI-Visual-Question-Answering/
├── app.py
├── train.py
├── model.py
├── requirements.txt
├── notebook.ipynb
├── README.md
└── screenshots/
```

## Author
**Arindam Jaiswal**
