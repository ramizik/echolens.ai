# EchoLens AI

YouTube Demo:

[![EchoLens AI](https://img.youtube.com/vi/HJFwOpEGalA/0.jpg)](https://www.youtube.com/watch?v=HJFwOpEGalA)

EchoLens.AI is an innovative application designed to assist deaf and hard-of-hearing individuals by translating audio environments into accessible information. The system combines audio processing, emotion detection, and spatial awareness to provide a comprehensive understanding of the user's surroundings.

## ✨ Features

- **Speech Transcription**: Real-time speech-to-text conversion with contextual understanding
- **Sound Detection**: Identifies and classifies environmental sounds (doorbell, alarms, etc.)
- **Emotion Recognition**: Analyzes speech for emotional content and context
- **Spatial Audio Mapping**: Determines the direction and distance of sound sources
- **Interactive Sound Map**: Visualizes sound sources in a spatial representation showing direction, distance, and type
- **Directional Indicators**: Shows where sounds are coming from (North, South, East, West)
- **Visual Feedback**: Intuitive interface displaying audio information with customizable themes
- **AI-Powered Chat**: Contextual conversation with an AI assistant
- **Multimodal Analysis**: Combined audio/text and visual processing for enhanced understanding
- **Real-time Visualization**: Dynamic audio waveforms and particle effects
- **Spatial Environment Modeling**: 3D representation of sound locations

## 🚀 Getting Started

### Prerequisites

- Python 3.8+ for backend
- Node.js 14+ for frontend
- Google Gemini API key for AI features
- MongoDB (optional for persistent storage)

### Installation

1. Clone the repository
```bash
git clone https://github.com/yourusername/echolens-ai.git
cd echolens-ai
```

2. Set up the backend
```bash
cd backend
pip install -r requirements.txt
cp .env.example .env
# Edit .env file to add your GOOGLE_API_KEY
```

3. Frontend Launch
```bash
cd ../frontend
npm install
npm start
```

4. Backend Launch
```bash
cd ..
python echolens_api.py
```

## 🧠 Technology Stack

### Backend
- **Flask**: Web server framework with REST API endpoints
- **Flask-CORS**: Cross-origin resource sharing middleware
- **Python-dotenv**: Environment variable management
- **TensorFlow & TensorFlow Hub**: ML frameworks for audio processing
- **Google Generative AI (Gemini)**: Multimodal AI for analysis
- **SpeechRecognition**: Audio transcription engine
- **NumPy & SciPy**: Scientific computing and signal processing
- **Sounddevice**: Audio capture and playback
- **PyRoomAcoustics**: Spatial audio analysis
- **OpenCV & Pillow**: Image and video processing
- **PyMongo**: MongoDB database connectivity
- **Deepface**: Face and emotion detection (optional)
- **YAMNet**: Pretrained audio event classification model
- **Pytest**: Testing framework

### Frontend
- **React.js**: UI component library and framework
- **Material-UI (MUI)**: Design system and component library
- **Emotion**: CSS-in-JS styling
- **Framer Motion**: Animation and motion effects library
- **React Router**: Client-side routing
- **React Scripts**: Development toolchain
- **Custom Animation**: Pulse and ripple effects for audio visualization
- **Canvas API**: For drawing audio waveforms and particle effects
- **CSS Keyframes**: For custom animations and transitions

## 🔧 Architecture

EchoLens.AI consists of three main components:

1. **Audio Processing Engine**: Captures and analyzes audio input using microphone arrays and signal processing
   - Sound classification with YAMNet
   - Speech recognition with advanced audio processing
   - Directional audio analysis with spatial algorithms

2. **AI Analysis System**: Processes audio for context, emotion, and meaning
   - Google Gemini AI for multimodal analysis
   - Emotional context detection
   - Background noise filtering
   - Sound event classification

3. **Visual Interface**: Presents processed information in an accessible format
   - Interactive sound map showing sound sources
   - Directional indicators for spatial awareness
   - Emotion visualization with color coding
   - Real-time transcription with speaker identification
   - Custom animations for different sound types

## 🛠️ Development

### Running in Debug Mode

```bash
python app.py --debug --open-browser
```

## 📱 Usage

1. Start the application
2. Grant microphone and camera permissions when prompted
3. Use the main dashboard to view real-time audio transcription and sound detection
4. Navigate to the Sound Map to visualize spatial audio information
5. Check the Spatial Audio Visualizer for directional sound representation
6. Switch to Chat mode to have contextual conversations about the audio environment
7. Adjust visualization settings for optimal experience on your device


## 📜 License

This project is licensed under the MIT License - see the LICENSE file for details.

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## 🙏 Acknowledgements

- [Google Gemini AI](https://ai.google.dev/) for multimodal analysis
- [TensorFlow](https://www.tensorflow.org/) for machine learning capabilities
- [YAMNet](https://github.com/tensorflow/models/tree/master/research/audioset/yamnet) for audio classification
- [Material-UI](https://mui.com/) for UI components
- [Framer Motion](https://www.framer.com/motion/) for animations
- [PyRoomAcoustics](https://github.com/LCAV/pyroomacoustics) for spatial audio modeling 
