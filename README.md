# Alexa Voice Assistant

This is a simple voice assistant using Python that can recognize voice commands, respond with speech, and perform actions like playing YouTube videos, telling jokes, fetching Wikipedia summaries, and more.

## Features

- Listens for voice commands using `speech_recognition`.
- Responds with text-to-speech using `pyttsx3`.
- Plays YouTube videos with `pywhatkit`.
- Provides current time.
- Fetches Wikipedia summaries.
- Tells jokes using `pyjokes`.

## Requirements

Install the required Python libraries before running the script:

```sh
pip install speechrecognition pyttsx3 pywhatkit wikipedia pyjokes
```

## Usage

1. Run the script:

   ```sh
   python assistant.py
   ```

2. Speak commands starting with "Alexa", such as:
   - "Alexa play [song name]" → Plays a song on YouTube.
   - "Alexa what time is it?" → Tells the current time.
   - "Alexa who the heck is [person]?" → Gives a short Wikipedia summary.
   - "Alexa tell me a joke" → Tells a random joke.
   - "Alexa are you single?" → Responds humorously.

## Notes

- Ensure your microphone is working properly for accurate voice recognition.
- The assistant continuously listens for commands in a loop.
- You can modify the script to include additional commands.

## License

This project is open-source and free to use.
