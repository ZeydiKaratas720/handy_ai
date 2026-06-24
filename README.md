# Handy AI
### Real-Time Gesture Intelligence Platform

Handy AI is a browser-based human-computer interaction platform that enables users to interact with digital environments through natural hand gestures. Using real-time computer vision and hand landmark tracking, the system transforms hand movements into visual, auditory, and interactive experiences without requiring any additional hardware beyond a webcam.

The project leverages Google's MediaPipe Hands framework to detect and track hand landmarks in real time, enabling gesture-driven interaction modes such as visual effects generation, shape recognition, and mid-air drawing.

---

## Overview

Handy AI explores the integration of computer vision, gesture recognition, and interactive graphics to create an intuitive and immersive user experience.

The platform processes live webcam input, extracts hand landmark data, interprets gesture patterns, and generates dynamic responses through a combination of visual effects, procedural animations, and audio feedback.

---

## Key Features

### Real-Time Hand Tracking
- Live hand detection using MediaPipe Hands
- Tracking of up to two hands simultaneously
- 21 landmark points per detected hand
- Low-latency gesture processing

### Play Mode
An interactive environment focused on gesture-driven visual effects.

Features:
- Pinch gesture recognition
- Dynamic particle systems
- Procedural ripple generation
- Multi-hand interaction effects
- Lightning-field generation between hands
- Real-time audio synthesis

### Shapes Mode
Recognition and visualization of predefined symbolic gestures.

Supported Gestures:
- Heart Gesture
- Peace Sign
- Star Burst Gesture

Each gesture triggers a dedicated procedural animation and visual response.

### Write Mode
A gesture-controlled drawing environment.

Features:
- Air-writing with index finger tracking
- Smooth path interpolation
- Persistent stroke rendering
- Gesture-based canvas clearing
- Pinch-based stroke completion

---

## System Architecture

```text
Webcam Input
      │
      ▼
MediaPipe Hands
      │
      ▼
Landmark Extraction
      │
      ▼
Gesture Recognition Layer
      │
      ├── Play Mode
      ├── Shapes Mode
      └── Write Mode
      │
      ▼
Visual & Audio Rendering Engine
      │
      ▼
User Interaction Feedback
```

---

## Technologies

### Computer Vision
- MediaPipe Hands

### Frontend
- HTML5
- CSS3
- JavaScript (ES6)

### Graphics & Rendering
- HTML5 Canvas API
- Procedural Animation Systems
- Particle Engine

### Audio
- Web Audio API

---

## Gesture Recognition Strategy

The system performs gesture analysis using spatial relationships between detected hand landmarks.

Examples include:

- Distance-based pinch detection
- Finger extension analysis
- Palm proximity estimation
- Landmark spread calculations
- Motion pattern recognition
- Directional wrist movement tracking

These techniques allow the platform to recognize user intent without requiring machine learning model retraining.

---

## Performance Characteristics

- Real-time processing
- Browser-native execution
- No backend dependency
- Hardware-independent deployment
- Low-latency interaction pipeline

Performance depends primarily on:
- Camera quality
- Browser optimization
- Device processing power

---

## Installation

Clone the repository:

```bash
git clone https://github.com/yourusername/handy-ai.git
```

Navigate to the project directory:

```bash
cd handy-ai
```

Launch a local server:

```bash
python -m http.server 8000
```

Open:

```text
http://localhost:8000
```

---

## Requirements

- Modern web browser
  - Google Chrome (recommended)
  - Microsoft Edge
- Webcam access
- JavaScript enabled

---

## Future Development

Planned improvements include:

- Custom gesture training
- Machine learning based gesture classification
- Multi-user interaction support
- Mobile device optimization
- Additional gesture libraries
- Gesture-based application control
- Performance analytics dashboard

---

## Research Areas

This project combines concepts from:

- Human-Computer Interaction (HCI)
- Computer Vision
- Gesture Recognition
- Real-Time Graphics
- Interactive Systems Design
- User Experience Engineering

---

## Author

**Dilara Karataş**

Computer Engineering Student

Areas of Interest:
- Embedded Systems
- Computer Vision
- Human-Computer Interaction
- Autonomous Systems
- Artificial Intelligence Applications

---

## License

This project is released for educational, research, and portfolio purposes.
