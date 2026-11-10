# photoshop-a4
photo shop a4 6x4 fit


# A4 Photo Grid Batch Automator (AVIF & Image Processor)

A Python script that automatically processes a folder of images (including modern **AVIF**, JPG, PNG, etc.) and arranges them into a **2x2 grid on A4 sheets** at 300 DPI. 

## ✨ Features
* **Multi-Format Support:** Handles `.avif`, `.jpg`, `.jpeg`, `.png`, `.bmp`, and `.tiff` files.
* **Auto-Orientation:** Automatically detects landscape images and rotates them to portrait orientation.
* **Full-Fit Processing:** Scales images to fill the A4 grid cells completely without unwanted white/black padding or data cropping.
* **Batch Automation:** Automatically groups images into sets of 4 per A4 page (`A4_FullFit_Sheet_1.jpg`, etc.).

---

## 🚀 Prerequisites & Installation

Make sure you have Python installed on your system. Then, install the required libraries (`Pillow` and `pillow-heif` for AVIF support) by running the following command in your terminal:

```bash
pip install Pillow pillow-heif
