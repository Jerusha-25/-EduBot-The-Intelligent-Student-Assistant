# Project Title: EduBot-The-Intelligent-Student-Assistant

# EduBot: The Intelligent Student Assistant

## Overview

EduBot is an advanced chatbot designed to assist students with their academic inquiries. By leveraging web scraping, natural language processing, and text-to-speech technology, EduBot provides accurate, context-aware responses in both text and audio formats.

## Features

### 1. Web Scraping
- **Real-Time Information Retrieval**: EduBot can fetch the latest information from Google Search based on user queries. This ensures that the responses are up-to-date and relevant.
- **Snippet Extraction**: The bot extracts concise snippets from search results, providing users with quick answers without overwhelming them with information.

### 2. Natural Language Processing
- **Contextual Understanding**: Utilizes the Microsoft Phi-2 model to generate responses that are contextually relevant to the user's questions.
- **Dynamic Response Generation**: The chatbot can generate answers based on both user input and additional context from web scraping or uploaded documents.

### 3. Text-to-Speech Conversion
- **Audio Responses**: EduBot converts text responses into speech using the gTTS (Google Text-to-Speech) library, allowing users to listen to answers instead of just reading them.
- **Interactive Experience**: The audio feature enhances user engagement, making the interaction more dynamic and accessible.

### 4. PDF Support
- **Document Upload**: Users can upload PDF files containing relevant academic material. EduBot extracts text from these documents to provide context for answering questions.
- **Enhanced Contextual Responses**: By utilizing the content of uploaded PDFs, EduBot can deliver more informed and specific answers.

## User Interaction Options

When interacting with EduBot, users can choose from the following options:

1. **Text Input**: 
   - Users can type their questions directly into the chat interface.
   - Example: "What is the theory of relativity?"

2. **Upload PDF for Context**: 
   - Users can upload a PDF document that EduBot will read to extract relevant information.
   - Example: "Please upload your PDF file now."

3. **Clear PDF Context**: 
   - Users can clear any previously uploaded PDF context, allowing for a fresh start.
   - Example: "PDF context cleared."

4. **Exit**: 
   - Users can choose to end the session at any time.
   - Example: "Chatbot: Goodbye!"

## Output Format

- **Text Output**: EduBot provides responses in text format, which can be read directly in the chat interface.
- **Speech Output**: EduBot also converts the text responses into audio, which is played back to the user, enhancing the interaction.

### Example Interaction

```plaintext
Welcome to EduBot: The Intelligent Student Assistant!
You can ask your academic questions or choose additional input methods.

Select option:
1. Text input
2. Upload PDF for context
3. Clear PDF context
4. Exit
Enter choice (1-4): 1
You: What is the theory of relativity?
Chatbot: The theory of relativity, developed by Albert Einstein, consists of two theories: special relativity and general relativity...
