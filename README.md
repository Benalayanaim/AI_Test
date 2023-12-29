# Stress Detection Project

## Overview

This project aims to detect stress levels in individuals through facial analysis using computer vision techniques. The solution processes video input and provides stress scores based on various features such as blink, lip movement, emotions, and eyebrow movement.

## Features Implemented

- **Blink Detection**
- **Lip Movement Analysis**
- **Emotion Recognition**
- **Eyebrow Movement Analysis**

## Stress Calculation Formula

\[ \text{Final Stress} = 0.25 \times \text{Blink Stress} + 0.25 \times \text{Lip Movement Stress} + 0.25 \times \text{Emotion Stress} + 0.25 \times \text{Eyebrow Movement Stress} \]

## Requirements

- Python 3
- OpenCV
- MediaPipe
- Matplotlib

## Setup

1. Install required packages:

   ```bash
   pip install opencv-python mediapipe matplotlib

