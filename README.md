# FitFlow Redesign

FitFlow is a redesigned fitness tracking application created as part of the IT3060 Human Computer Interaction module.

## Project Objectives

The redesigned FitFlow system aims to provide:

- AI-powered personalized workout plans
- Nutrition tracking using computer vision
- Social community functionality
- Real-time fitness challenges
- Progress tracking
- Secure health-related data management
- Android, iOS and web support

## Technology Stack

### Frontend
- React Native
- TypeScript
- React for web

### Backend
- Node.js
- NestJS

### AI Service
- Python
- FastAPI
- TensorFlow Lite

### Database
- PostgreSQL

### Real-Time Services
- Firebase

### Authentication
- Firebase Authentication

### Caching
- Redis

## Repository Structure

frontend/
backend/
ai-service/
docs/
diagrams/

## Architecture

The FitFlow architecture follows a modular service-oriented approach.

The React Native application communicates with the NestJS backend through secure REST APIs.

AI processing is handled by a separate FastAPI service.

PostgreSQL stores structured application data while Firebase provides real-time social functionality.

Redis is used for caching frequently requested data.

## Author

IT3060 – Human Computer Interaction
BSc (Hons) Information Technology