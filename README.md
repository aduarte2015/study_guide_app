![Screenshot 2024-12-06 162538](https://github.com/user-attachments/assets/aa860dd7-3021-4b3b-ba0f-743610815a23)
# Study Guide Generator with Audio and PowerPoint

This app generates a detailed study guide for a given theme or topic, creates an audio guide from the study guide, and generates a PowerPoint presentation with images related to the theme. It's built using OpenAI's GPT-4 for text generation, audio synthesis, and an image generation API for the PowerPoint slides.

## Features
- **Generate Study Guide**: Provide a theme or topic, and the app will create a detailed study guide.
- **Audio Guide**: The study guide is converted into an audio file (MP3 format) for easy listening.
- **PowerPoint Presentation**: A PowerPoint presentation is automatically generated with a title slide, content, and a related image.

## How It Works
1. **Study Guide Generation**: The app uses OpenAI's GPT-4 model to generate a detailed study guide based on the provided theme or topic.
2. **Audio Generation**: The generated study guide is converted into an audio file using OpenAI's Whisper API or another text-to-speech API.
3. **PowerPoint Generation**: The app generates a PowerPoint presentation with a title and content slide, including a generated image that represents the theme.

## Requirements
Before running the app, make sure you have the following libraries installed:

- `openai`
- `gradio`
- `python-dotenv`
- `requests`
- `pptx`

You can install them using pip:

```bash
pip install openai gradio python-dotenv requests python-pptx

