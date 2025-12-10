[![Python](https://img.shields.io/badge/Python-3.8%2B-blue?style=flat-square&logo=python&logoColor=white)](https://python.org)
[![OpenCV](https://img.shields.io/badge/OpenCV-4.x-green?style=flat-square&logo=opencv&logoColor=white)](https://opencv.org)
[![Google API](https://img.shields.io/badge/Google%20API-Gemini-red?style=flat-square&logo=google&logoColor=white)](https://ai.google.dev)
[![License](https://img.shields.io/badge/License-Apache%202.0-orange?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/DeepMind-Craft/ai?style=flat-square&logo=github)](https://github.com/DeepMind-Craft/ai)
<p align="center">
  <img src="assets/real-time-detection-demo.gif" width="700" alt="Real-time AI description demo"/>
</p>

<div align="center">

### 🤖 Advanced AI Model That Describes What It Sees in Real-Time

**An intelligent system that observes your webcam and narrates the scene using cutting-edge AI**

[![Python](https://img.shields.io/badge/Python-3.8%2B-blue?style=flat-square&logo=python)](https://python.org)
[![License](https://img.shields.io/badge/License-Apache%202.0-green?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/DeepMind-Craft/ai?style=flat-square)](https://github.com/DeepMind-Craft/ai)

</div>

---

## 🌟 Project Overview

This project demonstrates a **Real-Time AI Image Description System** that analyzes live webcam feeds and generates intelligent scene descriptions instantly. The AI observes what's happening in front of the camera and **describes it in real-time**, with descriptions both displayed on screen and read aloud.

### 🔧 Technology Stack

- **🐍 Python** – Powerful programming language for AI applications
- **🎬 OpenCV** – Fast and efficient webcam video capture
- **🔷 Google API** – Advanced AI model for scene understanding
- **🔊 pyttsx3** – Real-time text-to-speech narration

### 💡 Use Cases

- 🎯 **Real-time object recognition** demonstrations
- ♿ **Assistive technology** for visually impaired individuals
- 🎓 **Educational tool** to showcase AI perception capabilities
- 📱 **Interactive applications** and accessibility features

---

## ⚡ Key Features

✨ **Real-Time Processing**
- 🎥 Continuous webcam feed analysis
- ⚙️ Optimized frame processing for smooth performance
- 💻 Clean, intuitive user interface

🧠 **AI-Powered Intelligence**
- 📝 Intelligent scene descriptions using Gemini AI
- 🌐 Context-aware analysis
- 🎯 Accurate object recognition

🔊 **Accessibility Features**
- 🔊 Automatic text-to-speech narration
- 📢 Customizable voice parameters
- 🎧 Real-time audio feedback

⚡ **Performance & Optimization**
- 🚀 Fast processing on standard hardware
- 📊 Adjusted resolution for optimal speed
- 💾 Memory-efficient frame handling

---

## 🎯 Project Scope

### What It Does Now

| Feature | Status | Details |
|---------|--------|---------|
| 📹 Live Webcam Feed | ✅ | Real-time video capture and processing |
| 🤖 AI Scene Description | ✅ | Intelligent analysis using Google Gemini |
| 🔊 Audio Narration | ✅ | Automated text-to-speech output |
| 💻 User Interface | ✅ | Simple controls and visual feedback |

### Future Enhancements

🔮 **Phase 2 - Enhanced Intelligence**
- 🎯 Multi-AI model support for better accuracy
- 🧠 Fine-tuned models for specialized domains
- 📊 Scene analysis metrics and statistics

🔮 **Phase 3 - Advanced Tracking**
- 🎨 Object detection with visual highlighting
- 🎬 Motion tracking and trajectory analysis
- 👁️ Attention mapping showing AI focus areas

🔮 **Phase 4 - Extended Features**
- 🎤 Voice command support for interactive queries
- 📹 Video recording with embedded descriptions
- 🔐 Privacy-preserving on-device processing options

🔮 **Phase 5 - Accessibility & Deployment**
- 📱 Mobile app (iOS/Android)
- 🌐 Web interface for browser access
- 🐳 Docker containerization
- 🌍 Multi-language support

---

## 📋 Requirements

```
✓ Python 3.8 or higher
✓ Google Gemini API key
✓ Webcam (USB or built-in)
✓ Microphone & speakers
✓ Internet connection
```

---

## 🚀 Quick Start

### 1️⃣ Installation

```bash
# Clone the repository
git clone https://github.com/DeepMind-Craft/ai.git
cd ai

# Create virtual environment
python -m venv venv
source venv/bin/activate  # Windows: venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt
```

### 2️⃣ Configuration

```bash
# Set your API key
export GEMINI_API_KEY="your_api_key_here"
```

Get your API key from: https://console.cloud.google.com/

### 3️⃣ Run the Application

```bash
python app.py
```

### 🎮 Controls

| Key | Action |
|-----|--------|
| **Q** | Quit application |
| **S** | Save snapshot |
| **M** | Mute/unmute audio |

---

## 📸 How It Works

```
1. 📹 Capture → Webcam sends live video frames
2. 🤖 Analyze → AI model analyzes the scene
3. 📝 Describe → Gemini generates description
4. 🔊 Narrate → Text-to-speech reads it aloud
5. 📺 Display → Results shown on screen
```

---

## 🛠️ Technical Details

**Architecture:** Real-time streaming pipeline with asynchronous processing

**Dependencies:**
- `🐍 opencv-python` – Computer vision and image processing
- `🔷 google-generativeai` – Google Gemini AI model access
- `🔊 pyttsx3` – Text-to-speech synthesis
- `🔐 python-dotenv` – Environment configuration management

**Performance:**
- Processes multiple frames per second
- Optimized resolution (640x480) for speed
- Minimal latency between capture and narration

---

## 📝 Important Notes

⚠️ **Cost Consideration** – Google Gemini API calls are charged per request

⚠️ **Connection Required** – Internet connection needed for AI processing

⚠️ **Audio Output** – Requires working speakers or headphones

💡 **Tip** – Start with a lower frame rate for faster initial setup

---

## 📄 License

Licensed under the Apache License 2.0 - see [LICENSE](LICENSE) file for details

---

<div align="center">

### 🌟 Support This Project

If you find this useful, please ⭐ star the repository!

**Made with ❤️ for accessibility and AI education**

[Report Issue](https://github.com/DeepMind-Craft/ai/issues) • [Request Feature](https://github.com/DeepMind-Craft/ai/discussions) • [Documentation](https://github.com/DeepMind-Craft/ai/wiki)

</div>
