# 🕉️ Bhagavad Gita Q&A System 📖

This project implements a **Retrieval-Augmented Generation (RAG)** system to answer questions based on the **Bhagavad Gita**. The system uses the **LangChain** framework along with **Google Generative AI** to retrieve relevant context and generate answers.

## ✨ Features

- **Text Extraction**: Load and process a PDF of the Bhagavad Gita.
- **Text Splitting**: Split the text into smaller chunks to improve retrieval performance.
- **Embedding**: Use Google Generative AI embeddings for document retrieval.
- **Question Answering**: Ask questions related to the Bhagavad Gita, and the system will provide concise answers based on the retrieved context.
- **Gradio Interface**: A user-friendly interface for easy interaction with the system.

## 🚀 Requirements

- Python 3.7+
- **Google Cloud API key** (for embeddings)
- **Gradio**
- **LangChain**
- **langchain-google-genai**
- **pypdf**
- **langchain_chroma**

## 🛠️ Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/bhagavad-gita-qa.git
   cd bhagavad-gita-qa
   
2. Install dependencies:
    pip install langchain langchain_community pypdf langchain-chroma langchain-google-genai gradio



## 🖥️ How to Use
Text Extraction and Embedding:

Load the PDF using PyPDFLoader.
Split the PDF content into manageable chunks using RecursiveCharacterTextSplitter.
Generate document embeddings using Google Generative AI embeddings.
Question-Answering:

Once the system is set up, you can use the Gradio interface to ask questions.
The system will use RAG to retrieve relevant context from the Bhagavad Gita and generate answers.
Run the Gradio Interface:

# Run the script below to start the Gradio interface:

python
Copy code
interface.launch()

You will be able to ask questions like:

"How to control lust?"
"What is the nature of the soul?"
"Explain the concept of duty in Bhagavad Gita."
Interact with the Model:

After launching the interface, type in a question and click the "Submit" button to get a response.

## ❓ Example Questions
How to control lust?
What is the concept of karma?
Explain the importance of duty in the Bhagavad Gita.
What is the role of meditation in the Gita?


##Demo

# Simple UI

![Bhagavad Gita](1.png)

# Queries and Answers

![Bhagavad Gita](2.png),![Bhagavad Gita](3.png),![Bhagavad Gita](4.png)


