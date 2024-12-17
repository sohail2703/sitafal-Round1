PDF Processing and Query System :
Extract Text and Images from PDFs: This program reads text and extracts images from uploaded PDF files using pdfminer and PyMuPDF.

Save Images and Text: Extracted images are stored in a folder, and text is split into manageable chunks for better processing.

Build Searchable Index: Creates a searchable index using FAISS and HuggingFace sentence embeddings to help find answers efficiently.

Answer Questions: Ask questions about the content of the PDFs, and the program will use a language model to provide relevant answers.

Save and Load Data: The FAISS index is saved to a file, so you can reuse it without reprocessing PDFs.

Easy to Run: Just upload your PDFs, process them, and ask questions – all steps are automated for ease of use.






