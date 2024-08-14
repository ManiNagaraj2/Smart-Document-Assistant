# Smart Document Assistant Using Langchain,Google Generative AI,Hugging Face Transformers and Streamlit

## Overview

The Document Interaction Platform allows users to upload various types of documents (PDF, CSV, DOCX, TXT) and interact with them using text or voice queries. It supports both text-based and voice-based interactions, provides document summarization, and utilizes state-of-the-art language models and speech recognition technologies.

### Features
- **Versatile Document Support**: Supports PDF, CSV, DOCX, and TXT files.
- **Text Query**: Allows users to submit text queries to retrieve relevant information from the documents.
- **Voice Query**: Enables users to ask questions through voice commands.
- **Summarization**: Provides a summary of the document content.
- **Text-to-Speech**: Converts text responses into speech for auditory feedback.

## Technologies

- **LangChain**: Framework for managing and using language models.
- **Google Generative AI**: For generating answers based on document content.
- **FAISS**: Library for efficient similarity search and clustering.
- **Hugging Face Transformers**: For summarization using pre-trained models.
- **SpeechRecognition**: For speech-to-text conversion.
- **gTTS**: Google Text-to-Speech for converting text to speech.
- **Streamlit**: For building the interactive web interface.

## Installation

### Prerequisites

- Python 3.7 or higher
- Google API Key (for using Google Generative AI services)

### Install Required Packages

To set up the project, follow these steps:

1. **Clone the Repository**

   ```bash
   git clone https://github.com/ManiNagaraj2/Smart-Document-Assistant.git
   ```
   
2. **Install the necessary Python packages using requirements.txt:**

   ```bash
   pip install -r requirements.txt
   ```

## Configuraion
Set up Google API Key: Replace "YOUR_GOOGLE_API_KEY" in the code with your actual Google API key.

## Usage
### Running the Application
To run the Streamlit web application, use the following command:
```bash
streamlit run app.py
```

### Interacting with the Application
Upload a Document: Choose a file (PDF, CSV, DOCX, or TXT) using the file uploader.
Summarize Document: Click the "📋 Summarize Document" button to get a summary of the document.
Text Query: Select "📝 Text Query" and enter your query in the text input field.
Voice Query: Select "🎤 Voice Query" and click "🎙️ Record Voice Query" to ask questions using your voice.
Speak Answer: Use the "🔊 Speak Answer" button to listen to the response.

## Code Structure
smartdoc.ipynb: Jupyter notebook containing the core functionality for document processing, querying, and summarization.

app.py: Streamlit application for interactive document upload, query, and summarization.

