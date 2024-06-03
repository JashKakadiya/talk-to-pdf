# Chat with Multiple PDF

**Chat with Multiple PDF** is a platform that enables users to engage in conversations while simultaneously viewing and discussing multiple PDF documents. This functionality facilitates collaboration by allowing users to share, discuss, and annotate PDF files in real-time within a chat interface. It is particularly useful for teams working on projects that involve reviewing, editing, or analyzing multiple documents concurrently.

## Features
- **Simultaneous Viewing**: View multiple PDF documents at the same time.
- **Real-time Collaboration**: Chat and collaborate with team members in real-time.
- **Annotation**: Annotate PDF documents while discussing them with your team.
- **User-friendly Interface**: Easy-to-use interface for seamless document management and discussion.

## Tools & Technology
- **Langchain**: For managing and chaining together various AI and ML components.
- **Python**: The core programming language used for development.
- **Llama2**: Utilized for natural language processing tasks.
- **Streamlit**: Provides the web interface for users to interact with the application.

## How It Works
------------

![MultiPDF Chat App Diagram](./docs/PDF-LangChain.jpg)

The application follows these steps to provide responses to your questions:

1. PDF Loading: The app reads multiple PDF documents and extracts their text content.

2. Text Chunking: The extracted text is divided into smaller chunks that can be processed effectively.

3. Language Model: The application utilizes a language model to generate vector representations (embeddings) of the text chunks.

4. Similarity Matching: When you ask a question, the app compares it with the text chunks and identifies the most semantically similar ones.

5. Response Generation: The selected chunks are passed to the language model, which generates a response based on the relevant content of the PDFs.

## Dependencies and Installation
----------------------------
To install the MultiPDF Chat App, please follow these steps:

1. Clone the repository to your local machine.

2. Install the required dependencies by running the following command:
   ```
   pip install -r requirements.txt
   ```

3. Obtain an API key from OpenAI and add it to the `.env` file in the project directory.
```commandline
OPENAI_API_KEY=your_secrit_api_key
```

## Usage
Visit the web application at [Chat with Multiple PDF](https://talk-to-pdf-b26l.onrender.com) to start collaborating on your PDF documents.

## Contributing
Contributions are welcome! Please fork this repository and submit a pull request for any enhancements or bug fixes.

## License
This project is licensed under the MIT License.

## Acknowledgments
- Special thanks to the developers of Langchain, Llama2, and Streamlit for their amazing tools.

---

Feel free to reach out with any questions or feedback!


