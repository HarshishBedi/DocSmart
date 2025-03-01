# DocSmart 📑🧠

DocSmart is an innovative Retrieval Augmented Generation (RAG) agent for document analysis built with Streamlit, Deep-Seek-R1:1.5b, and Ollama. It allows you to upload PDF documents, query their content interactively, and receive concise, factual answers based on your document's context.

## Features

- **PDF Upload & Analysis:** Easily upload your research documents in PDF format.
- **RAG-Powered Q&A:** Retrieve relevant document sections and generate expert-level answers.
- **Interactive Chat Interface:** Enjoy a chat-based interface with custom styling for an enhanced user experience.
- **Customizable & Extendable:** Built using popular libraries like LangChain, making it easy to adapt and expand.

## Installation

1. **Clone the Repository**

   ```bash
   git clone https://github.com/yourusername/docsmart.git
   cd docsmart
   ```

2. **Set Up a Virtual Environment (Optional but Recommended)**

    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows: venv\Scripts\activate
    ```

3.	**Install Dependencies**
Make sure you have Python 3.7+ installed. Then, install the required packages with:

    pip install -r requirements.txt

## Running the Application

To launch the DocSmart application, run the following command:

    streamlit run rag_deep.py

This command will start the Streamlit server and open the application in your default web browser. You can then upload your PDF document and start interacting with the RAG agent.

## Usage

1.	Upload a PDF Document: Click the upload button to select a PDF file.
2.	Ask Questions: Enter your query about the document in the chat input field.
3.	Receive Answers: The system will analyze the document and respond with concise, factual answers.

## Contributing

Contributions are welcome! If you have suggestions, improvements, or bug fixes, please fork the repository and create a pull request.

## License

This project is licensed under the MIT License.

## Acknowledgements
	•	Built with Streamlit
	•	Powered by LangChain and Ollama
	•	Thanks to the contributors and the open-source community for their support.
