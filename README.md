# Description
An AI-powered mobile platform that diagnoses crop diseases from images and provides farm-level monitoring and analysis.


# CropCare AI

AI-powered mobile platform for crop disease detection and farm monitoring using plant images.

## Overview
CropCare AI is a capstone project that helps users diagnose crop diseases from plant images and monitor disease trends across farm zones.

The system is designed as a mobile application with the following goals:
- Detect crop diseases from uploaded or captured plant images
- Visualize disease regions and explain AI predictions
- Provide treatment recommendations and disease information
- Store diagnosis history by farm and zone
- Analyze disease trends through a dashboard
- Improve user engagement with a mascot-based attendance feature

---

## Key Features

### 1. Diagnosis
- Plant image upload or camera capture
- Image quality check before inference
- Disease classification
- Disease region detection
- Severity estimation
- Confidence display
- Grad-CAM visualization
- Treatment recommendation
- Disease detail page

### 2. History Management
- Diagnosis record storage
- Search and filter by date, crop, disease, and zone
- Action status tracking
  - Pending
  - Completed

### 3. Analytics Dashboard
- Severity trend analysis
- Disease frequency analysis
- Crop-wise disease analysis
- Zone-based disease map
- Risk zone highlighting
- Alert notifications

### 4. User Experience
- Mascot character
- Daily attendance check
- Mascot growth system

---

## Tech Stack

### Mobile App
- Flutter

### Backend
- FastAPI

### AI / ML
- Python
- PyTorch
- OpenCV
- YOLO / Classification Model
- Grad-CAM

### Database
- TBD

---

## Project Structure

```text
cropcare-ai/
├── mobile/          # Flutter app
├── backend/         # API server
├── ai/              # Model training and inference
├── data/            # Dataset metadata / preprocessing scripts
├── docs/            # Project documents
└── README.md

## Team Roles

### AI Engineer
Leads the AI development pipeline, including:
- Dataset preprocessing
- Disease classification model training
- Disease detection model training
- Severity estimation logic
- Grad-CAM visualization
- AI inference pipeline

### Backend Engineer
Leads the backend and data system development, including:
- API server development
- Database design and management
- History and analytics APIs
- Farm / zone management
- App-backend integration support

### Shared Responsibilities
Both team members collaborate on:
- Flutter UI development
- Testing and validation
- Presentation preparation
- Debugging and final polishing

---

## Development Plan

This project is planned as a 12-week capstone project.

### Phase 1 — Planning and Setup
- Requirement definition
- System architecture design
- Dataset analysis
- App skeleton setup

### Phase 2 — Core System Development
- AI model development
- API implementation
- Mobile UI development

### Phase 3 — Integration and Finalization
- Feature integration
- Dashboard implementation
- Testing and debugging
- Final presentation preparation

---

## Expected Impact

CropCare AI is designed to help non-expert users identify crop diseases early and manage farm health more effectively through AI-powered diagnosis, record management, and zone-based monitoring.

---

## Status

Project initialized.

---

## License

MIT License
