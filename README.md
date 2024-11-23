# WebApp
# DOCX to PDF Converter Web App

This web application allows users to upload a `.docx` file, view its metadata (such as title, author, creation date), and download the converted file as a PDF. The PDF is generated from the content of the `.docx` file.

## Features
- **File Upload**: Users can upload `.docx` files.
- **Metadata Extraction**: Extracts and displays metadata such as title, author, and creation date from the `.docx` file.
- **PDF Conversion**: Converts the uploaded `.docx` file to a PDF.
- **PDF Download**: Allows users to download the generated PDF.

## Technologies Used
- **Flask**: A lightweight WSGI web application framework used to build the web application.
- **Python-docx**: A Python library to interact with `.docx` files (reading content and extracting metadata).
- **ReportLab**: A library used to generate PDFs in Python.
- **HTML/CSS**: Basic front-end technologies to render the file upload form and display metadata.
