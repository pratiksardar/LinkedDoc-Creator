# LinkedIn Post to PDF/HTML Converter

Convert your LinkedIn posts to PDF or HTML documents with this simple tool. This tool utilizes Selenium for web scraping and PyPDF2 and ReportLab for PDF generation. You can use it to capture your LinkedIn posts, including text and images, and save them as PDF or HTML files for offline viewing or sharing.

## Features

- Convert LinkedIn posts to PDF documents.
- Generate HTML documents from your LinkedIn posts.
- Capture both text and images from posts.
- Customize watermark text for your documents.

## Requirements

Before using this tool, ensure you have the following dependencies installed:

- Python (>=3.6)
- Selenium (`pip install selenium`)
- Chrome WebDriver (compatible with your Chrome browser version)
- PyPDF2 (`pip install PyPDF2`)
- ReportLab (`pip install reportlab`)
- Pillow (`pip install pillow`)

## Usage

1. Clone this repository to your local machine or download the script files.

2. Install the required Python libraries using the provided `requirements.txt` file:
   
   ```shell
   pip install -r requirements.txt