# Image-W2-OCR
This script performs OCR (Optical Character Recognition) on either a single image or a dataset. Features include:

# OCR Preprocessing & Evaluation

# Dataset

The dataset used is from a public Kaggle Dataset:
https://www.kaggle.com/datasets/quantumkaze/infrrd-dataset/data

It contains W2 forms, some have been skewed and distorted and some are machine-ready

## Description
This script performs OCR (Optical Character Recognition) on either a single image or a dataset. Features include:

- Image deskewing (automatic skew correction)
- Grayscale conversion and denoising
- OCR using Tesseract
- Evaluation against ground truth (accuracy, precision, recall, F1-score)

The script can run in two modes:
1. **Single Image Mode** – Run OCR on a specified image
2. **Dataset Mode** – Process a folder of images and evaluate OCR against `.tsv` ground truth files

---

## Requirements

- Python 3.8+
- [Tesseract OCR](https://github.com/tesseract-ocr/tesseract)
- Python packages (install via pip):

```bash
pip install opencv-python numpy pandas pytesseract
