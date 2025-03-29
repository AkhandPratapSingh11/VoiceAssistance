# OpenAI Conversational Chatbot 🤖

This is a voice-enabled chatbot powered by OpenAI's GPT-3.5-turbo and Whisper models, built using Streamlit. Users can interact with the chatbot using both voice and text, and the chatbot responds with both text and generated speech.

## 🚀 Live Demo  
[Click here to try the app!](https://voiceassistance1.streamlit.app/)


## 🚀 Features
- **Conversational AI**: Uses OpenAI's GPT-3.5-turbo for generating responses.
- **Speech-to-Text**: Converts user voice input into text using OpenAI's Whisper model.
- **Text-to-Speech**: Generates audio responses using OpenAI's TTS model.
- **Streamlit UI**: Provides an interactive and user-friendly interface.
- **Floating Microphone**: Uses `streamlit-float` to keep the microphone accessible.

## 🛠️ Installation

### 1. Clone the Repository
```bash
git clone https://github.com/AkhandPratapSingh11/VoiceAssistance.git
cd VoiceAssistance
```

### 2. Create a Virtual Environment (Recommended)
```bash
python -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate`
```

### 3. Install Dependencies
```bash
pip install -r requirements.txt
```

### 4. Set Up OpenAI API Key
Create a `.env` file in the root directory and add your OpenAI API key:
```
openai_api_key=your-api-key-here
```
Alternatively, set the environment variable:
```bash
export OPENAI_API_KEY="your-api-key-here"
```

## 🏃‍♂️ Running the Application
```bash
streamlit run app.py
```
This will open the chatbot in your default web browser.

## 📂 Project Structure
```
VoiceAssistance/
│-- app.py               # Main Streamlit application
│-- utils.py             # Helper functions for OpenAI API calls
│-- requirements.txt     # Required dependencies
│-- .gitignore           # Ignores sensitive files
│-- .env                 # API key storage (should not be committed)
```

## 🔧 How It Works
1. The chatbot greets the user.
2. Users can type or use the microphone to ask a question.
3. The question is processed using OpenAI's models:
   - Whisper converts audio to text.
   - GPT-3.5-turbo generates a response.
   - TTS converts the response into speech.
4. The response is displayed and played back as audio.

## 📌 Dependencies
- `streamlit`
- `openai`
- `python-dotenv`
- `audio_recorder_streamlit`
- `streamlit-float`

## 🛡️ Security Best Practices
- **Never expose your API keys in the repository**. Use `.env` files or secret management tools.
- **Add `.env` to `.gitignore`** to prevent accidental commits.
- **Revoke and regenerate keys** if they are accidentally exposed.


## 🤝 Contributing
Feel free to fork the repository, create a branch, and submit a pull request!

---
🔗 **GitHub Repository:** [VoiceAssistance](https://github.com/AkhandPratapSingh11/VoiceAssistance)

