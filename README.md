
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
2. **Install the dependencies**
   ```bash
   pip install -r requirements.txt

3.**Set environment variables Create a .env file and add your Twilio credentials:**
    ```bash
   TWILIO_SID=your_sid
   TWILIO_AUTH_TOKEN=your_token
   TWILIO_PHONE=your_twilio_phone

4. **Run the App**
   python app.py Then open  http://127.0.0.1:5000 in your browser.

 # 📷 Screenshots
 <img width="1871" height="880" alt="image" src="https://github.com/user-attachments/assets/441b68d6-c640-41f2-8fa4-3052465cfd28" />
<img width="1908" height="847" alt="image" src="https://github.com/user-attachments/assets/e846f78c-0726-45dd-ba89-da57fb237948" />
+Appointment
<img width="1463" height="865" alt="image" src="https://github.com/user-attachments/assets/5294b92d-54fc-42a1-af7c-2514756d63c3" />
+Medication
<img width="1494" height="882" alt="image" src="https://github.com/user-attachments/assets/4e05ec25-bd3d-4718-830b-ed4aeb913d3b" />


