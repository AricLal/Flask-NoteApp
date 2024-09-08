
# Flask Note-Taking Web Application

## Overview
This is a simple Flask web application that allows users to sign up, log in, and take personal notes. The app features user authentication and uses a SQLite database to store notes and user data.

## Features
- User registration and login with secure password hashing.
- Note-taking functionality for authenticated users.
- Bootstrap integration for responsive design.
- SQLite database management with SQLAlchemy.
- Flash messaging for user feedback on actions.

## Technologies Used
- **Python** (Flask framework)
- **Flask-Login** for user authentication.
- **SQLAlchemy** for database management.
- **SQLite** as the database.
- **HTML5**, **CSS3** (via Bootstrap 4) for the front-end design.
  
## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/your-repo-name.git
   ```

2. Navigate to the project directory:
   ```bash
   cd your-repo-name
   ```

3. Create a virtual environment:
   ```bash
   python -m venv venv
   ```

4. Activate the virtual environment:
   - On **Windows**:
     ```bash
     venv\Scripts\activate
     ```
   - On **macOS/Linux**:
     ```bash
     source venv/bin/activate
     ```

5. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

6. Run the application:
   ```bash
   flask run
   ```

7. Open your web browser and go to `http://127.0.0.1:5000/`.

## Project Structure
```bash
your-repo-name/
│
├── app/
│   ├── __init__.py      # Flask app setup
│   ├── auth.py          # Routes for authentication
│   ├── views.py         # Routes for main app views
│   ├── models.py        # Database models (User, Note)
│   └── templates/       # HTML templates for the frontend
│
├── static/              # Static files (CSS, JavaScript)
├── .gitignore           # Git ignore file
├── README.md            # Project readme file
├── requirements.txt     # Python dependencies
└── database.db          # SQLite database
```

## License
This project is open-source and available under the MIT License.
