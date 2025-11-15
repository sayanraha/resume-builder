<div align="center">

# 📄 AI Resume Builder (Full-Stack)

AI-Powered Resume Creation and Optimization using the MERN Stack

*Powered by essential web technologies and Google's AI:*

![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=node.js&logoColor=white)
![Express](https://img.shields.io/badge/Express.js-000000?style=flat-square&logo=express&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=flat-square&logo=tailwind-css&logoColor=white)
![Google Gemini](https://img.shields.io/badge/Google_Gemini-4285F4?style=flat-square&logo=google&logoColor=white)
![ImageKit](https://img.shields.io/badge/ImageKit-000000?style=flat-square&logo=imagekit&logoColor=white)

## LIVE - DEMO 🌐
Visit the 👉 [_LINK 🔗_](https://resumo-blue.vercel.app/)

</div>

---

## Table of Contents

- [Overview](#overview)
- [Key Features](#key-features)
- [Tech Stack](#tech-stack)
- [Architecture](#architecture)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
  - [Environment Variables](#environment-variables)
- [AI Capabilities](#ai-capabilities)
- [API Endpoints](#api-endpoints)
- [Deployment](#deployment)
- [Contributing](#contributing)
- [License](#license)
- [Support](#support)

---

## Overview

This **AI Resume Builder** is a comprehensive full-stack application built using the **MERN stack** (MongoDB, Express.js, React, Node.js). It leverages the power of the **Google Gemini API** to offer AI-driven content generation, resume parsing, and real-time optimization, making professional resume creation fast and efficient.

---

## Key Features

### 🤖 AI-Powered Tools
- **AI Summary Generator**: Automatically generate a compelling professional summary based on the user's experience data using Gemini.
- **AI Job Description Enhancer**: Rephrase and optimize bullet points in the work experience section for greater impact.
- **PDF Resume Parsing**: Upload an existing PDF resume, and the AI will extract and pre-fill the form data.

### 🎨 User Experience & Design
- **Real-time Live Editor**: Instant, simultaneous preview of the resume while editing.
- **Multiple Templates**: Choose from various professional, modern, and minimal design templates.
- **Customization**: Easily change the accent color and theme of the resume.
- **Secure Authentication**: User sign-up and login powered by JWT for saving multiple resumes.

### 🗃️ Utilities & Deployment
- **Image Upload (ImageKit)**: Profile picture handling with features like automatic face-focus and AI background removal.
- **PDF Download**: Export the final resume as a high-quality PDF.
- **Public Share Link**: Generate a unique URL for sharing the live, updated resume online.
- **MERN Stack API**: Robust RESTful API for handling user data, resume CRUD operations, and AI requests.

---

## Tech Stack

### Frontend (Client)
- **React.js (Vite)** - Fast development and modern frontend structure.
- **Tailwind CSS** - Utility-first CSS framework for rapid and responsive styling.
- **React Router DOM** - Declarative routing for navigation.
- **Axios** - Promise-based HTTP client.
- **React Hook Form** - Efficient form management.

### Backend (Server)
- **Node.js** - JavaScript runtime environment.
- **Express.js** - Minimalist web framework.
- **MongoDB Atlas** - Cloud-hosted NoSQL database.
- **Mongoose** - MongoDB object modeling for Node.js.
- **Google Gemini API** - AI integration for content generation and parsing.
- **JSON Web Token (JWT)** - For secure user authentication.
- **ImageKit SDK** - For managing image uploads and transformations.

### DevOps & Deployment
- **Vite** - Frontend build tool.
- **[Specify Deployment Platform, e.g., Hostinger, Vercel, Render]** - Hosting for the full-stack application.

---

## Architecture

The application follows a standard **Client-Server Architecture** typical of the MERN stack:

1.  **Client (React)**: Handles the user interface, routing, state management, and makes API calls to the Express server.
2.  **Server (Express/Node.js)**: Acts as the API layer, handles authentication, processes AI requests (Gemini), manages file uploads (ImageKit), and communicates with the database (MongoDB).
3.  **Database (MongoDB)**: Stores user credentials and all resume data (personal details, experience, skills, etc.).

---

## Getting Started

### Prerequisites

- Node.js (v18 or higher)
- npm or yarn
- MongoDB Atlas account
- Google Gemini API key
- ImageKit Public and Private API keys

### Installation

1. Clone the repository:
```console
git clone [https://github.com/your-username/ai-resume-builder.git](https://github.com/your-username/ai-resume-builder.git)
cd ai-resume-builder
```
2. Install client dependencies:
```console
cd client && npm install
```
3.Install server dependencies:
```console
cd ../server && npm install
```
### Environment Variables

**Client (.env)**
```console
VITE_BASE_URL = "http://localhost:3000"
```

**Server (.env)**
```console
JWT_SECRET="your_jwt_key"
MONGODB_URI="your_connection_string"
IMAGEKIT_PRIVATE_KEY="your_imagekit_privatekey"
OPENAI_API_KEY="your_openAi_apiKey"
OPENAI_BASE_URL= "openAibaseurl"
OPENAI_MODEL="openAiModel"
```
4. Start the development servers:
```console
# Terminal 1 - Start backend
cd server && npm start

# Terminal 2 - Start frontend
cd client && npm run dev
```
## Contributing

We encourage contributions! Please follow the steps below:

1. Fork the repository.
2. Create a new feature branch (git checkout -b feature/your-feature-name).
3. Commit your changes (git commit -m 'feat: Added awesome feature').
4. Push to the branch (git push origin feature/your-feature-name).
5. Open a Pull Request.

## License
This project is licensed under the MIT License. See the LICENSE file for details.

## Support
For support, email _sayan.raha.dev77@gmail.com_ or create an issue in the GitHub repository.

<div align="center">

**AI Resume Builder** - Build your professional resume, powered by AI. 🚀

**Made with ❤️ by <i>[Sayan Raha])</i>**

[⬆ Back to Top](#table-of-contents)

</div>
