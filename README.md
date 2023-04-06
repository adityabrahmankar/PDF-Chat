# PDF Chatbot

PDF Chatbot is a web-based application that allows users to upload PDF files and ask questions about the content of those files. The chatbot leverages OpenAI GPT and Pinecone to provide accurate and relevant answers based on the uploaded PDFs.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Installation

To set up the PDF Chatbot project on your local machine, follow these steps:

1. Clone the repository: 
git clone https://github.com/adityabrahmankar/PDF-Chat.git


2. Install the necessary Python packages:
pip install -r requirements.txt


3. Set up environment variables:
export OPENAI_API_KEY="your_openai_api_key"
export PINECONE_API_KEY="your_pinecone_api_key"
export PINECONE_API_ENV="your_pinecone_api_environment"
export OPENAI_PROMPT="your_openai_prompt"

Replace the placeholder values with your actual API keys and other required information.

4. Run the Flask application:
python app.py

The application will be accessible at `http://0.0.0.0:8080`.

## Usage

To use the PDF Chatbot, follow these steps:

1. Access the application at `http://0.0.0.0:8080`.

2. Upload one or more PDF files by clicking "Choose Files" and selecting the files from your local machine. Then, click "Upload PDFs" to submit the files to the chatbot.

3. Once the PDF files are uploaded, you can start asking questions about the content of the uploaded files. Type your question in the input box and click the paper plane icon to submit your question.

4. The chatbot will analyze the content of the uploaded PDFs and provide an answer based on the documents.

## Contributing

We welcome contributions to the PDF Chatbot project! Here's how you can contribute:

1. Fork the repository.

2. Create a new branch for your feature or bugfix:
git checkout -b my-feature

3. Make changes to the code and commit your changes:
git add .
git commit -m "Add my feature"

4. Push your changes to your fork:

5. Create a pull request on the original repository to merge your changes.

Please ensure that your code follows the project's style guidelines and is well-documented.

## License

This project is licensed under the [MIT License](LICENSE). Please see the [LICENSE](LICENSE) file for more information.





