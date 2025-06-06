# Question Answering with Unstructured Data

## Project Description
This project demonstrates how to preprocess unstructured data from various document formats and use it as context for a transformers-based Question Answering (QA) model. The pipeline extracts text from multiple document types and structures it for effective retrieval.

### Supported Document Types
- PDF
- Word (.docx)
- Excel (.xlsx)
- PowerPoint (.pptx)
- EPUB
- HTML

## Installation

```bash
# Clone the repository
git clone https://github.com/Begolosamazaref/Question-Answering.git
cd Question-Answering

# Install required packages
pip install -r requirements.txt
```

## Required Dependencies
- python-docx
- python-pptx
- BeautifulSoup4
- transformers
- pdfplumber
- pytesseract
- Pillow
- pandas
- ebooklib

## How to Run the Code

### 1. Prepare Your Documents
Place your documents in the appropriate input directory.

### 2. Run the Preprocessing Notebook
```bash
jupyter notebook QA.ipynb
```

### 3. Review Extracted Data
The extracted text and metadata will be saved in the `output/` folder in JSON format.

### 4. Using the RAG Pipeline
After preprocessing, the extracted text can be used as input for a Question-Answering (QA) model using the transformers' pipeline.


## Contributing
Contributions are welcome! Please feel free to submit a Pull Request.

