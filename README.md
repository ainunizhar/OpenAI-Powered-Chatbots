# 🪐 PlutoAI : One Chat at a Time.
by Songfurina

**Bachelor project · Bachelor in Computer Forensic (Hons), Management and Science University (2024)**

**PlutoAI** is an AI-powered chatbot built with OpenAI's GPT model and Streamlit, designed for seamless and intelligent interactions. Whether you're a coder, creative, or just curious, PlutoAI is here to simplify your queries and provide insightful responses.

## 🌟 Features

- **Smart Chat:** Powered by OpenAI's GPT for intelligent responses.
- **Clean UI:** Modern purple theme with a responsive design.
- **Clear Chatbox:** Automatically clears input after each message.
- **Reset Button:** One-click chat reset for starting fresh.
- **Chat History:** Displays past conversations.

## 🛠️ Tech Stack
- Backend AI: OpenAI GPT
- Frontend Framework: Streamlit
- Styling: Custom CSS for enhanced visuals

## 📦  Installation
1. **Clone this repository**
   ```bash
   git clone https://github.com/ainunizhar/OpenAI-Powered-Chatbots.git
   cd OpenAI-Powered-Chatbots
   ```
2. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```
3. **Set up your API key** in `.streamlit/secrets.toml` (generate your own key at
   https://platform.openai.com/account/api-keys):
   ```toml
   OPEN_API_KEY = "your_openai_api_key"
   ```
4. **Run the app**
   ```bash
   streamlit run main.py
   ```

## 📂 Project Files

- `main.py`: main application file.
- `requirements.txt`: dependencies.
- `.streamlit/secrets.toml`: where your OpenAI API key goes (never commit a real key).

## ✨ Usage

- Open the app in your browser (default: http://localhost:8501).
- Type a message in the input box and press Enter.
- View the bot's response and interact seamlessly.
- Use Clear Chat to reset the conversation.
