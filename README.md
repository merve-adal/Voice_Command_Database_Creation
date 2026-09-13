
```markdown
# Voice Command Database Creation

This project focuses on creating a database to store and manage voice commands within a user-friendly web application. The goal is to provide an efficient interface for users to record audio commands and retrieve them using voice recognition technology. The system facilitates audio storage, search capabilities, and playback features in both Turkish and English languages.

## 🚀 Features and Functionalities

* **User Authentication:** The system includes user registration (Sign Up) and login functionalities.
* **Audio Recording & Storage:** After logging in, users can record 3-second audio clips using the "Record Audio" (Ses Kaydet) button and store them in the database.
* **Multilingual Voice Search:** Users can search the database by speaking commands via microphone in both Turkish (using the "Turkish Search" menu) and English (using the "English Search" menu).
* **Audio Playback:** The audio files retrieved from the database (e.g., Air Conditioning.opus, aydinlatmayi.wav) are listed and can be listened to by pressing the "PLAY AUDIO" or "SES ÇAL" buttons.
* **Session Management:** Users can safely log out of the application using the "Logout" or "Oturumu Kapat" buttons.

## 💻 System Requirements

* **Operating System:** Windows 10 or later, macOS 10.15 or later, Linux.
* **Development Tools (IDE):** Visual Studio Code (or any preferred IDE).
* **Languages & Tools:** Python 3.7 or later and pip for Python package management.

## ⚙️ Installation Guide

Follow these steps to run the project on your local machine:

1. Download the project from GitHub by selecting "Download ZIP" from the "Code" section.
2. Use an IDE like Visual Studio Code, select "Open Folder" from the File menu, and open the `softwareLogin` folder inside the downloaded file.
3. Open the terminal and install the necessary libraries by typing the following command:
   ```bash
   pip install django pygame pandas SpeechRecognition pyaudio scipy sounddevice whitenoise

```

4. Navigate to the correct directory and start the development server by running the following commands:
```bash
cd .\softwareLogin
python manage.py runserver

```


5. Access the website by typing the following URL into your browser's address bar:
`http://127.0.0.1:8000/`

## 📖 Usage Instructions

* When you visit the site, a login screen appears. If you don't have an account, you can create one by clicking the signup button and following the password guidelines (e.g., your password must contain at least 8 characters).
* After logging in, you are redirected to the recording page where you can record your voice commands.
* You can search the database by clicking the "Turkish Search" or "English Search" buttons from the navigation bar.

## 👥 Contributors

* Recep Sami Özdemir 
* İbrahim Mert Günay 
* Muhammet Melikan Atalay 
* Merve Adalı 

```

```
