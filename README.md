# YouTube Video Summarizer App

## Project Overview
The **YouTube Video Summarizer App** is a Streamlit-based application designed to convert YouTube video transcripts into concise summaries. Leveraging the power of the Google Gemini API, this app provides users with quick and informative summaries of video content, making it easier to extract key information from lengthy videos.

## Key Features
- **User-Friendly Interface**: A simple and intuitive interface where users can input a YouTube video URL and receive a summary.
- **Automatic Transcript Extraction**: Utilizes the YouTube Transcript API to fetch and compile video transcripts seamlessly.
- **Summarization with Google Gemini**: Integrates Google Gemini’s generative capabilities to produce detailed and informative summaries.

## Use Case: Summarize Cooking Tutorials to Generate Recipes
Imagine needing to quickly get the recipe from a long cooking video. Instead of watching the entire video, users can simply input the video’s URL into the app and receive a concise summary of the recipe, saving time and effort. The app effectively extracts the essential steps, ingredients, and instructions from cooking tutorials, providing users with a clear and concise recipe.

## Technologies Used
- **Streamlit**: For building the web interface.
- **Google Gemini API**: For generating video summaries.
- **YouTube Transcript API**: For extracting video transcripts.
- **Python**: Core programming language used for developing the app.

## Implementation
The app processes a given YouTube URL to extract the video ID, fetches the transcript using the YouTube Transcript API, and generates a summary using a predefined prompt with Google Gemini. The resulting summary is displayed in a clean, readable format within the app.

## Current Limitations
- **Non-Specific URL Handling**: The app does not currently differentiate between cooking and non-cooking videos. As a result, summaries may be generated for any type of video, which might not be relevant if the content is unrelated to cooking.
  
## Planned Improvements and Next Steps
1. **Content Validation**: Implement a content validation mechanism to ensure that only cooking-related videos are processed. This could involve analyzing video metadata, titles, descriptions, or transcript content to confirm relevance.

2. **Multi-Domain Support**: Explore expanding the app’s capabilities to handle different types of video content beyond cooking, such as educational videos or tutorials, with customized prompts for each domain.

3. **User Feedback Integration**: Introduce a feedback loop where users can indicate if a summary is relevant or suggest improvements, allowing the app to learn and adapt over time.

## Conclusion
This project represents a starting point for developing an effective tool to summarize cooking tutorials into concise recipes. However, it is acknowledged that the current version is not optimized for cooking videos specifically, and future enhancements will focus on addressing this limitation.

---
