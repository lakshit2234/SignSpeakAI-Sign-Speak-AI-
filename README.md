SignSpeakAI – Bridging Speech & Sign Language with AI
🌟 Overview
SignSpeakAI is an AI-powered system designed to enhance communication between speech and sign language users. It integrates real-time gesture recognition, Speech-to-Sign (STS), and Text-to-Speech (TTS) using deep learning techniques. The system enables seamless translation between spoken words and sign gestures, improving accessibility for the deaf and hard-of-hearing communities.

🚀 Features
✔ Real-time Hand Gesture Recognition – Uses MediaPipe & LSTM-based deep learning model
✔ Speech-to-Sign Conversion (STS) – Converts spoken words into corresponding sign images
✔ Text-to-Speech (TTS) – Converts text input into natural-sounding speech
✔ Multilingual Support – Recognizes and translates speech across different languages
✔ User-Friendly Interface – Provides an intuitive and interactive experience

🏗 Implementation
Hand Gesture Recognition: Utilizes MediaPipe Hands to extract hand landmarks and classify gestures using an LSTM model trained on custom datasets.

Speech-to-Sign (STS): Recognizes speech with SpeechRecognition and maps words to sign images.

Text-to-Speech (TTS): Converts text into audio using gTTS and plays it with Pygame.

🛠 Tech Stack & Libraries
🔹 Python – Core programming language
🔹 TensorFlow/Keras – Deep learning model for gesture recognition
🔹 OpenCV – Real-time video processing
🔹 MediaPipe – Hand landmark detection
🔹 SpeechRecognition – Converts spoken words into text
🔹 gTTS (Google Text-to-Speech) – Converts text into speech
🔹 Pygame – Plays generated speech audio
