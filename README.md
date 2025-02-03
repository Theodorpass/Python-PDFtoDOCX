# Python-PDFtoDOCX
This script allows you to convert the text content of a PDF document into a DOCX file. It uses the PyMuPDF library to extract the text from the PDF and the python-docx library to create and save the DOCX file.
## Usage

1. Clone or download this repository to your local machine.

   ```bash
   git clone https://github.com/Theodorpass/Python-PDFtoDOCX.git

2  Navigate to the project folder:
  cd Python-PDFtoDOCX


3  Install the required dependencies:
  pip install -r requirements.txt


4  Open the pdf_to_docx.py script and modify the pdf_file and docx_file paths to your specific files:

pdf_file = r'C:\path\to\your\input.pdf'  # Replace with your input PDF file path
docx_file = r'C:\path\to\your\output.docx'  # Replace with your desired output DOCX file path

5  Run the script:
python pdf_to_docx.py

After execution, check the destination folder for the newly created DOCX file containing the extracted text from the PDF.
