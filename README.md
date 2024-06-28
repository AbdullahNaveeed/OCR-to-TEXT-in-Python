# OCR-to-TEXT-in-Python
 
An OCR to Text converter in Python using FastAPI is a web application that processes images to extract and convert text. FastAPI, known for its speed and ease of use, handles the API endpoints and request handling. The OCR (Optical Character Recognition) functionality can be powered by libraries such as Tesseract OCR or EasyOCR. When an image is uploaded via a POST request, the FastAPI server reads the image and passes it to the OCR library, which processes the image to extract text. The extracted text is then returned in the response. This setup allows for a scalable and efficient way to automate text extraction from images, useful for various applications like digitizing documents, extracting text from photos, and more.


Overview
This project is a web application built with FastAPI that allows users to upload images and convert the text within them to various formats (TXT, DOCX, XLSX) using Optical Character Recognition (OCR). The application leverages EasyOCR for the OCR functionality and provides a user-friendly interface for uploading images and downloading the extracted text in the desired format.

Features
Image Upload: Users can upload images in formats like JPG and PNG.
OCR Processing: Extract text from images using EasyOCR.
Multi-language Support: Supports OCR for multiple languages including English, Spanish, French, German, and Italian.
Output Formats: Extracted text can be downloaded in TXT, DOCX, or XLSX formats.
Static and Upload Directories: Serves static files and manages uploaded files.
Requirements
Python 3.7+
FastAPI
EasyOCR
Jinja2
python-docx
pandas
openpyxl
Uvicorn