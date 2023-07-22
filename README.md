# Multiple-PDF-LangChain-chat-application
A chatbot that allows you to ask questions about your multiple PDFs using LangChain and ChatGPT API.

# Description : 

The primary goal of this project is to provide users with an interactive and conversational experience when dealing with PDF documents. The chatbot utilizes the capabilities of ChatGPT to understand natural language queries and respond intelligently to user inputs related to the content of PDF files.
The ChatGPT-PDF-Chatbot opens up exciting possibilities for users to unlock the potential of their PDF documents in a dynamic and interactive manner. Whether it's extracting specific information, summarizing content, or seeking answers to complex questions, the chatbot offers a novel way to interact with text-based documents.

PDF-Chatbot Workflow:

1. PDF Parsing: The application begins by parsing multiple PDF documents to extract their text content. Each document is carefully processed, and the text is retrieved for further analysis.

2. Text Segmentation: To improve processing efficiency, the extracted text is divided into smaller, manageable chunks. These smaller text segments facilitate more effective language model analysis.

3. Language Model Utilization: The heart of the application lies in leveraging a powerful language model. By employing this sophisticated AI model, the chatbot can generate vector representations (embeddings) of the segmented text chunks.

#Run this app by following the steps : (I can't share the deployed link Due to Open AI access limits) 

1. Put your Open AI secret Key in the .env file
2. put your HuggingFace API token in the .env file

IN THE TERMINAL RUN THE BELOW LINES 

3. pip install -r requirements.txt

4. streamlit run app.py
