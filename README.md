# AskYourPDF

AskYourPDF is a Streamlit application that allows users to ask questions about the content of a PDF document and receive relevant answers using OpenAI's language models. It utilizes the LangChain library for text splitting, embeddings, and question-answering capabilities.

# Getting Started

To run the AskYourPDF application locally, follow these steps:

Prerequisites
1. Python 3.x
2. OpenAI API key

Installation
1. Clone this repository to your local machine.
2. Install the required dependencies by running the following command:

```
 pip install -r requirements.txt 
```


# Configuration
1. Create a .env file in the project directory.
2. Add your OpenAI API key to the .env file using the following format:
``` OPENAI_API_KEY=your_api_key_here ```

# Running the Application
To start the server locally, execute the following command:
` streamlit run app.py `
The application will be accessible in your browser at http://localhost:8501.

# Uploading a PDF
Click the "Upload your PDF" button to select a PDF file for analysis.

# Asking a Question
- Once the PDF is uploaded, a text input field will appear.
- Type your question related to the content of the PDF in the input field.
- Press Enter or click outside the input field to submit the question.

# Viewing the Answer

- The application will process your question and display the corresponding answer.
- The answer will be shown in the format:
- "Your Answer: [answer]"
- "Your Spending: [spending]"

# Important Note

Please ensure that you have the necessary access and permissions for using the OpenAI API. Update the OPENAI_API_KEY global variable in the .env file with your valid API key before running the application.

**Note:** The application is dependent on OpenAI's language models and LangChain libraries, and requires a stable internet connection for proper functioning.

Enjoy exploring your PDFs with AskYourPDF!
