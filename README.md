# Youtubetranscriber using LLM MODEL
Develop a web application that takes a YouTube video link as input, extracts the video’s transcript, and generates a concise summary using a Large Language Model (LLM) like Google’s Gemini Pro.

Key Components
1. Frontend:
Streamlit: Utilized for creating an interactive and user-friendly web interface. Users can input the YouTube video link directly into the app.

2. Transcript Extraction:
YouTube Transcript API: This API is used to fetch the transcript of the provided YouTube video. The transcript is then processed to form a continuous text.

3. Summarization:
Google Gemini Pro API: The extracted transcript is sent to Google’s Gemini Pro model, which generates a concise summary of the video content. This helps in quickly understanding the main points of the video without watching the entire length.


Workflow
1. User Input: The user enters the YouTube video URL into the Streamlit app.
2. Transcript Retrieval: The app uses the YouTube Transcript API to fetch the transcript of the video.
3. Summarization: The transcript is sent to the Google Gemini Pro API, which processes it and returns a summarized version.
4. Display Summary: The summarized content is displayed on the Streamlit app for the user to read.
