# TranscribeNow
This repository contains the source code for a Single-Page Audio Transcription Application built using Spring Boot (backend) and Vite (frontend). The application allows users to upload audio files and receive the transcription in real-time by leveraging  OpenAI's transcription services.
## Features
- Single Page Application (SPA): No database or complex backend storage, purely for audio upload and immediate transcription.
- Audio Upload: Supports uploading audio files in various formats (MP3, WAV, etc.).- 
- Transcription: Converts audio to text using OpenAI's API.
- Minimal Setup: Simple architecture focused on functionality without the need for persistent storage.
  ## Technologies
### Backend
- Spring Boot: Backend API for processing audio and interacting with Azure OpenAI.
-  OpenAI: Provides the transcription service.
### Frontend
- Vite: Fast frontend development environment.
- React: UI framework for creating a responsive and simple user interface.
## Prerequisites
- Java 17 or higher installed.
- Node.js installed (with npm or Yarn).
- OpenAI API key.
## Setup
### Backend (Spring boot)
Clone the repository:
 ```
 git clone https://github.com/Satvinder9955/TranscribeNow.git
  ```
navigate to the backend directory
```
cd TrancribeNow-backend
```
Update the application.properties file with your OpenAI API key:
```
.openai.api.key=your_openai_api_key
```
Run the project to check if the key works

### Frontend (vite)
navigate to the backend directory
 ```
cd TrancribeNow-frontend
  ```
install the dependencies
```
npm install
```
Start the development server:
```
npm run dev
```
---

## Deployment

To deploy the application:

1. **Backend**: 
   - Package the Spring Boot application using Maven:
     ```bash
     ./mvnw clean package
     ```
   - Deploy the generated `.jar` file on a server or cloud platform (e.g., AWS, Heroku).

2. **Frontend**:
   - Build the frontend:
     ```bash
     npm run build
     ```
   - Deploy the built frontend files (in the `dist` folder) to any static hosting service (e.g., Netlify, Vercel).

---

## Contributing

Feel free to contribute by opening a pull request:

1. Fork the repository.
2. Create a new branch for your feature:
   ```bash
   git checkout -b feature-name

3. Commit your changes:
   ```
   git commit -m "Add feature"
   ```
4. Push to the branch:
   ```
   git push origin feature-name
   ```
5. open a pull request

