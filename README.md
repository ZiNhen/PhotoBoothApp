 # Smart Photobooth System

![Status](https://img.shields.io/badge/status-active-brightgreen)
![Platform](https://img.shields.io/badge/platform-Raspberry%20Pi-blue)
![Language](https://img.shields.io/badge/language-Python-blue)

## Overview
A fully **Photobooth System** built on **Raspberry Pi + Python**, capable of capturing photos, processing them, uploading final images to the cloud, and generating QR codes for instant download.  
The system supports **AI-based gesture recognition** and uses **multithreading** to ensure fast, responsive interaction during events.

---

## Features
- Automated capture → processing → cloud upload pipeline  
- AI gesture recognition for touchless photo capture  
- Real-time gallery with auto-generated QR codes  
- Multithreaded camera, processing, and networking workflow  
- Customizable GUI for user interactions  
- Cloud-based image storage & instant retrieval  

---

## Tech Stack
- **Hardware:** Raspberry Pi, Raspberry Pi Camera Module V1  
- **Language:** Python  
- **Libraries:** OpenCV, NumPy, Requests, qrcode, Pillow  
- **Cloud:** Google Drive API
- **Tools:** Git, GitHub Actions, virtualenv, Visual Studio Code.  

## Installation / Setup
1. Connect the Raspberry Pi and attach the Camera Module.
2. Clone the branch `Nhan/merge_gif_feature` to your local machine:
   ```bash
   git clone -b Nhan/merge_gif_feature https://github.com/your_username/Photobooth.git
3. Open the project using Visual Studio Code (either on Raspbian OS or Windows).
4. Navigate to the AppInterface directory and run:
   python Main_Window.py
