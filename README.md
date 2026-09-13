# FitFlow Redesign

FitFlow is a fitness application redesign developed as part of the IT3060 Human Computer Interaction project.

The redesign focuses on improving personalization, motivation, social engagement, workout tracking, progress visualization, and nutrition tracking.

## Project Objectives

The main objectives of the FitFlow redesign are:

- Provide personalized AI-powered workout recommendations.
- Improve workout planning and logging.
- Provide clear progress tracking and visualization.
- Support social interaction and fitness challenges.
- Simplify nutrition tracking.
- Provide real-time notifications and updates.
- Provide a consistent and user-friendly experience across platforms.

## Key Features

- AI-powered personalized workout plans
- Workout planning and logging
- Progress tracking
- Community feed
- Social challenges
- Nutrition tracking
- Food image recognition
- Real-time notifications
- Personalized recommendations

## Technology Stack

### Frontend
React Native

### Backend
Node.js with Express

### Cloud and Real-Time Services
Firebase

### Authentication
Firebase Authentication

### AI and Machine Learning
TensorFlow Lite and Cloud AI Services

### Computer Vision
ML Kit

## Project Architecture

The FitFlow redesign follows a layered architecture consisting of:

1. React Native frontend
2. Node.js and Express backend
3. Firebase cloud and real-time services
4. Firebase Authentication
5. AI and machine learning services
6. ML Kit for computer vision
7. Cloud data storage

## Main User Flows

### Personalized Workout Plan

User → React Native → Node.js/Express → AI Services → Workout Recommendation → User

### Social Sharing

User → React Native → Node.js/Express → Firebase → Real-Time Community Feed

### Nutrition Tracking

User → React Native → ML Kit → Food Recognition → Firebase → Progress Dashboard

## Security

The architecture considers:

- User authentication
- Authorization and access control
- Secure API communication
- Protection of user information
- Privacy-focused AI processing
- Secure cloud storage

## Scalability

The architecture supports scalability through:

- Cross-platform development
- Cloud-based services
- Modular backend services
- Real-time cloud infrastructure
- Independent AI services
- Caching of frequently accessed data

## Repository Structure

```text
fitflow-redesign/
│
├── frontend/
│   ├── src/
│   ├── components/
│   ├── screens/
│   └── README.md
│
├── backend/
│   ├── controllers/
│   ├── routes/
│   ├── models/
│   ├── middleware/
│   └── README.md
│
├── ai-service/
│   ├── models/
│   ├── services/
│   └── README.md
│
├── docs/
│   ├── technology-comparison.md
│   ├── decision-matrix.md
│   ├── architecture.md
│   ├── architecture-diagram.png
│   └── ADR-001.md
│
├── .gitignore
├── README.md
└── LICENSE