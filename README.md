# Whisper Subtitle Generator

A Python tool that automatically generates subtitles for WAV audio files using OpenAI's Whisper model.

## Features
- Automatically processes all WAV files in the working directory
- Generates SRT subtitle files
- Shows detailed progress with time estimates
- Supports Chinese language transcription
- Easy to use with minimal setup

## Requirements
- Python 3.7+
- ffmpeg

## Installation

1. Clone the repository:
```bash
git clone https://github.com/lwg1111/whisper-subtitle-generator.git
cd whisper-subtitle-generator
```

2. Install dependencies:
```bash
pip install -r requirements.txt
```

3. Install ffmpeg (on macOS):
```bash
brew install ffmpeg
```

## Usage
1. Place your WAV audio files in the same directory as the script
2. Run the script:
```bash
python generate_subtitles.py
```

## License
MIT License

## Author
WeiGuang Li