# Real Time Hand Gesture Recognition 

# Overview

This project implements a **real-time hand gesture recognition system** using **MediaPipe Hands** and **OpenCV**. It detects and classifies various hand gestures, such as:

- 👍 **Thumbs Up**
- ✌️ **Peace Sign**
- 👌 **OK Sign**
- ☝️ **Index Finger Up**
- ✋ **Open Hand**
- ✊ **Fist (closes the application)**

# **Technologies Used**

- **Python**
- **OpenCV** (for video processing)
- **MediaPipe** (for hand landmark detection)
- **NumPy** (for mathematical operations)

# Installation

Follow these steps to set up the project on your local system:

### Prerequisites

Make sure you have Python installed on your system. You can download it from [python.org](https://www.python.org/downloads/).

### Install Dependencies

Run the following command to install the required dependencies:

```bash
pip install opencv-python mediapipe numpy
```

## Usage

1. Clone this repository:
   ```bash
   git clone https://github.com/abbhiii/Real-Time-Hand-Gesture-Recognition-using-OpenCV.git
   cd Real-Time-Hand-Gesture-Recognition-using-OpenCV
   ```
2. Run the script:
   ```bash
   python hand_gesture_recognition.ipynb
   ```
3. The webcam will start, and gestures will be detected in real-time.
4. **Make a fist to close the application** or press `q` to exit.

## Future Aspects

This project can be extended in the following ways:

- **Gesture-Controlled Interfaces**: Implement gesture-based navigation for applications, games, or smart home devices.
- **Sign Language Recognition**: Extend the system to recognize more complex hand gestures used in sign language.
- **Integration with AI**: Use deep learning models to improve gesture recognition accuracy.
- **Augmented Reality (AR) Applications**: Apply hand gesture recognition to control AR experiences.
- **Multi-Hand and Multi-Person Support**: Enhance the system to detect gestures from multiple hands simultaneously.

---

Happy coding! 🚀

