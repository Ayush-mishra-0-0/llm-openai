# llm-openai
# LangChain Project

## Introduction
The LangChain project is a Python application that uses various Natural Language Processing (NLP) tools and libraries to perform document processing, text splitting, and question-answering. It leverages OpenAI's GPT-3.5 language model and other components for a variety of NLP tasks.

## Installation
To get started with the LangChain project, you need to set up the required dependencies. Follow these steps to set up the environment:

### 1. Install Required Packages
You can install the necessary packages using `pip`:

```bash
!pip install langchain
!pip install openai
!pip install cohere
!pip install tiktoken
!pip install llmx==0.0.15a0
```

### 2. Export Your OpenAI API Key
Make sure to set your OpenAI API key as an environment variable:

```bash
import os
os.environ["OPENAI_API_KEY"] = "your-api-key"
```

### 3. Download Sample PDF Document (Optional)
The example provided in the code assumes you have a PDF document named "book.pdf" in the project directory. If you want to use a different document, make sure to change the PyPDFLoader initialization accordingly.
