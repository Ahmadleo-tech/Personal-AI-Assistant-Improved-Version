Here's the updated description with the additional content:

---

## Personal Assistant Script

This Python script implements a basic voice-activated personal assistant named Tony using various libraries. It provides functionalities such as searching the web, sending emails, and opening applications based on voice commands.

### Features
- **Voice Interaction:** Uses `pyttsx3` for text-to-speech and `speech_recognition` for speech-to-text.
- **Web Search:** Searches for information using DuckDuckGo.
- **Web Navigation:** Opens websites like YouTube, Google, LinkedIn, Twitter, and GitHub.
- **Email Functionality:** Sends emails via Gmail using SMTP.
- **Music Playback:** Opens Spotify.
- **File and Application Access:** Opens files or directories on the local system.
- **Weather Forecast:** Provides weather updates and forecasts using the OpenWeatherMap API.
- **Face Recognition:** Uses OpenCV for face detection and recognition.

### Prerequisites
- Python 3.x
- Required Python libraries: `pyttsx3`, `requests`, `webbrowser`, `os`, `smtplib`, `speech_recognition`, `opencv-python`, `pyowm`, `yt_dlp`, `numpy`, `getpass`

### Installation
1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/personal-assistant.git
   ```
2. Install the required libraries:
   ```bash
   pip install pyttsx3 requests SpeechRecognition opencv-python pyowm yt_dlp numpy
   ```

3. Set up environment variables for sensitive data (e.g., email password):
   ```bash
   export EMAIL_PASSWORD='your_password'
   ```

### Usage
1. Run the script:
   ```bash
   python personal_assistant.py
   ```

2. The assistant will greet you and wait for voice commands. Use commands like:
   - "Open YouTube"
   - "Play music"
   - "Send email to sender person"
   - "Check weather in [city]"
   - "Add new face"
   - "Recognize face"

### Code Overview
- **Initialization:** Sets up the text-to-speech engine, configures voice settings, and initializes face recognition.
- **`speak` Function:** Handles speaking text aloud.
- **`wishMe` Function:** Greets the user based on the time of day.
- **`takeCommand` Function:** Listens to and recognizes voice commands.
- **`search_duckduckgo` Function:** Searches DuckDuckGo for information.
- **`sendEmail` Function:** Sends an email via Gmail.
- **`get_weather` Function:** Retrieves weather information using the OpenWeatherMap API.
- **`add_password` & `verify_password` Functions:** Manage and verify user passwords for added security.

### Contributing
Feel free to contribute by creating issues or submitting pull requests with improvements or additional features.

---

Feel free to adjust any details or add any additional instructions specific to your setup!

Here's a description you can use for your GitHub repository that outlines the key features and functionality of your project:

---

# TonyAI: Intelligent Personal Assistant

TonyAI is an advanced personal assistant application designed to assist users with various tasks using voice commands and face recognition. This project combines artificial intelligence with practical features, including weather reporting, email sending, YouTube video downloading, and more. Developed in Python, TonyAI utilizes various libraries and APIs to provide a seamless and interactive experience.

## Features

- **Voice Commands**: Interact with TonyAI using natural language voice commands.
- **Password Protection**: Secure access to the application with password functionality.
- **Face Recognition**: Add and recognize faces using OpenCV for personalized interactions.
- **Weather Reporting**: Retrieve current and forecasted weather information based on user preferences.
- **Email Sending**: Send emails directly from the application.
- **YouTube Video Downloader**: Download YouTube videos with the specified URL and save path.
- **Dynamic Responses**: TonyAI responds with personalized messages based on user interactions.

## Setup

1. **Clone the Repository**
   ```bash
   git clone https://github.com/yourusername/tonyai.git
   ```

2. **Install Dependencies**
   Ensure you have Python installed, then install the required packages:
   ```bash
   pip install pyowm pyttsx3 requests smtplib yt_dlp speech_recognition opencv-python numpy
   ```

3. **Configuration**
   - Set up your OpenWeatherMap API key in the `api_key` variable within the code.
   - Configure email settings for sending emails, and ensure that the email password is stored securely.

4. **Running the Application**
   Run the main script to start TonyAI:
   ```bash
   python tonyai.py
   ```

## Usage

- **Voice Commands**: Use natural language to issue commands such as "time", "date", "search", "weather", "face", "send email", "download", or "exit".
- **Face Recognition**: Add faces to the application and recognize them during live video feed.

## Contributing

Contributions are welcome! Please fork the repository and submit pull requests with improvements or bug fixes.


---

Feel free to modify this description to better fit your project's specifics or add any additional sections as needed.
