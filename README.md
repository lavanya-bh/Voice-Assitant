# NAARI Voice Assistant 👩‍💻🗣️📱

NAARI is an advanced Python-based voice assistant that can handle calls and messages, send emails, forecast weather, and perform web searches — all through natural voice interaction.

## 🎯 Objective

To build a smart, voice-enabled desktop assistant that supports daily and emergency tasks with a focus on real-world applicability, especially for safety, communication, and information needs.

## ⚙️ Core Features

- **🔊 Speech-to-Text and Text-to-Speech**: Uses `speech_recognition` and `pyttsx3` to interact naturally via voice.
- **📱 Contact via Twilio API**:
  - Send **SMS**
  - Make **automated phone calls** with a custom message
- **📧 Send Emails via SMTP**:
  - Compose and send emails using Gmail SMTP server
- **🌦️ Weather Forecast**:
  - Uses **OpenWeatherMap API** to provide live weather updates
- **🔎 Intelligent Web Search**:
  - Performs Google searches using the **Google Search API**
## 🧰 Technologies Used

- Python  
- `speech_recognition`, `pyttsx3`  
- `smtplib`, `email.message`  
- `twilio` for SMS and voice calls  
- `requests`, `json` for API calls  

## 🗣️ Example Voice Commands

- “Send a message to my friend's name”
- “Call my parents now”
- “Email my teacher about the assignment”
- “What’s the weather in Mumbai?”
- “Search for Top 10 Horror Places on Earth”

## 🚀 How to Run

1. Install dependencies:
   ```bash
   pip install speechrecognition pyttsx3 twilio wikipedia pyjokes requests
