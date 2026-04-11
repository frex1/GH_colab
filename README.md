# GH_colab

A collaborative Django project demonstrating the basics of Django web app development and organization.

## Project Structure

```text
GH_colab/
├── app/
│   ├── hello_django/      # Main Django project folder
│   ├── helloapp/          # Example app
│   ├── users/             # Custom user management
│   ├── manage.py          # Django management script
│   ├── db.sqlite3         # SQLite database (default, dev use)
│   └── requirements.txt   # Python dependencies
├── .gitignore
├── README.md
```

## Features

- Django 3.x project
- Example apps: `helloapp`, `users`
- SQLite database for easy local testing
- Ready-to-use `requirements.txt`
- Basic project structure for extensions or teamwork

## Getting Started

### Prerequisites

- Python 3.7+
- pip

### Setup Instructions

Clone the project and set up the environment:
```bash
git clone https://github.com/frex1/GH_colab.git
cd GH_colab/app
pip install -r requirements.txt
```

Run migrations and start the server:
```bash
python manage.py migrate
python manage.py runserver
```

Visit [http://127.0.0.1:8000](http://127.0.0.1:8000) to view the project.

## Development

- To create apps use `python manage.py startapp <app_name>`
- Add your apps to `INSTALLED_APPS` inside `hello_django/settings.py`
- For ready deployments, switch from SQLite to PostgreSQL or MySQL as needed

## License

MIT

## Author

[@frex1](https://github.com/frex1)

---

## Issues

Report issues or suggestions at: https://github.com/frex1/GH_colab/issues