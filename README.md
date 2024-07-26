# 🛡️ ChatGenie - Advanced Document Processing & Chat Application

[![Python Version](https://img.shields.io/badge/python-3.9%2B-blue)](https://www.python.org/downloads/)
[![React Version](https://img.shields.io/badge/react-18.0%2B-61DAFB)](https://reactjs.org/)

## 🚀 Overview

ChatGenie is an advanced document processing and chat application that leverages state-of-the-art NLP techniques and Retrieval-Augmented Generation (RAG) to provide insightful and contextually relevant responses to user queries. It's your AI-powered sidekick for conquering information overload!

### ✨ Key Features

- 📊 **Text & Graph Responses**: Get answers in both text and eye-catching visuals.
- 🧠 **RAG-powered Document Preprocessing**: Our AI splits and understands your docs like a pro.
- 🎯 **Contextual Relevance**: Pinpoint accuracy with advanced embedding techniques.
- 💾 **Smart Session Management**: Pick up right where you left off, every time.
- 🔬 **Cutting-edge NLP**: Combines retrieval and generative models for unparalleled accuracy.

### 🛠️ Tech Stack

| Component | Technologies |
|-----------|--------------|
| Frontend  | React, Bootstrap, Chart.js |
| Backend   | Python, Flask |
| AI Magic  | Google Generative AI (Gemini), Hugging Face API |
| Text Extraction | pdfplumber, python-docx, python-pptx |
| Hosting   | Render (backend), Vercel (frontend) |

## 🏗️ Setup Instructions

### 🔑 Obtain API Keys

#### Hugging Face API:
1. Visit [Hugging Face](https://huggingface.co/)
2. Log in or sign up for a new account
3. Navigate to your account settings and locate the "Access Tokens" section
4. Create a new token with 'write' permissions and copy the generated key

#### Google Gemini API:
1. Visit [Google AI Studio](https://aistudio.google.com/app/apikey)
2. Log in to your account
3. Create a new API key or use an existing one, and copy the generated key

### 🖥️ Backend Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/GinnasKJSCE/Crusaders.git
   ```

2. Navigate to the backend directory:
   ```bash
   cd NLP_Backend
   ```

3. Create a .env file:
   ```bash
   echo "HUGGING_FACE_API_TOKEN='your_hugging_face_api_token'" > .env
   echo "GEMINI_API_KEY='your_gemini_api_key'" >> .env
   ```

4. Install the required Python packages:
   ```bash
   pip install -r requirements.txt
   ```

5. Run the Flask backend:
   ```bash
   python -m flask --app app run
   ```

### 🎨 Frontend Setup

1. Navigate to the frontend directory:
   ```bash
   cd ../frontend
   ```

2. Install Node.js dependencies:
   ```bash
   npm install
   ```

3. Run the frontend application:
   ```bash
   npm run dev
   ```

## 🚀 Usage

1. Navigate to the application in your web browser
2. Upload the files you want to process
3. Use the chat interface to ask questions related to the uploaded files
4. Enjoy AI-powered insights and visualizations based on your documents

## 🐛 Troubleshooting

| Issue | Solution |
|-------|----------|
| Port conflicts | If default ports (5000 for backend, 5173 for frontend) are in use, specify different ports by setting environment variables or modifying configuration files |
| API key issues | Ensure your API keys are correctly set in the `.env` file and have the necessary permissions |
| Dependency problems | If you encounter issues with dependencies, try deleting `node_modules` and `package-lock.json` (for frontend) or `venv` (for backend) and reinstalling the dependencies |

## 👏 Acknowledgements

- [Hugging Face](https://huggingface.co/) for providing the API for natural language processing
- [Google AI Studio](https://aistudio.google.com/) for their generative AI API
- The open-source community for providing the tools and libraries that made this project possible
