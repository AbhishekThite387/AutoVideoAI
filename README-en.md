# AutoVideoAI 🎬🤖

An AI-powered video generation platform that automatically creates short videos from a user-provided topic or keyword.

## Features

- AI-generated video scripts
- Automatic subtitle generation
- Text-to-Speech voice narration
- Background music integration
- HD video generation
- Multiple aspect ratios (9:16, 16:9)
- FastAPI backend
- Docker support
- Web-based user interface

## Technology Stack

### Backend

- Python
- FastAPI

### AI Integration

- LLM APIs
- Prompt Engineering

### Media Processing

- FFmpeg
- Subtitle Generation

### Database

- MongoDB

### Deployment

- Docker
- Docker Compose

## How It Works

1. User enters a topic or keyword.
2. AI generates a video script.
3. Relevant media assets are collected.
4. Voice narration is generated.
5. Subtitles are created automatically.
6. Video assets are merged using FFmpeg.
7. Final video is generated and ready for download.

## Installation

```bash
git clone https://github.com/yourusername/AutoVideoAI.git
cd AutoVideoAI
pip install -r requirements.txt
```

## Running the Application

### Local Setup

```bash
python main.py
```

### Docker

```bash
docker compose up
```

## Project Structure

```text
AutoVideoAI/
├── app/
├── docs/
├── resource/
├── webui/
├── main.py
├── requirements.txt
├── docker-compose.yml
└── Dockerfile
```

## Future Enhancements

- Voice Cloning
- Multi-language Video Generation
- AI Thumbnail Generation
- YouTube Auto Upload
- Advanced Video Templates

## Author

Abhishek Thite

## License

This project is intended for educational and learning purposes.
