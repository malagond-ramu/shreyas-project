# 🚗 Vehicle Number Plate Recognition using OpenCV and OCR (Computer Vision)

This project demonstrates an automated system for **vehicle number plate recognition** using **OpenCV** for image processing and **Tesseract OCR** for text extraction. The system detects the number plate from vehicle images, extracts the number, and stores it along with the timestamp into a **CSV file**.

---

## 🧠 Project Overview

The core functionality of this project is to automatically process an image of a vehicle, detect the number plate, and read the registration number using Optical Character Recognition (OCR). The steps followed by the system are:

1. **Pre-processing**: Resize and convert the image to grayscale to enhance processing.
2. **Edge Detection**: Use **Canny Edge Detection** to detect significant edges in the image.
3. **Contour Detection**: Find contours in the image, focusing on those that match the shape of a number plate (rectangular).
4. **OCR (Optical Character Recognition)**: Extract the text from the detected number plate using **Tesseract OCR**.
5. **Data Saving**: Save the recognized number plate along with the timestamp to a **CSV file**.

---

## 🚀 How to Use the Project

### 1. **Install Dependencies**

Before running the script, ensure you have the necessary Python libraries installed. You can install them via `pip`:
```bash
pip install opencv-python pytesseract imutils pandas
