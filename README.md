
# Personalized Networking Assistant – RelationSphere

A lightweight AI-powered Personal CRM designed to help professionals organize and strengthen their networking relationships. RelationSphere enables users to manage contacts, track interactions, schedule follow-ups, and generate personalized outreach emails using Google Gemini AI.

---

## Overview

Professional networking is an essential part of career growth, but managing contacts and remembering follow-ups can be challenging. RelationSphere simplifies this process by providing a centralized platform to organize professional relationships and automate communication.

The application combines a FastAPI backend with a Streamlit frontend and uses SQLite for data storage. AI-powered email generation enhances productivity by creating personalized outreach messages based on user preferences.

---

## Features

- Contact Management
  - Add, edit, delete, and search professional contacts.
  - Store name, email, company, designation, and notes.

- Dashboard
  - View relationship statistics.
  - Monitor follow-up reminders.
  - Track networking activity.

- Interaction Logging
  - Record meetings and conversations.
  - Automatically update the last contacted date.
  - Calculate relationship status.

- AI Email Generator
  - Generate personalized outreach emails using Google Gemini AI.
  - Built-in fallback templates when AI is unavailable.

- Follow-up Tracking
  - Intelligent reminders for reconnecting with contacts.

- REST API
  - FastAPI backend with modular endpoints.

- Testing
  - Automated testing using Pytest.

---

## Technology Stack

### Frontend
- Streamlit

### Backend
- FastAPI
- Python

### Database
- SQLite
- SQLAlchemy ORM

### Artificial Intelligence
- Google Gemini 1.5 Flash API

### Testing
- Pytest
- HTTPX

---

## Project Structure

```
personalized-networking-assistant/
│
├── backend/
├── frontend/
├── models/
├── services/
├── database/
├── tests/
├── requirements.txt
├── app.py
└── README.md
```

---

## Installation

### Clone the repository

```bash
git clone https://github.com/yourusername/personalized-networking-assistant.git
```

### Navigate to the project

```bash
cd personalized-networking-assistant
```

### Install dependencies

```bash
pip install -r requirements.txt
```

### Run the application

```bash
python app.py
```

or

Backend

```bash
uvicorn backend.main:app --reload
```

Frontend

```bash
streamlit run frontend/streamlit_app.py
```

---

## Future Enhancements

- User Authentication
- Cloud Deployment
- Email Integration
- LinkedIn Import
- CSV Import
- Automated Follow-up Notifications
- Multi-user Support

---

## Project Outcomes

- Improved networking management
- Automated follow-up tracking
- AI-powered personalized email generation
- Lightweight and scalable architecture
- Simple and user-friendly interface

---

## Contributors

- Vinay Mohan
- C. S. Chirathanagandla
- Y. Durgaprasad
- A. Yeshwanth
- D. Hussain Z.

      
