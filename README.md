# Free-Alexa: Your Personal Voice Assistant

Programmers can get anything for free, even Alexa. Building your own (hot) personal assistant — how cool that is!

## Overview

This project provides a Python-based voice assistant application that mimics the functionalities of popular voice assistants like Alexa. Users can interact with the assistant by speaking commands prefixed with "Alexa". The assistant can perform tasks such as playing music from YouTube, providing the current time, fetching information from Wikipedia, telling jokes, and more.

## Features

- Speech recognition using the `speech_recognition` library
- Text-to-speech conversion using the `pyttsx3` library
- Integration with `pywhatkit` for playing YouTube videos
- Retrieval of current time and date using `datetime`
- Access to Wikipedia for fetching information
- Entertainment with random jokes fetched using `pyjokes`

## Requirements

Ensure you have the following Python libraries installed:

- `speech_recognition`
- `pyttsx3`
- `pywhatkit`
- `wikipedia`
- `pyjokes`

You can install these libraries via pip:

```
pip install speechrecognition pyttsx3 pywhatkit wikipedia pyjokes
```

## Usage

1. Clone the repository to your local machine:

```
git clone https://github.com/yourusername/free-alexa.git
```

2. Navigate to the project directory:

```
cd free-alexa
```

3. Run the Python script:

```
python voice_assistant.py
```

4. Once the program is running, interact with it by speaking commands prefixed with "Alexa". For example:
   - "Alexa, play songname"
   - "Alexa, what is the time?"
   - "Alexa, tell me about Python"
   - "Alexa, tell me a joke"

5. Enjoy your personal voice assistant experience!

## Note

- This is a simple voice assistant application intended for educational and entertainment purposes.
- Voice recognition accuracy may vary based on environmental factors and microphone quality.
- Some functionalities, such as playing YouTube videos, require an active internet connections.
