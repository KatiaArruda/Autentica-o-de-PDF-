## PDF Authentication with CPF

The PDF authentication project with CPF is a webpage where users can upload a PDF file and enter a CPF number. They can select the color and position (bottom left, bottom right, top left, or top right) on the PDF where the CPF will be printed. After generating the document, the CPF number will be visible in the selected color and position.

## 📌 Overview
The PDF Authentication with CPF project allows users to add a CPF number to a PDF file. The system enables customization by allowing users to select the color and position of the CPF within the document, ensuring a flexible and personalized process.

## 🚀 Key Features  
-  Upload PDF files for modification.  
-  Insert a CPF number into the document.  
-  Choose the CPF position (top-left, top-right, bottom-left, or bottom-right).  
- Select the text color for the CPF.  
-  Download the modified PDF with the CPF inserted.

## 🛠 Technologies Used
- Python + Flask → Backend and web interface.
- WTForms → Form handling.
- PyPDF2 + ReportLab → PDF modification.
- HTML + CSS → Application interface.

## 🔧 How It Works?
- The user accesses the web interface.
- Enters the CPF, selects the color and position in the PDF.
- Uploads the PDF file.
- The system processes the CPF insertion and returns the modified document for download.

## 📂 Code Structure
- app.py → Manages the Flask application logic and file uploads.
- pdf_modifier.py → Inserts the CPF into the PDF using PyPDF2 and ReportLab.
- templates/index.html → Web interface for file upload and parameter selection.
- static/styles.css → Styles for the application interface.

## 🎯 Demo
https://authentication-the-pdf-with-cpf.onrender.com


