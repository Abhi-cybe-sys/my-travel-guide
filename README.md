# ✈️ AI Travel Guide

An AI-powered travel guide that generates informative descriptions of tourist destinations using Google Gemini AI and converts them into spoken audio using Murf AI.

## 🌟 Features

- **AI-Generated Travel Information:** Get descriptions of tourist destinations, including their history, cultural significance, and interesting facts.
- **Summary and Detailed Modes:** Choose between a concise overview and a more detailed explanation.
- **Multilingual Support:** Designed to support English, Hindi, Tamil, and Telugu.
- **AI Voice Narration:** Convert generated descriptions into speech using Murf AI.
- **Voice Selection:** Choose from available voice options.
- **Audio and Text:** Read the generated description and listen to the narration.

## 🛠️ Technologies Used

- Python
- Flask
- HTML
- CSS
- JavaScript
- Google Gemini API
- Murf AI Falcon API
- Flask-CORS

## 📁 Project Structure

```text
travel-guider/
├── app.py
├── index.html
├── index.js
├── requirements.txt
├── .gitignore
└── README.md
```

## ⚙️ Setup and Installation

### 1. Clone the repository

```bash
git clone YOUR_GITHUB_REPOSITORY_URL
cd YOUR_REPOSITORY_NAME
```

### 2. Install dependencies

```bash
pip install -r requirements.txt
```

### 3. Configure API keys

Create a `.env` file in the project root and add your API keys:

```env
GEMINI_API_KEY=your_gemini_api_key
MURF_AI_API_KEY=your_murf_api_key
```

Replace the example values with your own API keys. Never upload your `.env` file or expose your API keys publicly.

### 4. Run the backend

```bash
python app.py
```

### 5. Open the frontend

Open `index.html` in your browser or serve the frontend using a local development server, depending on your application configuration.

Ensure the frontend API URL points to the running backend.

## 🔑 API Requirements

This project requires API credentials for:
- Google Gemini AI
- Murf AI

Availability, usage limits, and pricing depend on the providers' current plans.

## 🌐 Live Demo

[Try Travel Guider here] 

## 🚀 Future Improvements

- Add more tourist destinations and languages.
- Improve error handling and loading indicators.
- Deploy the frontend and backend for public access.

## 👨‍💻 Author

**Name:** Veerabhi Vardhan

**GitHub username:** Abhi-cybe-sys

**GitHub:**(https://github.com/Abhi-cybe-sys)

**Project:** AI Travel Guide using Gemini AI and Murf AI

