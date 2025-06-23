# Multimodal AI Agent Video Summarizer 📽️

This project is a Streamlit web application that uses Google Gemini 2.0 Flash and Phidata to analyze and summarize video content. Users can upload a video file, ask questions about its content, and receive detailed, actionable insights powered by AI and supplementary web research.

## Features

- Upload video files (`.mp4`, `.mov`, `.avi`)
- Ask custom questions about the video content
- AI-powered analysis using Google Gemini and Phidata
- Supplementary web research via DuckDuckGo integration
- User-friendly Streamlit interface

## Setup

1. **Clone the repository**  

https://github.com/KUHELI08/Multimodal-AI-Agent-Video-Summarizer.git

2. **Install dependencies**  
pip install -r requirements.txt


3. **Set up your Google API key**  
- Create a `.env` file in the project root  and add your Google API key:
  ```
  GOOGLE_API_KEY="your-google-api-key"
  ```

4. **Run the app**
streamlit run video_summerizer.py


## Usage

1. Open the app in your browser.
2. Upload a video file.
3. Enter your question or insight request about the video.
4. Click "Analyze video" to receive an AI-generated summary and insights.

## Requirements

- Python 3.8+
- See [requirements.txt](requirements.txt) for all dependencies.

## Notes

- The app uses temporary files to process uploaded videos.
- Make sure your Google API key has access to Gemini models.

## License

