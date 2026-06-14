# Jarvis Voice Assistant

A Python-based voice assistant that responds to the wake word "Alexa" and executes voice commands.

## Features

- **Wake Word Detection**: Always listening for "Alexa" to activate
- **Voice Commands**: 
  - Open websites (YouTube, Google)
  - Launch apps/files by name
  - Play music from predefined library
  - Exit assistant
- **Text-to-Speech**: Speaks responses using pyttsx3

## Files

- `main.py` - Core assistant logic with speech recognition and command handling
- `music_lib.py` - Music library with song names mapped to URLs

## Requirements

```bash
pip install speechrecognition pyttsx3 pyaudio
```

## Usage

```bash
python main.py
```

Say "Alexa" to wake the assistant, then give a command like:
- "Open YouTube"
- "Play song"
- "Open notepad"
- "Exit"

## Note

The `useless` folder contains duplicate files and virtual environments - safe to delete.
