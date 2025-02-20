# AIE314 Tutorial 1: Preprocessing Unstructured Data for LLM Applications  

## Team Members  
- Ahmed Dawood (ID: 21100820)  
- Mohamed Ibrahim (ID: 21100837)  
- Begol Osama (ID: 21100791)  

## Project Description  
This project focuses on **preprocessing unstructured data** from various document types, including:  
✅ **PDF**  
✅ **Word (.docx)**  
✅ **Excel (.xlsx)**  
✅ **PowerPoint (.pptx)**  
✅ **EPUB**  
✅ **HTML**  

After extraction, the structured data is used as context for a transformers-based QA model. 

## How to Run the Code  

### 🔹 1. Install Dependencies  
Before running the script, ensure you have all the required Python libraries:  
✅ **Document**
✅ **Presentation**
✅ **BeautifulSoup**
✅ **transformers import pipeline**
✅ **pdfplumber**
✅ **pytesseract**
✅ **PIL import Image**
✅ **os**
✅ **json**

### 🔹 2️. Run the Preprocessing Notebook
Execute the Jupyter Notebook to process files and extract structured data:
✅ **Jupyter notebook preprocessing.ipynb**

### 🔹 3. Extracted Data Output
✅ **The extracted text and metadata will be saved in the output/ folder in JSON format.**

### 🔹 4. Using the RAG Pipeline
✅ **After preprocessing, the extracted text can be used as input for a Question-Answering (QA) model using the transformers' pipeline.**
✅ **Modify the answer_question(filepath, question) function in preprocessing.ipynb to test queries.**
