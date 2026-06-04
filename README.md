# 🎙️ SpeechTrans

**SpeechTrans** is an AI-powered speech translation system that automatically converts **English audio/video into natural Hindi speech**. It is designed for **video dubbing, accessibility, education, and cross-language communication**, enabling users to seamlessly translate spoken English content into Hindi.

---

## 🚀 Features

- 🗣️ **Speech Recognition** – Converts English speech into text.
- 🌐 **Language Translation** – Translates English text into Hindi using NLP and Machine Learning models.
- 🔊 **Speech Synthesis** – Generates natural-sounding Hindi audio output.
- 🎬 **Video Dubbing** – Supports dubbing English audio/video content into Hindi.
- 🤖 **AI-Powered Pipeline** – Built using Python, NLP, Speech Processing, and Machine Learning.
- ☁️ **Cloud & Offline Support** – Choose between local processing and cloud-based transcription.

---

## 🏗️ System Architecture

```text
English Audio/Video
          │
          ▼
 Speech Recognition
    (Whisper/OpenAI)
          │
          ▼
   English Transcript
          │
          ▼
 Hindi Translation
          │
          ▼
 Text-to-Speech (TTS)
          │
          ▼
   Hindi Audio Output
```

---

## 📂 Project Structure

```text
SpeechTrans/
│
├── streamlit_app.py      # Streamlit user interface
├── transcriber.py        # Backend transcription wrapper
├── requirements.txt      # Project dependencies
├── README.md             # Documentation
│
└── assets/               # Optional audio/video samples
```

---

## 🛠️ Technologies Used

- Python
- Streamlit
- OpenAI Whisper
- OpenAI Speech-to-Text API
- Natural Language Processing (NLP)
- Machine Learning
- Text-to-Speech (TTS)
- FFmpeg

---

## ⚙️ Installation

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/SpeechTrans.git
cd SpeechTrans
```

### 2. Create a Virtual Environment

#### Windows

```bash
python -m venv venv
venv\Scripts\activate
```

#### macOS/Linux

```bash
python -m venv venv
source venv/bin/activate
```

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

---

## ▶️ Running the Application

Start the Streamlit app:

```bash
streamlit run streamlit_app.py
```

The application will open automatically in your browser.

---

## 🔄 Available Modes

### 1. Local Mode (Offline)

Uses the OpenAI Whisper model locally.

**Requirements:**

- FFmpeg installed
- Sufficient CPU resources
- No API key required

**Advantages:**

- Works without internet
- No API usage costs

---

### 2. Cloud Mode (Recommended)

Uses the OpenAI Speech-to-Text API.

**Requirements:**

```bash
OPENAI_API_KEY=your_api_key
```

**Advantages:**

- Faster transcription
- Better performance on Streamlit Cloud
- Lower local resource usage

---

## ☁️ Deploying on Streamlit Cloud

1. Push the project to GitHub.
2. Connect the repository to Streamlit Cloud.
3. Add your API key in **Secrets**:

```toml
OPENAI_API_KEY="your_api_key"
```

4. Deploy the application.

---

## 🎯 Use Cases

- Video Dubbing
- Educational Content Translation
- Accessibility Solutions
- Podcast Localization
- Cross-Language Communication
- Content Creation

---

## 📸 Example Workflow

1. Upload an English audio/video file.
2. SpeechTrans transcribes the English speech.
3. The transcript is translated into Hindi.
4. Hindi speech is synthesized automatically.
5. Download or use the generated Hindi audio.

---

## 🤝 Contributing

Contributions are welcome!

1. Fork the repository
2. Create a feature branch

```bash
git checkout -b feature-name
```

3. Commit your changes

```bash
git commit -m "Add new feature"
```

4. Push to GitHub

```bash
git push origin feature-name
```

5. Open a Pull Request

---

## 📜 License

This project is licensed under the MIT License.

---

## 👨‍💻 Author

**Umang**

Final Year Project – AI-Based Speech Translation System

---

## ⭐ Support

If you find this project useful, please consider giving it a ⭐ on GitHub.
