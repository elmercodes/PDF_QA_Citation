# PDF Document Expert

## About
The PDF Document Expert is a specialized tool designed to extract and analyze information from PDF documents. It enables users to upload PDF files and ask questions related to their content. Leveraging OpenAI's technology, the system provides precise answers along with references to the source material within the documents.

## Features
- **PDF Upload**: Users can upload up to 5 PDF files for in-depth analysis.
- **Question Answering**: After uploading, users can pose questions regarding the PDFs' content to receive detailed answers.
- **Source Referencing**: For each query, the tool cites three sources from the uploaded documents, providing transparency and traceability for the information given.

## How It Works
The application combines Streamlit for user interaction, Llama_index for processing PDFs, and OpenAI's ChatGPT for generating answers.

### Core Components
- **Streamlit**: Facilitates the web interface for user interaction.
- **Llama_index**: Handles the indexing and querying of PDF document contents.
- **OpenAI ChatGPT**: Powers the answering mechanism, generating accurate responses to queries.

### Remember
1. Clone the repository to your local system.
2. Install necessary Python packages: `streamlit`, `streamlit_extras`, `llama_index`, and `dotenv`.
3. Configure your OpenAI API key in a `.env` file as `OPENAI_API_KEY`.

## Setup and Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-github-username/pdf-document-expert.git
   ```
2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the application:
   ```bash
   streamlit run app.py
   ```
   
## Usage

- Navigate to the sidebar to upload your PDFs.
- After the upload, enter your question in the "Ask a question about the PDF content" field.
- View the answers, along with their sources and locations, directly below the query field.

## Contributing

Interested in contributing to the PDF Document Expert? Contributions, issues, and feature requests are welcome. Feel free to check the issues page to either create a new issue or help out with existing ones.
