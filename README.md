
# 🧠 SARA - Smart Alzheimer’s Reminder Assistant

SARA is a secure, multilingual reminder system tailored for medical and caregiving scenarios, especially to assist patients with Alzheimer's or memory-related conditions.

---

## 🔐 Features

- 💬 **Voice-based medication & appointment reminders**
- 🌐 **Multilingual support** (English, Hindi, Kannada) using Google Text-to-Speech (gTTS)
- 🔑 **Twilio OTP authentication** for secure login/register
- 📅 **Smart scheduling** with APScheduler
- 👤 **User registration, login, and session management**
- 🧠 **Cognitive-friendly UI** with accessibility in mind
- 📜 **History log** of all past reminders

---

## 🛠 Tech Stack

| Layer       | Technologies Used                            |
|-------------|-----------------------------------------------|
| **Backend** | Flask (Python)                                |
| **Frontend**| HTML, CSS, JavaScript                         |
| **Voice**   | Google Text-to-Speech (gTTS)                  |
| **Database**| SQLite (can be upgraded to PostgreSQL)        |
| **Auth**    | Twilio OTP API                                |
| **Scheduler**| APScheduler                                  |
| **Voice Input**| SpeechRecognition + PyAudio                |

---

## 📌 Future Improvements

- 📊 **Health Stats Dashboard**
- 📍 **Geofencing with Alerts**
- 📧 **Email/SMS Summary Reports**

---

## 🚀 How to Run

1. **Clone the repository**
   ```bash
   git clone https://github.com/DiyaJannu/sara.git
   cd sara
