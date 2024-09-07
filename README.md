Project-V


Voice Sharing App (Pre-Alpha)

##Overview

The Voice Sharing App is an ongoing project that aims to allow users to record, upload, and share short voice recordings. This app will support a wide range of audio events such as songs, podcasts, speeches, debates, discussions, and even animal sounds. The project is currently in the **pre-alpha** stage, and many features are incomplete or still in development.

## Project Status: Pre-Alpha

⚠️ **Important**: This project is in the **pre-alpha** phase, which means it's not ready for production or general use. Features are being implemented, but the app is not yet functional. This repository serves as a work-in-progress and a learning opportunity for me, as I'm new to developing open-source projects.

## Features (Planned)

- **Voice Recording**: Record voice clips directly within the app.
- **Audio Uploading**: Upload recorded audio to a backend server for storage.
- **AI Content Moderation**: Check for inappropriate content in voice recordings (planned).
- **Short Audio Events**: Limit voice recordings to 20-second snippets for quick and easy sharing.

## Current Progress

- **Code Development**: The code for basic voice recording and uploading has been written with the help of **ChatGPT** and **Cursor**.
- **Backend Setup**: A simple Flask-based backend has been started to handle file uploads, but it's not fully integrated yet.

## Getting Started (For Developers)

### Prerequisites

- **Node.js** and **npm**: Required for running the React frontend.
- **Python** and **pip**: Required for running the Flask backend.

### Installation

1. Clone the Repository:

   ```bash
   git clone https://github.com/your-username/voice-sharing-app.git
   cd voice-sharing-app
   ```

2. Frontend Setup:

   Navigate to the frontend directory and install dependencies:

   ```bash
   cd voice-sharing-app
   npm install
   npm start
   ```

3. Backend Setup:

   Navigate to the backend directory, install dependencies, and run the Flask server:

   ```bash
   cd voice-sharing-backend
   pip install -r requirements.txt
   python app.py
   ```

### Project Structure

```bash
voice-sharing-app/
│
├── voice-sharing-app/           # React frontend folder
│   ├── public/                  # Public assets
│   ├── src/                     # Source files
│   │   ├── App.js               # Main React component
│   │   ├── VoiceRecorder.js     # Voice recorder component
│   └── package.json             # Frontend dependencies
│
├── voice-sharing-backend/        # Flask backend folder
│   ├── app.py                   # Flask app handling uploads and moderation
│   ├── uploads/                 # Directory where audio files will be saved
│   └── requirements.txt         # Backend dependencies (Flask, CORS, etc.)
└── README.md                    # Project documentation
```

## Contribution

This project is in its early stages, so feedback is welcome, but contributions may not be immediately accepted until the app reaches a more stable version. Feel free to **fork** the repository and experiment with it on your own.

## Future Goals

- **Complete Voice Recording**: Fully implement the voice recording feature.
- **AI Moderation**: Integrate AI moderation to detect inappropriate content in voice clips.
- **Backend Integration**: Complete the backend to handle storing and retrieving audio files.
- **Enhanced UI**: Improve the user interface for a better user experience.

## Acknowledgments

This project is being developed with the assistance of tools like **ChatGPT** and **Cursor**, which have helped generate and structure code throughout the process.

---

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

---

## Disclaimer

The app is currently in **pre-alpha** status and is **not ready for production**. Expect incomplete features and frequent updates.

---

### Pre-Alpha Release Notes

**Version**: `v0.1.0-pre-alpha`

- Initial commit with basic setup for recording and uploading audio.
- Basic **voice recording** component written in React.
- Flask backend to handle audio file uploads has been started, but not fully functional yet.
- Code generated and structured with assistance from **ChatGPT** and **Cursor**.
