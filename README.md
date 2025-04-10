# AI Chatbot with Gemini

This is a Python-based AI chatbot that uses Google's Gemini AI model. It provides both a web interface and a CLI interface for interacting with the AI.

## Features

- Web interface with a modern, responsive design
- CLI interface for testing and direct interaction
- Powered by Google's Gemini AI model
- Deployable to Vercel

## Setup

1. Install the required dependencies:
```bash
pip install -r requirements.txt
```

2. The application is configured to use environment variables from vercel.json for deployment.

## Usage

### Web Interface
To run the web interface:
```bash
python api/app.py
```
Then open your browser and navigate to `http://localhost:5000`

### CLI Interface
To use the CLI interface:
```bash
python api/app.py --cli
```
Type 'exit' to quit the CLI mode.

## Deployment

The application is configured for deployment on Vercel. The `vercel.json` file contains all necessary configuration, including environment variables.

## Project Structure

- `api/app.py`: Main application file containing both web and CLI interfaces
- `requirements.txt`: Python dependencies
- `vercel.json`: Vercel deployment configuration
- `README.md`: This file 