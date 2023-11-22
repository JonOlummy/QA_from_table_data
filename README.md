# PDF Table Extractor and Question Answering System

This Python application allows you to extract tables from PDF files and ask questions related to the extracted data. It utilizes the Camelot library for PDF table extraction, OpenAI's GPT-3 for question answering, and other Python libraries for data processing. The LangChain library is used for text processing and embeddings.

## Installation

1. Install the required Python packages using pip:

   ```bash
   pip install -r requirements.txt
   ```

2. Set up your OpenAI API key by creating a `.env` file and adding your API key:

   ```
   OPENAI_API_KEY=your_api_key_here
   ```

3. Run the application:

   ```bash
   streamlit run app.py
   ```

## Description

This application is designed to extract tables from PDF files and provide a question-answering feature based on the extracted data. It's a useful tool for quickly retrieving information from PDF documents in a tabular format and obtaining answers to questions related to that data.

## Usage

1. **Upload a PDF**: Click the "Upload a PDF containing tables" button and select a PDF file from your local device.

2. **Extract Tables**: The system will use Camelot to extract tables from the uploaded PDF. Extracted tables will be displayed in tabular format.

3. **Ask a Question**: Enter a question related to the extracted data in the "Enter your question related to the table(s)" text input field.

4. **Get an Answer**: After entering your question, click the "Get Answer" button. The system will use OpenAI's GPT-3 to generate an answer based on the question and the extracted data.

5. **View the Answer**: The answer will be displayed below the input field.
