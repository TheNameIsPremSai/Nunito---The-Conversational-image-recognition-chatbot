Nunito is an AI-powered multi-modal chatbot that integrates text processing, image recognition, and speech-to-text capabilities. It uses advanced Natural Language Processing (NLP), Image Recognition algorithms, and Speech Recognition to interact with users seamlessly.

Table of Contents
Overview
Features
Technologies Used
System Architecture
Setup Instructions
Usage
Screenshots
Future Enhancements
Contributors
License
Overview
Nunito is a smart conversational chatbot that processes multiple forms of input, including:

Text: Understanding and responding to natural language queries.
Images: Recognizing objects and text from user-uploaded images.
Voice: Converting speech into text and responding accordingly.
It is designed to deliver accurate answers, understand user intent, and enhance interactivity using a user-friendly interface.

Features
Text Processing:

Natural Language Understanding (NLU) with keyword detection.
Accurate responses to user queries with NLP techniques like Named Entity Recognition and Dependency Parsing.
Image Recognition:

Object detection using CNNs and YOLO/Faster R-CNN.
Identifying and describing objects in uploaded images.
OCR support for text recognition in images.
Voice Interaction:

Speech-to-text conversion using the Web Speech API.
Real-time voice input and processing for hands-free interaction.
Customizable UI:

Clean and responsive UI with light and dark themes.
Support for chat history, animations, and predictive analysis.
Technologies Used
Frontend
React.js: Framework for building the interactive user interface.
Vite: Optimized development environment for the frontend.
CSS: Customized styles with teal and skin-colored themes.
Backend
Node.js: Backend server for handling requests.
Express.js: RESTful API endpoints.
Gemini 1.5 Flash API: AI-powered processing of user inputs (text, images, voice).
Algorithms
Natural Language Processing (NLP): Tokenization, NER, POS Tagging, Dependency Parsing.
Image Recognition: CNNs, YOLO/Faster R-CNN for object detection.
Speech-to-Text: Web Speech API, Hidden Markov Model (HMM) for voice processing.
System Architecture
The project is modular and organized as follows:

NunitoText: Handles text-based input using NLP algorithms.
NunitoImg: Processes image uploads for object detection and OCR.
NunitoVoice: Supports real-time voice input and speech-to-text conversion.
Setup Instructions
Follow the steps below to set up the project locally:

Prerequisites
Ensure you have the following installed:

Node.js (v16+)
npm or yarn
Git
API Key for Gemini 1.5 Flash
Steps to Run Locally
Clone the Repository

bash
Copy code
git clone https://github.com/your-username/nunito.git
cd nunito
Install Dependencies
Run the following command to install project dependencies:

bash
Copy code
npm install
Set Up Environment Variables
Create a .env file in the root directory and add your Gemini API key:

env
Copy code
VITE_GEMINI_API_KEY=your_api_key_here
Run the Project
Start the development server with the following command:

bash
Copy code
npm run dev
Access the Application
Open your browser and visit:

arduino
Copy code
http://localhost:5173  
Usage
Text Interaction:

Type queries in the chatbot, and the AI will respond intelligently.
Image Interaction:

Upload an image to get object recognition results or extracted text.
Voice Interaction:

Use the microphone button to interact with the chatbot using speech.
Screenshots
Main Chat Interface


Image Upload and Recognition


Voice Interaction


Future Enhancements
Multi-language support for text and voice interactions.
Enhanced OCR accuracy with advanced deep learning models.
Integration of predictive analytics for smarter responses.
Voice Output for generating verbal responses.
