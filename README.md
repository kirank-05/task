# Task Management Web Application

This project is a web-based task management application developed using Flask, a lightweight web framework for Python. The application allows users to register, log in, and manage their tasks efficiently. It incorporates user authentication, task creation, viewing, and deletion functionalities.

## Key Features

- **User Registration and Authentication:**
  - Users can register with a unique username and password.
  - Registered users can log in to access their personalized task management dashboard.
  - Users can log out securely from the application.

- **Task Management:**
  - Authenticated users can create new tasks with a title and optional description.
  - Users can view a list of their tasks.
  - Users can delete tasks they no longer need.

- **Modern Front-End Design:**
  - The front-end is designed using Bootstrap to ensure a clean and responsive user interface.
  - Forms and task lists are styled with Bootstrap classes for a consistent look and feel.

## Technologies Used

- **Flask:** A micro web framework for Python, used for creating the back-end of the application.
- **Flask-SQLAlchemy:** An ORM (Object-Relational Mapping) library for managing the SQLite database.
- **Flask-Login:** A user session management library for handling user authentication.
- **Bootstrap:** A popular CSS framework for designing responsive and visually appealing user interfaces.

## File Structure
task_manager/ ├── app.py# Main application file ├── templates/ # HTML templates │ ├── index.html│ ├── login.html│ ├── register.html│ └── tasks.html└── models.py# (Optional) Separate file for database models


## How to Use

1. **Set Up the Environment:**
   - Create a virtual environment and activate it:
     ```bash
     python3 -m venv venv
     source venv/bin/activate  # On Windows use `venv\Scripts\activate`
     ```
   - Install the required libraries:
     ```bash
     pip install Flask Flask-SQLAlchemy Flask-Login
     ```

2. **Run the Application:**
   - Initialize the database and run the Flask application:
     ```bash
     python app.py
     ```
   - Access the application through `http://127.0.0.1:5000` in your web browser.


## Contributing

Contributions are welcome! Please fork this repository and submit a pull request for any improvements or bug fixes.

## Acknowledgments

- [Flask Documentation](https://flask.palletsprojects.com/)
- [Bootstrap Documentation](https://getbootstrap.com/)
- [Flask-SQLAlchemy Documentation](https://flask-sqlalchemy.palletsprojects.com/)
- [Flask-Login Documentation](https://flask-login.readthedocs.io/)

---

Feel free to customize and enhance the application to suit your specific needs! If you have any questions or need further assistance, just let me know.
