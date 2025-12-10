# 🖼️ Real-Time AI Image Description

<p align="center">
  <img src="assets/real-time-detection-demo.gif" width="700" alt="Real-time AI description demo"/>
</p>

---

## 🌟 Project Overview

This project demonstrates a **Real-Time AI Image Description System** using a webcam. The AI model observes the live camera feed and **describes what it sees in real-time**. The descriptions are both displayed on screen and read aloud using text-to-speech technology.

The system leverages cutting-edge technologies to provide intelligent visual perception:

- **OpenCV** – Efficient webcam video capture and frame processing
- **Google Gemini AI (via API)** – Advanced natural language descriptions of scenes
- **pyttsx3** – Real-time audio narration with customizable voice parameters
- **API Integration** – Cloud-based AI processing with internet connectivity

### 💡 Perfect For
- Real-time object recognition and scene understanding demonstrations
- Assistive technology for visually impaired or blind users
- Educational purposes showcasing modern AI perception capabilities
- Interactive installations and accessibility applications

---

## ⚡ Key Features

| Feature | Description |
|---------|-------------|
| 🎥 **Real-Time Webcam Analysis** | Continuously processes video frames from your camera feed |
| 📝 **AI-Powered Scene Descriptions** | Uses Google Gemini AI to generate intelligent, contextual descriptions |
| 🔊 **Text-to-Speech Narration** | Automatically reads descriptions aloud with `pyttsx3` |
| 💻 **Intuitive User Interface** | Clean display showing live feed with on-screen instructions |
| ⚡ **Performance Optimized** | Tuned resolution and frame rate for smooth, lag-free operation |
| 🌐 **Cloud-Based Processing** | API-driven AI ensures intelligent, up-to-date scene analysis |
| 🎨 **Visual Feedback** | Status indicators and interactive controls for seamless user experience |

---

## 🔍 Scope of the Project

This project serves as a comprehensive demonstration of **how modern AI models perceive, interpret, and communicate visual information in real-time**. It bridges computer vision and natural language understanding.

### Current Capabilities
- Live webcam stream processing
- Scene understanding and description generation
- Audio output for accessibility
- Real-time performance on standard hardware

### Potential Extensions & Future Enhancements

**🎯 Accessibility & Assistive Technology**
- Integration with specialized assistive devices for visually impaired users
- Multi-language support for global accessibility
- Customizable speech speed and voice selection
- Braille output integration for enhanced accessibility

**🎬 Visual Tracking & Highlighting**
- Object detection and bounding box visualization
- Real-time highlighting of detected items in the video feed
- Motion tracking with trajectory visualization
- Attention mapping showing AI focus areas

**🧠 Advanced AI Processing**
- Multi-model ensemble for improved accuracy and redundancy
- Specialized models for medical, security, or industrial applications
- Custom fine-tuned models for domain-specific scenarios
- Comparative analysis using multiple AI backends

**📹 Recording & Analytics**
- Video recording with embedded descriptions
- Temporal analysis of scene changes
- Automated surveillance and monitoring systems
- Description logging for post-analysis and research

**🔐 Privacy & Security Features**
- On-device processing options to avoid cloud uploads
- Privacy masking for sensitive areas (faces, documents)
- Encrypted API communications
- Selective frame sampling for improved performance

**🎮 Interactive Features**
- User queries about specific objects ("What color is this?")
- Zoom and focus controls for detailed analysis
- Gesture recognition for hands-free control
- Real-time statistics dashboard showing processing metrics

**🌍 Deployment Options**
- Mobile app deployment for iOS/Android
- Web interface for browser-based access
- Edge computing for offline scenarios
- Docker containerization for easy deployment

---

## 📋 Requirements

- **Python 3.8+** – Latest stable version recommended
- **API Key** – Google Gemini AI API credentials
- **Internet Connection** – Required for cloud-based AI processing
- **Webcam** – Standard USB or built-in camera
- **Microphone/Speakers** – For text-to-speech audio output

---

## 🚀 Getting Started

### Installation Steps

```bash
# Clone or download the project
git clone https://github.com/yourusername/ai-image-description.git
cd ai-image-description

# Create virtual environment
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt
```

### Configuration

1. **Obtain API Key** – Get your Google Gemini API key from [Google Cloud Console](https://console.cloud.google.com/)
2. **Set Environment Variable** – Add your API key:
   ```bash
   export GEMINI_API_KEY="your_api_key_here"
   ```
3. **Configure Settings** – Adjust parameters in `config.py` as needed

### Running the Application

```bash
python main.py
```

- Press **Q** to quit the application
- Press **S** to save a snapshot
- Press **M** to mute/unmute audio

---

## 🛠️ Technical Stack

- **Computer Vision** – OpenCV for frame capture and processing
- **AI Model** – Google Generative AI (Gemini) API
- **Text-to-Speech** – pyttsx3 with offline synthesis
- **Language** – Python 3.8+
- **Architecture** – Real-time streaming with async processing

---

## 📝 Notes & Considerations

- API calls incur costs based on Google's pricing model
- Processing speed depends on internet connection quality
- Audio feedback requires functional speakers/headphones
- First startup may take additional time for dependency initialization

---

## 📄 License

This project is provided as-is for educational and research purposes.

---

**Created with ❤️ for accessibility and AI education**
