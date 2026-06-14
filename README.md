# TechForge Tutorials

A comprehensive Django-based online learning platform for interconnected tech topics including Databases, Full Stack Web Development, Cloud Computing, Data Science, Machine Learning/AI, IoT Devices, and Cybersecurity.

## Features

- User registration and authentication with Django's built-in system
- Progressive learning with 7 core modules
- Lessons with text, video embeds, and code examples
- Interactive quizzes and hands-on projects
- User progress tracking and personalized recommendations
- Community forum for discussions
- Resources section with downloads
- Admin panel for content management
- Responsive design with Bootstrap 5
- PostgreSQL database with SQLite fallback


## Installation

1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd techforge
   ```

2. Create a virtual environment:
   ```bash
   python -m venv venv
   ```

3. Activate the virtual environment:
   - Windows: `venv\Scripts\activate`
   - macOS/Linux: `source venv/bin/activate`

4. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

5. Configure the database:
   - For PostgreSQL: Update `DATABASES` in `techforge/settings.py` with your database credentials
   - For SQLite: No changes needed (default)

6. Run migrations:
   ```bash
   python manage.py makemigrations
   python manage.py migrate
   ```

7. Create a superuser:
   ```bash
   python manage.py createsuperuser
   ```

8. Run the development server:
   ```bash
   python manage.py runserver
   ```

9. Access the application at `http://127.0.0.1:8000/`

## Project Structure

- `core/`: Main application logic, home, dashboard
- `users/`: User authentication and profiles
- `courses/`: Course modules, lessons, quizzes, projects
- `forum/`: Community discussion forum
- `resources/`: Downloads and external links
- `templates/`: HTML templates with Bootstrap 5
- `static/`: CSS, JS, images

## Security

- CSRF protection enabled
- Secure password hashing
- Input validation
- User authentication required for protected views

## Contributing

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Test thoroughly
5. Submit a pull request
 

