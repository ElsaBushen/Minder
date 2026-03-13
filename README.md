# Minder

**Minder** is a mobile application designed to support individuals experiencing short-term memory loss by capturing, transcribing, and revisiting meaningful moments. The app allows users to record conversations and events, automatically transcribe them using AI-powered speech recognition, and securely store them for later reference.

The goal of Minder is to help users maintain continuity in their daily lives by providing an easy way to revisit important conversations and experiences.

---

## Key Features

- **Video and audio recording** to capture important moments  
- **AI-powered transcription** using speech-to-text services  
- **Conversation analysis** to extract useful context from recordings  
- **Cloud storage** for secure access to recordings and transcripts  
- **Cross-platform mobile application** built with Flutter  

---

## Technology Stack

### Frontend
- Flutter  
- Dart  

### AI / APIs
- OpenAI APIs for conversation analysis  
- Whisper speech-to-text transcription  

### Cloud
- AWS Amplify  
- AWS cloud storage  

### Development Tools
- Visual Studio Code  
- GitHub version control  

---

## Architecture Overview

1. The user records a conversation or important moment through the mobile application.  
2. The recording is processed and sent to **AI transcription services**.  
3. The transcription is analyzed to extract meaningful information.  
4. The recording and transcript are stored securely in **AWS cloud storage**.  
5. Users can later search, review, and revisit their recorded moments.

---

## Project Purpose

Minder was developed as a collaborative academic project focused on exploring how **AI, cloud services, and mobile applications** can be combined to build assistive technology for individuals experiencing memory challenges.

The project demonstrates the integration of **mobile development, AI services, and cloud infrastructure** to deliver a practical and impactful solution.

---

## Getting Started

### Prerequisites

Before running the application, make sure you have the following installed:

1. **Visual Studio Code (VS Code)**  
   Recommended IDE for Flutter development  
   https://code.visualstudio.com/

2. **Flutter SDK**  
   https://flutter.dev/docs/get-started/install

3. **Dart SDK**  
   Included with Flutter  
   https://dart.dev/

4. **AWS Account**  
   Required for cloud configuration  
   https://aws.amazon.com/getting-started/

---

## AWS Amplify Configuration

The project uses **AWS Amplify** to enable cloud capabilities such as authentication and storage.

### Install Amplify CLI

Ensure Node.js is installed, then run:

```bash
npm install -g @aws-amplify/cli
