# Invoice Data Extraction using OCR

This project automates the process of extracting text data from invoice images using Python, OpenCV, and Tesseract OCR. It is designed to handle image preprocessing, contour detection to isolate document areas, and character recognition.

## 🚀 Features
* **Image Preprocessing:** Uses Grayscale conversion and Gaussian Blur to reduce noise.
* **Document Localization:** Implements Adaptive Thresholding and Contour detection to find the invoice structure.
* **OCR Extraction:** Leverages `Pytesseract` to convert image data into searchable text.
* **Batch Processing:** Capable of handling multiple images in a single run.

## 🛠️ Tech Stack
* **Language:** Python
* **Libraries:** OpenCV, Pytesseract, Matplotlib, NumPy
* **Environment:** Google Colab

## 📋 How to Use
1. Open the `Data_Ext.ipynb` notebook in **Google Colab**.
2. Run the first cell to install the necessary Tesseract dependencies:
   ```bash
   !apt-get install tesseract-ocr
   !pip install pytesseract
