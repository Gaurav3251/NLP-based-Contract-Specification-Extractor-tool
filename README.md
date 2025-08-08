# NLP-based-Contract-Specification-Extractor-tool

NLP Contract Specification Extractor with Q&A

This project is an AI-powered tool designed to extract and analyze contract specifications from PDF documents, with a focus on construction contracts. It leverages natural language processing (NLP) techniques to identify key information such as materials, tests, standards, and definitions. 

🌟 Key Features

Extraction of Materials, Tests, and Standards: Automatically extracts relevant information from construction contract PDFs.

Intelligent Q&A System: Enables users to query the document (e.g., "What are the requirements for M25 concrete?") with answers derived from extracted data and full text..

Support for Large Documents: Optimized for processing PDFs with 100+ pages.

OCR Fallback: Employs Tesseract OCR for scanned documents when text extraction fails.


🛠️ Technologies Used

Python

pdfplumber: For PDF text and table extraction.

spaCy: For NLP tasks and entity recognition.

Transformers (BERT, DistilBERT): For named entity recognition (NER) and question-answering.

Gradio: For the interactive web interface.

FAISS: For efficient similarity search in the Q&A system.

ReportLab: For generating PDF reports.

Tesseract OCR: For optical character recognition.

Sentence Transformers: For semantic search in Q&A.


👥 Team Members

Gaurav Tarate | Shubham Palve | Atharav Pawar


📄 License

This project is licensed under the MIT License. See the LICENSE file for details.
