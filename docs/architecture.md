# FitFlow High-Level Architecture

The FitFlow redesign uses React Native for the mobile frontend and React Native Web/Expo for web support.

Node.js with NestJS/Express is used as the main backend.

Firebase Cloud Firestore is used to store user profiles, workout plans, nutrition information, progress data, and social data.

Firebase Authentication with Identity Platform is used for secure user authentication.

TensorFlow Lite is used for on-device AI functionality. Python with FastAPI can be used for more complex AI processing.

Firebase/Google Cloud Storage is used to store food images, profile pictures, and other files.

Redis can be used for caching frequently accessed data.

Firestore real-time listeners and WebSockets support real-time community features and updates.
