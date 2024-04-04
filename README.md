# [Gemini Homework Helper 📝](https://gemini-homework-helper.vercel.app/)
This project uses the Google Generative AI Gemini Pro to help students with homework. It works by extracting text from PDF and Word documents and taking the user's question to provide an answer. The user can also ask questions regarding uploaded images.

<div style="display: flex; justify-content: center; margin: 0 auto;">
    <img src="https://github.com/sankeer28/Gemini-Homework-Helper/assets/112449287/f6ffc0af-2d3e-49e9-8cb6-fac2396954d2" alt="Image 1" style="width: 100%; max-width: 100%;">
</div>


### Currently uses Gemini 1.0 Pro, will be updated to use Gemini 1.5 Pro once API is released to the public alongside new features
#### More information on models can be found [here](https://ai.google.dev/models/gemini)
## Features
- Uses API version V1.
- Saves API key to the cache, which persists upon page reload.
- Uses Gemini-1.0-Pro and Gemini-Pro-Vision models to interpret text and images, models are automatically selected
- Mobile-friendly layout.
- Markdown support for output.

## Usage
1. Go to https://gemini-homework-helper.vercel.app/
2. If you have a PDF (PDF must have copy-pasteable text) or Word document, you can upload it using the file input. The text will be extracted and used as input for the AI. Uploading an image uses the Gemini-Pro-Vision model.
3. You can also type your question directly into the text input field regarding a part of the document.
4. Click the "Send" button to get the AI's response.

## API Key
You will need to provide your Google Generative AI API key. You can get an API key [here](https://aistudio.google.com/)

## Contributing
1. **Bug Reports**: If you encounter any issues with the application, please file a bug report in the issue tracker on our project page.
2. **Feature Requests**: If you have a great idea for a new feature, feel free to submit it as a feature request on our project page. Please provide as much detail as possible about your idea.
3. **Code Contributions**: If you'd like to contribute code, bug fixes or improvements to the project, please fork the repository, make your changes, and submit a pull request. We'll review your contributions and integrate them into the project as soon as we can.

## Video Demo
https://github.com/sankeer28/Gemini-Homework-Helper/assets/112449287/b6a53b35-7376-468e-ad00-d9249f236e59

## Note
This project is for educational purposes only. Please use it responsibly.
- [API documentation for Web-based use](https://ai.google.dev/tutorials/get_started_web)


