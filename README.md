# Gemini AI Chatbot Workshop

Welcome to the Gemini AI Chatbot Workshop repository! This project is part of a workshop I'm facilitating at the **Coding Ladies Academy** at the **Google AI Center, Accra, Ghana**. 

## 🚀 Project Overview
This is a simple, single-file web application that demonstrates how to interact with Google's Gemini AI API. The interface provides an easy way to experiment with AI-powered conversations in a clean, user-friendly environment.

## 🛠️ Prerequisites

- A modern web browser (Chrome, Firefox, Safari, or Edge)
- A Gemini API key (get it from [Google AI Studio](https://makersuite.google.com/app/apikey))
- Git (for cloning the repository)
- A code editor (VS Code, Sublime Text, etc.)

## 🚀 Getting Started

### Clone the Repository
```bash
git clone https://github.com/JoyTaribagshaw/gemini-ai-chatbot.git
cd gemini-ai-chatbot
```

### Run the Application
1. Open `index.html` in your preferred web browser by either:
   - Double-clicking the file in your file explorer
   - Or using a local server (recommended):
     ```bash
     # Using Python (pre-installed on most systems)
     python3 -m http.server 8000
     # Then visit http://localhost:8000 in your browser
     ```

2. Enter your Gemini API key when prompted
3. Start chatting with the AI!

## 🔒 Security Measures

1. **API Key Protection**
   - The API key is never stored on any server
   - It's only used in the browser's memory during your session
   - Always use environment variables for API keys in production

2. **Best Practices**
   - Never commit API keys to version control
   - Use environment variables for sensitive information
   - Consider using a backend service to manage API calls in production

3. **Rate Limiting**
   - The API has rate limits
   - Be mindful of the number of requests you make
   - Implement error handling for rate limit responses

## 🏗️ Project Structure

```
gemini-ai-chatbot/
├── index.html      # Main application file
└── README.md       # This file
```

## 🤝 Contributing

This project is part of a workshop. If you have suggestions or find issues, feel free to open an issue or submit a pull request.

## 📝 License

This project is open source and available under the [MIT License](LICENSE).

## 🙏 Acknowledgments

- Thanks to Google for the Gemini API
- Special thanks to Coding Ladies Academy and Google AI Center, Accra for hosting this workshop

---

Facilitated by [Joy Taribagshaw](https://github.com/JoyTaribagshaw) at Coding Ladies Academy, Google AI Center, Accra, Ghana
