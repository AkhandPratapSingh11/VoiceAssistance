# Voice Assistance Chatbot 🤖🎙️

## Project Overview

Voice Assistance is an interactive AI-powered chatbot that enables seamless voice-based communication using OpenAI's advanced language and speech technologies. Users can interact with the chatbot through both text and voice inputs, receiving intelligent responses with audio playback.

## Features

- 🗣️ Speech-to-Text Transcription
- 💬 AI-Powered Conversational Responses
- 🔊 Text-to-Speech Audio Generation
- 🌐 Web Interface using Streamlit

## Technologies Used

- Python
- OpenAI API
- Streamlit
- Whisper (Speech Recognition)
- Text-to-Speech API

## Prerequisites

- Python 3.8+
- OpenAI API Key
- Streamlit
- Required Python Packages

## Installation

1. Clone the repository:
git clone https://github.com/AkhandPratapSingh11/VoiceAssistance.git
cd VoiceAssistance

2. Create Virtual Environment (Recommended)
# For Windows
python -m venv venv
venv\Scripts\activate

# For macOS/Linux
python3 -m venv venv
source venv/bin/activate

3. Install Dependencies
pip install -r requirements.txt

4. Configure OpenAI API Key
Create a .env file in the project root and add your OpenAI API key:
OPENAI_API_KEY=your_openai_api_key_here

5. Run the Application
streamlit run app.py

