# Chat with Multiple PDFs

A Streamlit web application that allows users to chat with documents using the Palm API.

## Overview

This project is a web application built with Streamlit, allowing users to interactively chat with documents uploaded in PDF format. It utilizes the Palm API for natural language understanding and conversational retrieval.

## Features

- **Document Upload**: Users can upload multiple PDF files.
- **Chat Interface**: Provides a user-friendly chat interface for interaction.
- **Natural Language Processing**: Utilizes Palm API for understanding user queries and providing relevant responses.
- **Conversational Retrieval**: Implements a conversational retrieval system for context-aware responses.
- **Real-time Interaction**: Responses are generated in real-time for seamless conversation flow.

## Installation

To run the application locally, follow these steps:

1. Clone this repository:

    ```bash
    https://github.com/keerthan03/Chat-With-Documents.git
    ```

2. Install the required Python packages:

    ```bash
    pip install -r requirements.txt
    ```

3. Set up the required API key:

    - Obtain an API key from [Palm API](https://palm-gpt.com/) and set it as an environment variable:

        ```bash
        export GOOGLE_API_KEY="YOUR_API_KEY"
        ```

4. Run the Streamlit app:

    ```bash
    streamlit run app.py
    ```

5. Access the application in your browser at `http://localhost:8501`.

## Usage

1. Upload one or more PDF files using the file uploader.
2. Type your question/query in the text input box.
3. Click the "Process" button to analyze the documents and receive a response from the chat interface.

## Technologies Used

- Streamlit
- PyPDF2
- Langchain Community
- FAISS
- Google Palm API

## Contributing

Contributions are welcome! If you'd like to contribute to this project, please fork the repository and submit a pull request with your changes.

## License

This project is licensed under the [MIT License](LICENSE).
## Acknowledgements

- [Streamlit](https://streamlit.io/) - Official Streamlit documentation.
- [Palm API](https://palm-gpt.com/) - Documentation for the Palm API used for natural language understanding.
- [Langchain Community](https://github.com/langchain/langchain-community) - Community repository for Langchain, a collection of tools for language processing tasks.
- [Awesome Langchain](https://github.com/kyrolabs/awesome-langchain) - A curated list of awesome language processing resources and tools.
- [How to Code a Project Like ChatPDF](https://postor.medium.com/how-to-code-a-project-like-chatpdf-e40441cb4168) - Medium article detailing the process of building a project similar to ChatPDF.
- [Streamlit Conversational Apps Tutorial](https://docs.streamlit.io/develop/tutorials/llms/build-conversational-apps) - Streamlit tutorial on building conversational apps.

