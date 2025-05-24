# 🧠 Body Language Interpreter

An AI-powered system for interpreting human body language using computer vision and machine learning.

![Demo](docs/assets/demo.gif)

## 📚 Table of Contents

- [Project Overview](#project-overview)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Model Details](#model-details)
- [Dataset and Training](#dataset-and-training)
- [Project Structure](#project-structure)
- [Examples](#examples)
- [Future Work](#future-work)
- [License](#license)
- [Acknowledgements](#acknowledgements)

---

## 📌 Project Overview

The **Body Language Interpreter** aims to bridge the gap between non-verbal communication and machine perception. By analyzing human posture and movement, this project detects and classifies body language cues that reflect emotional and psychological states.

Use cases:
- Assistive technology for individuals with social impairments
- Human-computer interaction (HCI) enhancements
- Psychological studies and behavioral analysis
- Surveillance and security monitoring

---

## 🚀 Features

- Real-time webcam support
- Frame-by-frame video processing
- Human pose detection using MediaPipe
- Feature vector generation from body landmarks
- Emotion or behavior classification (e.g., confident, anxious)
- Visual feedback overlay on frames
- Export of processed video with prediction labels

---

## 💾 Installation

### Requirements

Install Python (>= 3.8), then:

```bash
pip install -r requirements.txt
