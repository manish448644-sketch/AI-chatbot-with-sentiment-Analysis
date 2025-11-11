“This project is an AI chatbot that understands the user's emotions from text and replies in an emotionally appropriate manner. I have used Python, Tkinter for GUI, Hugging Face Transformer model for emotion detection, and Ollama’s Mistral model for generating replies. The chatbot detects multiple emotions like joy, sadness, anger, fear, etc. and adjusts the reply tone accordingly.”

Key Features:

Emotion Detection using Transformers (NLP model):

Uses SamLowe/roberta-base-go_emotions

Detects top 3 emotions from user message

Shows emoji and emotion score

Dynamic AI Reply (Ollama + Mistral model):

Responds according to emotion tone (ex: calm if user is sad)

Uses chat history for contextual conversation

System Context Awareness:

Shows real-time time, battery %, CPU usage, and weather

Tkinter GUI Application:

Chat window with scroll

Send button and Enter key support

Messages displayed like real chat interface
