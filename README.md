# Project Nexus – AI-Powered Campus Assistant

## Overview
Project Nexus is a unified AI-powered campus platform designed to reduce
information overload for students by integrating intelligent email
summarization, live academic scheduling, and a smart lost & found system.
The platform focuses on automation, real-time updates, and student-centric
usability.

---

## Problem Statement
Students face multiple challenges in daily campus life:
- Long and cluttered college-wide emails
- Frequently changing class schedules
- Difficulty recovering lost personal items

These systems are fragmented, manual, and inefficient.  
Project Nexus solves these issues using AI-driven analysis and automation.

---

## Core Features
1. AI Mail Summariser (Daily Pulse)
2. Live Timetable & Academic Cockpit
3. AI-Based Lost & Found System

---

## 1. AI Mail Summariser (Daily Pulse)

### Description
The AI Mail Summariser automatically processes lengthy official emails and
converts them into short, actionable insights for students.

### Functionalities
- AI-assisted parsing of long college-wide emails
- One-sentence action items or notices
- Automatic email categorization:
  - Academic
  - Events
  - Urgent
- Priority scoring (Low to High)
- Deadline extraction
- Sentiment analysis
- Smart spam filtering
- Searchable email archive
- Personalized relevance ranking

### AI Techniques Used
- Natural Language Processing (NLP)
- Large Language Models (LLMs)
- Text classification and keyword extraction

### Student Impact
Reduces cognitive overload and ensures students never miss important
announcements or deadlines.

---

## 2. Live Timetable (Academic Cockpit)

### Description
The Live Timetable module provides students with a customizable academic
schedule supported by intelligent planning and real-time updates.

### Functionalities
- Customizable personal class schedule
- Real-time updates for:
  - Class cancellations
  - Room changes
- Multi-semester timetable views
- Exam countdown tracker
- Free period finder
- Conflict detection between classes
- Smart class reminders
- Calendar export support
- Professor office hours tracking
- Classroom occupancy status (planned)

### Intelligent Features
- AI-based study planner using free slots
- Deadline-to-timetable integration
- Automated class reminder notifications

### Student Impact
Helps students manage time effectively, avoid scheduling conflicts,
and use free academic time productively.

---

## 3. AI-Based Lost & Found System (Student Exchange)

### Description
The Lost & Found system enables efficient reporting and recovery of lost
items using AI-powered matching and smart notifications.

### Functionalities
- Report missing and found items
- Image upload with AI object recognition
- Automatic item category tagging
- Location-based item matching
- Timestamp tracking
- ML-based duplicate detection
- Smart notifications when items align
- Item status tracking (lost / found / returned)
- Reward system (future enhancement)

### AI Techniques Used
- Object recognition
- Category classification
- Similarity matching algorithms

### Student Impact
Significantly improves recovery rates of lost items and encourages
campus-wide collaboration.

---

## System Architecture

Frontend:
- HTML
- CSS
- JavaScript

Backend:
- Node.js
- Express.js

AI Layer:
- NLP models for text processing
- AI-based classification and recommendation models

Database:
- In-memory storage / MongoDB (optional)

The frontend communicates with backend APIs, which process data using AI
services and return intelligent responses.

---

## Technology Stack

- Frontend: HTML, CSS, JavaScript
- Backend: Node.js, Express.js
- AI & ML: NLP, object recognition models
- Tools: VS Code, GitHub

---

## How to Run the Project

1. Clone the repository
2. Navigate to the backend folder
3. Install dependencies:
   npm install
4. Add your API key in the `.env` file
5. Start the server:
   node server.js
6. Open `frontend/index.html` in the browser

---

## Future Enhancements
- Mobile application support
- Push notifications
- Campus-wide analytics dashboard
- Student reward and trust score system
- Integration with official college ERP systems

---

## Conclusion
Project Nexus does not introduce another campus app—it creates a connected
intelligent system that simplifies student life through automation and AI.
