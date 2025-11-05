# 🤖 RAG-PDF-Query-Bot

Ask Questions to Your PDFs using AI!

This project implements a **R**etrieval-**A**ugmented **G**eneration (RAG) system using LangChain. It allows you to upload a PDF document and then ask questions about its content. Instead of using generic knowledge, the AI uses the specific information inside your document to generate accurate answers!

## Key Features

* **PDF Ingestion:** Easily load and process text from any PDF document.
* **Intelligent Q&A:** Ask complex questions and get precise answers based *only* on the content of the PDF.
* **RAG Architecture:** Utilizes the powerful RAG framework for grounded, factual responses.
* **Modular Code:** Built using the popular **LangChain** framework, making it easy to understand and expand.

## Technologies Used

| Technology | Purpose |
| :--- | :--- |
| **Python** | The primary programming language. |
| **LangChain** | Framework for developing applications powered by language models. |
| **OpenAI/Other LLMs** | The core large language model used for generating answers (requires an API Key). |
| **FAISS/ChromaDB** | Used as a vector store to efficiently index and search the PDF content. |
| **Streamlit/Jupyter** | (Implied by the repo content) Used for the user interface/interactive development environment. |

## Installation & Setup

Follow these steps to get your RAG Bot running locally.

### 1. Clone the Repository

Open your terminal or command prompt and clone the project:

```bash
git clone [https://github.com/Dev-1404/RAG-PDF-Query-Bot.git](https://github.com/Dev-1404/RAG-PDF-Query-Bot.git)
cd RAG-PDF-Query-Bot
````

### 2\. Set Up the Environment

It's best practice to use a virtual environment:

```bash
# Create a virtual environment
python -m venv venv 
# Activate the environment (macOS/Linux)
source venv/bin/activate
# Activate the environment (Windows)
venv\Scripts\activate
```

### 3\. Install Dependencies

Run this single command in your terminal or Jupyter/Colab notebook cell:

```
pip install langchain faiss-cpu pdfplumber langchain-google-genai tiktoken langchain-community
```

### 4\. Configure Your API Key

This bot requires an API key for the Large Language Model (e.g., OpenAI).

Create a file named `.env` in the project root directory and add your key like this:

```
# Example for OpenAI
OPENAI_API_KEY="your_secret_api_key_here" 
```

**Note:** Never commit your actual API keys directly to GitHub\!

## Usage

To run the RAG-PDF-Query-Bot, you will typically execute the main Python file or run the Jupyter Notebook.

### Running the Jupyter Notebook

1.  Start the Jupyter server:
```  
    jupyter notebook
```
2.  Open the file `RAG_LangChain.ipynb` in your browser.
3.  Execute the cells step-by-step to load a PDF, process it, and run the query chain.



## Contribution

Feel free to **fork** this repository, open issues, and submit pull requests. Any suggestions for improvement are welcome\!

## License

This project is licensed under the **MIT License** .

## Contact

Created by **Dev-1404** - feel free to reach out\!
