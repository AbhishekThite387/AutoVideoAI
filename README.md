# AutoVideoAI 🎬🤖

## Overview

AutoVideoAI is an AI-powered video generation platform that automatically creates short videos from a user-provided topic or keyword.

The system generates video scripts, collects relevant media assets, creates voice narration, generates subtitles, and combines everything into a final high-quality video.

---

## Features

- AI-powered script generation
- Automatic video creation
- Subtitle generation
- Text-to-Speech voice narration
- Background music integration
- Multiple video formats (9:16 and 16:9)
- FastAPI-based backend
- Docker support
- Web-based user interface

---

## Tech Stack

### Backend

- Python
- FastAPI

### AI Services

- LLM Integration
- Prompt Engineering

### Media Processing

- FFmpeg
- Subtitle Generation

### Deployment

- Docker
- Docker Compose

---

## Project Architecture

1. User enters a topic or keyword.
2. AI generates a video script.
3. Relevant media assets are collected.
4. Voice narration is generated.
5. Subtitles are created automatically.
6. FFmpeg combines assets into the final video.
7. User downloads the generated video.

---

## Installation

```bash
git clone https://github.com/yourusername/AutoVideoAI.git

cd AutoVideoAI

pip install -r requirements.txt
```

---

## Run Application

```bash
python main.py
```

or

```bash
docker compose up
```

---

## Future Improvements

- Multi-language support
- Advanced voice cloning
- YouTube auto-upload
- AI thumbnail generation
- Custom video templates

---

## Author

Abhishek Thite

---

## License

This project is intended for educational and learning purposes.
