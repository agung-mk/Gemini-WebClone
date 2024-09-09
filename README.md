# Gemini | WebClone

Gemini WebClone is a project built to replicate key features of the GeminiAI platform, allowing users to interact with an AI-powered chatbot via a simple web interface. This project is perfect for educational purposes and exploring web development and AI integration.

## 🎯 Key Features
- Clone of GeminiAI for AI-based web interactions
- API key-based integration for AI communication
- Simple and customizable interface with CSS animations for a sleek user experience

## ⚙️ Setup Instructions

If you encounter an error like **"API key not valid. Please pass a valid API key."**, follow these steps to resolve the issue.

### Step 1: Obtain Your API Key

1. Go to [Google AI Studio](https://aistudio.google.com/app/apikey).
2. Generate a new API key under the **API Key** section.

Your API key will look something like this: `AIzaSyDzgOdLlyl0peuWb-JGGiu2mvDhSbm0NwQ`

> **Note**: A temporary **Fire Key** is provided for you to use, but if it stops working, it has likely reached its usage limit. The API is free but has a limited number of requests.

### Step 2: Insert the API Key

1. Open your project in VS Code (or your preferred text editor).
2. Navigate to the `script.js` file.
3. Replace the placeholder in the `API_KEY` variable with your actual API key.

```javascript
// script.js
const API_KEY = 'PASTE-YOUR-API-KEY';  // Replace with your API key