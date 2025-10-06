 **Zena - Voice Assistant in Python**

Zena is a simple voice-controlled personal assistant built using Python. It can greet you, search Wikipedia, open websites, play music, and tell the current time — all through voice commands.

**Features**

🔊 Text-to-Speech (TTS) – Uses pyttsx3 to speak responses.

🎤 Speech Recognition – Captures your voice and converts it to text.

🌐 Wikipedia Search – Fetches short summaries from Wikipedia.

💻 Web Automation – Opens popular sites like Google, YouTube, and Stack Overflow.

🎵 Music Player – Plays local songs from a specified directory.

⏰ Time Query – Announces the current time.

📧 Email Sender – Sends emails via Gmail (requires configuration).

**Requirements**

Install all required libraries before running the script:

pip install pyttsx3

pip install SpeechRecognition

pip install wikipedia

pip install pyAudio

pip install pipwin

**Note**: If pyaudio installation fails, use:

pip install pipwin

pipwin install pyaudio

**Setup**
1. Replace the email credentials in sendEmail() with your own Gmail ID and app password:
   
server.login('your_email@gmail.com', 'your_app_password')

2. Update the music directory path

**Running the Assistant**

python zena.py

Command	Action

"Open Google"	Launches Google in your default browser

"Search Wikipedia for Python"	Reads a summary of Python from Wikipedia

"Play music"	Plays a song from your specified folder

"What’s the time?"	Tells you the current time

"Open YouTube"	Opens YouTube in your browser
