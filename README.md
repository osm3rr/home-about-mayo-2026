# 🏠 Home About 2006

[![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)](https://www.python.org/)
[![Django](https://img.shields.io/badge/Django-6.0.4-green.svg)](https://www.djangoproject.com/)
[![License](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

A beautiful and simple Django web application showcasing a personal home page and about section. Built with Django 6.0.4, this project demonstrates clean architecture and responsive design.

## ✨ Features

- **🏠 Home Page**: Welcome visitors with an engaging landing page
- **📖 About Page**: Share your story and background
- **🔧 Admin Panel**: Full Django admin interface for content management
- **📱 Responsive Design**: Mobile-friendly templates using HTML and CSS
- **⚡ Fast Setup**: Quick installation with virtual environment support

## 🚀 Installation

### Prerequisites

- Python 3.8 or higher
- Git (for cloning the repository)

### Step-by-Step Setup

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/home_about2006.git
   cd home_about2006
   ```

2. **Create a virtual environment**
   ```bash
   python -m venv .venv
   ```

3. **Activate the virtual environment**
   - On Windows:
     ```bash
     .venv\Scripts\activate
     ```
   - On macOS/Linux:
     ```bash
     source .venv/bin/activate
     ```

4. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

5. **Apply database migrations**
   ```bash
   python manage.py migrate
   ```

6. **Create a superuser (optional, for admin access)**
   ```bash
   python manage.py createsuperuser
   ```

7. **Run the development server**
   ```bash
   python manage.py runserver
   ```

8. **Open your browser**
   
   Visit `http://127.0.0.1:8000/` to see the home page!

## 📁 Project Structure

```
home_about2006/
├── db.sqlite3                 # SQLite database
├── manage.py                  # Django management script
├── requirements.txt           # Python dependencies
├── base_project/              # Main Django project
│   ├── __init__.py
│   ├── asgi.py
│   ├── settings.py           # Project settings
│   ├── urls.py               # URL routing
│   └── wsgi.py
├── pages/                     # Custom Django app
│   ├── __init__.py
│   ├── admin.py              # Admin configuration
│   ├── apps.py
│   ├── models.py             # Database models
│   ├── tests.py
│   ├── urls.py               # App URL routing
│   ├── views.py              # View functions
│   └── migrations/           # Database migrations
│       └── __init__.py
└── templates/                 # HTML templates
    ├── _base.html            # Base template
    ├── about.html            # About page template
    └── home.html             # Home page template
```

## 🎯 Usage

### Viewing Pages

- **Home**: `http://127.0.0.1:8000/`
- **About**: `http://127.0.0.1:8000/about/`
- **Admin**: `http://127.0.0.1:8000/admin/` (requires superuser login)

### Development Commands

```bash
# Run tests
python manage.py test

# Create new migrations
python manage.py makemigrations

# Collect static files (for production)
python manage.py collectstatic
```

## 🛠️ Technologies Used

- **Backend**: Django 6.0.4
- **Database**: SQLite (default, easily switchable to PostgreSQL/MySQL)
- **Frontend**: HTML5, CSS3
- **Python Packages**:
  - `asgiref==3.11.1` - ASGI utilities
  - `Django==6.0.4` - Web framework
  - `sqlparse==0.5.5` - SQL parsing
  - `tzdata==2026.2` - Timezone data

## 🤝 Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

### Development Guidelines

- Follow PEP 8 style guidelines
- Write tests for new features
- Update documentation as needed
- Ensure all tests pass before submitting

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙋‍♂️ Support

If you have any questions or need help:

- Open an issue on GitHub
- Check the Django documentation: https://docs.djangoproject.com/
- Python documentation: https://docs.python.org/

---

**Made with ❤️ using Django**