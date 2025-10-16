# 🚧 Pothole Detection App

[![Flutter CI](https://github.com/faridahjiji/pothole-detection-app/actions/workflows/flutter-ci.yml/badge.svg)](https://github.com/faridahjiji/pothole-detection-app/actions)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

A Flutter mobile application that detects potholes using AI vision and sensor data to help prevent accidents and vehicle damage.

## 📱 Features

### 🔍 Camera-based Detection
- **Real-time Processing**: Uses MobileNet SSD v2 quantized model for live pothole detection
- **Bounding Boxes**: Marks detected potholes with visual indicators
- **Location Tagging**: Automatically saves GPS coordinates of detected potholes

### 📊 Sensor-based Detection  
- **LSTM Model**: Analyzes accelerometer data for vibration patterns
- **Real-time Graphs**: Visualize sensor data with live charts
- **Smart Detection**: Automatically counts and locates potholes during driving

### 🗺️ Interactive Map
- **Google Maps Integration**: Display all detected potholes
- **Detection Details**: View confidence levels and detection methods
- **Navigation**: Easy location tracking and pothole avoidance

## 🚀 Quick Start

### Prerequisites
- Flutter SDK 3.0.0+
- Android Studio / VS Code
- Google Maps API Key

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/faridahjiji/pothole-detection-app.git
   cd pothole-detection-app
