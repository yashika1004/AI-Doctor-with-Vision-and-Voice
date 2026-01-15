
🩺 AI Doctor with Vision & Voice (VocDoc)

AI Doctor with Vision & Voice is a multimodal AI-powered medical assistant that allows users to speak their symptoms and upload medical images.
The system analyzes voice + vision inputs and responds like a virtual doctor with text-based and spoken medical insights using advanced generative AI models.

🚀 Features

🎤 Speech-to-Text (STT) using Whisper (via Groq API)

🖼️ Medical Image Analysis using LLaMA 3 Vision (via Groq API)

🧠 Doctor-like AI Responses using custom medical system prompts

🔊 Text-to-Speech (TTS) for AI voice responses

🌐 Interactive Web UI built using Gradio

⚡ Fast inference with Groq’s high-performance LPU backend

🧰 Tech Stack

| Layer                 | Tools / APIs                     |
| --------------------- | -------------------------------- |
| Programming Language  | Python                           |
| UI Framework          | Gradio                           |
| Speech-to-Text        | Whisper-large-v3 (Groq API)      |
| Image + Text Analysis | Meta LLaMA 3 Vision (Groq API)   |
| Text-to-Speech        | gTTS                             |
| Environment & Audio   | dotenv, Pydub, FFmpeg, PortAudio |
| Dependency Management | Pipenv                           |

⚙️ Setup Instructions

1️⃣ Clone the Repository
git clone https://github.com/yashika1004/AI-Doctor-with-Vision-and-Voice.git
cd AI-Doctor-with-Vision-and-Voice


2️⃣ Set Environment Variables

Create a .env file in the project root:

GROQ_API_KEY=your_groq_api_key


3️⃣ Install Dependencies
Option 1: Using Pipenv (Recommended)
pipenv install
pipenv shell

Option 2: Using pip
pip install -r requirements.txt


4️⃣ Install Audio Dependencies (Windows Users)

FFmpeg
Download from: https://ffmpeg.org/download.html

Add FFmpeg to system PATH

PortAudio / PyAudio

pip install PyAudio-0.2.11-cp311-cp311-win_amd64.whl


🧪 How It Works – Modular Architecture

| Phase | Module                    | Description                                |
| ----- | ------------------------- | ------------------------------------------ |
| 1     | `brain_of_the_doctor.py`  | Analyzes medical images using LLaMA Vision |
| 2     | `voice_of_the_patient.py` | Captures and transcribes patient speech    |
| 3     | `voice_of_the_doctor.py`  | Converts AI response into speech           |
| 4     | `gradio_app.py`           | Combines all modules into a single UI      |

🎨 User Flow

1️⃣ Speak your symptoms
2️⃣ Upload a relevant medical image
3️⃣ AI processes voice + vision
4️⃣ Receive text + spoken AI doctor response

📸 Demo Preview

UI allows:

🎙️ Voice input for symptoms

🖼️ Image upload (skin issues, reports, etc.)

📄 AI-generated diagnosis-style response

🔊 Spoken medical explanation

🌟 Project Inspiration

This project demonstrates how multimodal generative AI can be used to build:

Voice-enabled assistants

Vision-based medical insight systems

Accessible AI-driven healthcare demos

It explores the future of intelligent, empathetic AI health assistants.

🔮 Future Improvements

🌍 Multilingual support (Hindi, regional languages)

🗂️ User history & conversation logs

☁️ Deployment on Hugging Face / Streamlit Cloud

🔐 HIPAA/GDPR-safe sandbox mode

📱 Mobile-friendly UI

👩‍💻 Author

Yashika Srivastava
🎓 B.Tech CSE (Data Science)
🔗 GitHub: https://github.com/yashika1004

📄 License

This project is released for educational and demonstration purposes only.
Not intended for real-world medical diagnosis or treatment.
=======
