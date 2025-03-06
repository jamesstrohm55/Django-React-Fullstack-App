# Django-React Fullstack Application

This is a full-stack web application built using Django for the backend and React for the frontend. The application allows users to register, log in, input text-based notes, view them, and delete notes. The frontend and backend are connected using Choreo.

## Features
- User Registration
- User Login & Authentication
- Create Text Notes
- View Saved Notes
- Delete Notes

## Tech Stack
- **Frontend**: React, JavaScript, HTML, CSS
- **Backend**: Django, Django REST Framework
- **Database**: SQLite/PostgreSQL
- **Integration**: Choreo

## Installation

### Backend Setup
1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd django-backend
   ```
2. Create and activate a virtual environment:
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   ```
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Run migrations and start the backend server:
   ```bash
   python manage.py migrate
   python manage.py runserver
   ```

### Frontend Setup
1. Navigate to the frontend directory:
   ```bash
   cd react-frontend
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3. Start the frontend server:
   ```bash
   npm start
   ```

## Connecting with Choreo
This application uses Choreo to connect the frontend with the backend. Ensure that:
- The backend API is deployed and accessible.
- The frontend is configured to communicate with the correct Choreo service endpoint.
- Authentication tokens are handled properly in API requests.

## Usage
1. Register a new user.
2. Log in with the created credentials.
3. Add new text-based notes.
4. View all saved notes.
5. Delete unwanted notes.

## Contributing
Feel free to fork the repository and submit pull requests.
