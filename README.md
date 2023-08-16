# PDF-Image-Scraper

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/gist/mrjw717/cf4098586ce06b038b090cd0acf0702e/pdf-image-extraction-and-optional-color-reversal-1-0.ipynb)

# PDF Image Extraction and Color Reversal
This project provides a Python script for extracting images from PDF files and an additional script to reverse the colors of extracted images if they appear as negatives. It aims to streamline the process of extracting images from PDF documents and handling potential color inversion issues. The scripts are designed to be used in a Google Colab environment and leverage libraries such as PyMuPDF and Pillow for efficient PDF processing and image manipulation.

# Features
PDF Image Extraction: The primary part takes PDF files as input and extracts images from each page. It handles common challenges in image extraction, such as using both primary and fallback methods to ensure maximum image retrieval.

Color Reversal (Optional): The secondary part focuses on reversing the colors of images that may have been extracted as negatives. This process transforms inverted images back to their original colors, enhancing their visual quality.

# Usage
Clone or download this repository to your local machine.
Upload your PDF files to the designated input folder (/content/drive/MyDrive/ImageScrapePDF/Import) in Google Drive or use the automated option.
Run the PDF image extraction script in Google Colab. The extracted images will be stored in the output folder (/content/drive/MyDrive/ImageScrapePDF/Output).
(Optional) Run the color reversal script to correct any negatively extracted images. The corrected images will be saved in separate 'flipped' folders within the output directory.
Please refer to the provided scripts for more detailed instructions and customization options. Feel free to contribute, report issues, or suggest enhancements through GitHub's issue tracker and pull request mechanisms.
