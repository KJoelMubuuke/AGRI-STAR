#  Agri-Star

### AI-Driven Mobile-First PWA for Agricultural Disease Detection

![PWA](https://img.shields.io/badge/PWA-Mobile--First-green)
![Next.js](https://img.shields.io/badge/Next.js-App%20Router-black)
![Python](https://img.shields.io/badge/Backend-Python-blue)
![License](https://img.shields.io/badge/License-MIT-yellow)



##  Overview

**Agri-Star** is an AI-powered Progressive Web App (PWA) designed to empower farmers in Uganda with **real-time detection of plant and animal diseases**.

Built for **low-connectivity environments**, Agri-Star bridges the gap between advanced Machine Learning and practical farming needs—helping reduce crop loss and improve food security.



##  Key Features

*  **Offline-First Functionality**
  Works even with limited or no internet using Service Workers.

*  **Disease Detection System**
  Analyzes symptoms in crops and livestock using predictive logic.

*  **Mobile-First Design**
  Optimized for smartphones with an app-like experience.

*  **Lightweight & Efficient**
  Runs smoothly on low-end devices common in rural areas.


##  Tech Stack

### Frontend

* Next.js (App Router)
* Tailwind CSS

### State Management

* React Hooks (Context API)

### Backend / Logic

* Python-based processing (AI/ML logic)

### Architecture

* Progressive Web App (PWA)

### Deployment

* Docker (Containerized for scalability)



##  Software Engineering Principles

This project follows strong software construction practices:

*  **Fail-Fast Principle**
  Immediate error detection and handling.

* **Clean Code & Refactoring**
  Modular, maintainable codebase with minimal code smells.

*  **UML Modeling**
  Designed using Sequence and Class Diagrams.

*  **Well-Structured Documentation**
  Clear and organized for collaboration and scalability.



##  Project Structure

plaintext
agri-star/
├── src/
│   ├── app/           # Next.js routing & pages
│   ├── components/    # Reusable UI components
│   ├── lib/           # Logic & API utilities
│   └── styles/        # Tailwind & global styles
├── public/            # PWA assets (icons, manifest)
├── Dockerfile         # Container configuration
└── README.md


## Installation & Setup

### 1️ Clone the Repository
git clone https://github.com/KJoelMubuuke/AGRI-STAR.git
cd agri-star


### 2️ Install Dependencies

npm install


### 3️ Run Development Server
npm run dev

### 4️ Build for Production
npm run build




##  Usage

1. Open the application in your browser
2. Install it as a PWA (Add to Home Screen)
3. Input symptoms or relevant farm data
4. Receive disease insights and recommendations


##  Impact Vision

> “Technology should solve real problems.”

Agri-Star aims to:

* Support farmers with accessible AI tools
* Reduce agricultural losses
* Improve food security in Uganda and beyond



##  Future Improvements

*  Advanced AI/ML disease prediction models
*  Weather-based recommendations
*  Multi-language support (local languages)
*  Analytics dashboard




##  License

This project is licensed under the MIT License.



