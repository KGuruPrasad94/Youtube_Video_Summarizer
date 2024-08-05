# YouTube Video Summarizer App

Project Overview:
The YouTube Video Summarizer App is a Streamlit-based application designed to convert YouTube video transcripts into concise summaries. Leveraging the power of the Google Gemini API, this app provides users with quick and informative summaries of video content, making it easier to extract key information from lengthy videos.

Key Features:

	•	User-Friendly Interface: A simple and intuitive interface where users can input a YouTube video URL and receive a summary.
	•	Automatic Transcript Extraction: Utilizes the YouTube Transcript API to fetch and compile video transcripts seamlessly.
	•	Summarization with Google Gemini: Integrates Google Gemini’s generative capabilities to produce detailed and informative summaries.
	•	Real-Time Image Display: Displays the thumbnail image of the YouTube video for visual confirmation.
	•	Error Handling: Robust error handling to manage invalid URLs and API errors gracefully.

Use Case: Summarize Cooking Tutorials to Generate Recipes
Imagine needing to quickly get the recipe from a long cooking video. Instead of watching the entire video, users can simply input the video’s URL into the app and receive a concise summary of the recipe, saving time and effort. The app effectively extracts the essential steps, ingredients, and instructions from cooking tutorials, providing users with a clear and concise recipe.

Technologies Used:

	•	Streamlit: For building the web interface.
	•	Google Gemini API: For generating video summaries.
	•	YouTube Transcript API: For extracting video transcripts.
	•	Python: Core programming language used for developing the app.

Implementation:
The app processes a given YouTube URL to extract the video ID, fetches the transcript using the YouTube Transcript API, and generates a summary using a predefined prompt with Google Gemini. The resulting summary is displayed in a clean, readable format within the app.

This project demonstrates practical application of generative AI and web development skills, showcasing an innovative approach to content summarization that can be extended to various domains.
