# ComfyUI API Testing

A Flask-based web interface for interacting with ComfyUI's API to generate images.

## Features
- Simple web UI for prompt input
- Integration with ComfyUI's API
- Asynchronous image generation and display

## Setup
1. Install dependencies:
   \`\`\`bash
   pip install -r requirements.txt
   \`\`\`
2. Ensure ComfyUI is running locally (default: http://127.0.0.1:8188)

## Usage
1. Run the Flask app:
   \`\`\`bash
   python run.py
   \`\`\`
2. Access the web interface at `http://localhost:5000`
3. Enter a prompt and submit to generate an image

## Configuration
Adjust ComfyUI API URL and other settings in `config.py`

## Note
This project is a work in progress and may be subject to changes and improvements.
