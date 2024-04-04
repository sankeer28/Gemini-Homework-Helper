# Gemini Homework Helper
This project uses the Google Generative AI Gemini Pro to help students with homework. It works by extracting text from PDF and Word documents and taking the user's question to provide an answer. The user can also ask questions regarding uploaded images.

## Features
- Uses API version V1.
- Saves API key to the cache, which persists upon page reload.
- Uses Gemini-Pro and Gemini-Pro-Vision models to interpret text and images, models are automatically selected
- Mobile-friendly layout.
- Markdown support for output.

## Usage
1. If you have a PDF (PDF must have copy-pasteable text) or Word document, you can upload it using the file input. The text will be extracted and used as input for the AI. Uploading an image uses the Gemini-Pro-Vision model.
2. You can also type your question directly into the text input field regarding a part of the document.
4. Click the "Send" button to get the AI's response.

## API Key
You will need to provide your Google Generative AI API key. You can get an API key [here](https://aistudio.google.com/)

## Note
This project is for educational purposes only. Please use it responsibly.
