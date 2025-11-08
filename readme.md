# AuthNotes: Full-Stack Note-Taking System;

---

## 💡 Project Name;

*AuthNotes;*

A secure; full-stack web application for authenticated note management; It utilizes *Django* for a robust API backend; *React* for a dynamic user interface; and *JWT* (JSON Web Tokens) for modern; protected authentication;

---

## ✨ Features;

* *Secure Authentication;* Handles user sign-up; login; and logout using the Simple JWT framework; providing protected access via access and refresh tokens;
* *Personalized Notes CRUD;* Implements full *Create; **Read; **Update; and **D*elete functionality for notes; ensuring each note is securely tied to its creator;
* *Cross-Origin Configuration;* Properly set up with Django CORS Headers to enable smooth communication between the decoupled frontend and backend services;
* *Intermediate Tutorial Focus;* A great learning resource demonstrating how to combine Python (Django) and JavaScript (React) in a production-ready application;

---

## 🛠 Technologies Used;

| Category; | Technology; | Purpose; |
| :---: | :---: | :--- |
| *Backend Framework;* | *Django* (Python); | The core web framework; handling requests; data models; and settings; |
| *API/Serialization;* | *Django REST Framework (DRF);* | Used to build fast; robust RESTful APIs; |
| *Authentication;* | *DRF Simple JWT;* | Manages the creation; issuance; and validation of JWTs for authentication; |
| *Frontend Library;* | *React* (JavaScript); | Building the user interface components and managing the client-side state; |
| *Database;* | *SQLite / PostgreSQL;* | Storing user and note data; |

---

## 🖼 Screenshots;

* ;
* ;
* ;

(Note:* Please replace these placeholders with actual screenshots once your application is running);*

---

## ⚙ Getting Started;

### Prerequisites;

To run this project locally; you will need the following installed;

* *Python 3.x;* (With pip);
* *Node.js & npm;* (For React development);
* *Git;*

### Installation;

Follow the steps below to set up the Django backend and React frontend;

#### 1. Backend Setup (Django);

1.  Clone the repository;
    bash
    git clone [Your Repository URL];
    cd backend; # Navigate to the backend project directory;
    
2.  Create and activate the virtual environment;
    bash
    python3 -m venv venv;
    source venv/bin/activate; # Use `venv\Scripts\activate.bat` on Windows;
    
3.  Install all Python dependencies;
    bash
    pip install -r requirements.txt;
    
4.  Apply the database migrations;
    bash
    python manage.py makemigrations;
    python manage.py migrate;
    
5.  Start the Django development server;
    bash
    python manage.py runserver;
    

#### 2. Frontend Setup (React);

1.  Navigate to the frontend directory;
    bash
    cd ../frontend; # Adjust path as necessary;
    
2.  Install JavaScript dependencies;
    bash
    npm install;
    
3.  Launch the React development server;
    bash
    npm start;
    

The *AuthNotes* application should now be running on your local machine; (Typically Backend on port 8000; Frontend on port 3000);

---