# Bill Comparison Tool

This Jupyter Notebook provides a tool for analyzing and comparing two bills (in PDF or image formats) using an AI-powered assistant. The application highlights key pricing differences and reasons for changes between the bills.

## Features

- **PDF and Image Processing**: Extracts text from PDFs and images (PNG/JPG).
- **AI Analysis**: Uses OpenAI's GPT model to analyze and explain differences between the two bills.
- **Gradio Interface**: A user-friendly web interface for uploading and comparing files.

## Requirements

To run this notebook, you need the following:

- Python 3.8 or higher
- Required libraries:
  - `gradio`
  - `pytesseract`
  - `Pillow`
  - `PyPDF2`
  - `openai`
  - `dotenv`
- Tesseract OCR installed on your system
- OpenAI API Key
- HuggingFace Token (if applicable)

## Setup

1. **Install Python Dependencies**:

   ```bash
   pip install gradio pytesseract pillow pypdf2 openai python-dotenv
   ```

2. **Install Tesseract OCR**:

   - [Tesseract Installation Guide](https://github.com/tesseract-ocr/tesseract)

3. **Set Environment Variables**:

   Create a `.env` file with your OpenAI API Key and HuggingFace Token:

   ```env
   OPENAI_API_KEY=your_openai_api_key
   HF_TOKEN=your_huggingface_token
   ```

4. **Run the Notebook**:

   Launch the notebook in Jupyter and execute all cells.

5. **Launch Gradio Interface**:

   The Gradio interface will open in a new browser tab, allowing you to upload files and analyze them.

## Usage

1. **Upload Files**: Use the Gradio interface to upload two files (PDF or image).
2. **Analyze Differences**: The AI will analyze and return the key differences along with explanations.
3. **Error Handling**: Ensure both files are of the same type (PDF or image) for the analysis to work correctly.


## Limitations

- Requires clear and legible bill images or PDFs for accurate OCR processing.
- AI model results depend on the quality of extracted text and the model configuration.

![image](https://github.com/user-attachments/assets/3f664730-b7a1-4c7f-b95c-e3cd495803be)

Error handelling:
![image](https://github.com/user-attachments/assets/70c0ac4e-2c1f-4467-8dce-e79632ee9874)
