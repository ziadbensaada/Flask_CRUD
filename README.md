# Flask CRUD Application

![Flask](https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white)
![SQLAlchemy](https://img.shields.io/badge/SQLAlchemy-100000?style=for-the-badge&logo=sqlalchemy&logoColor=red)
![SCSS](https://img.shields.io/badge/SCSS-CC6699?style=for-the-badge&logo=sass&logoColor=white)

## Overview

This is a simple CRUD (Create, Read, Update, Delete) application built with Flask, SQLAlchemy, and SCSS. The application provides an interface to create new tasks, display them, and allows for editing or removing existing tasks.

## Features

- Create new tasks
- View a list of tasks
- Edit tasks
- Delete tasks

## Getting Started

### Prerequisites

- Python 3.7+
- Virtual environment tool (optional but recommended)

### Installation

1. **Clone the repository**
   ```sh
   git clone https://github.com/ziadbensaada/Flask_CRUD.git
   cd Flask_CRUD

2. **Create and activate a virtual environment (optional but recommended)**
  ```sh
  python -m venv venv
  source venv/bin/activate  # On Windows use `venv\Scripts\activate`
  ```
3. **Install the dependencies**
  ```sh
  pip install -r requirements.txt
  ```
4. **Run the application**
  ```sh
  python run app.py
  ```
### Project Structure
  Flask_CRUD/
  │
  ├── app/
  │   ├── static/
  │   │   ├── css/
  │   │   │   ├── main.scss
  │   │   │   └── main.css
  │   ├── templates/
  │   │   ├── base.html
  │   │   ├── index.html
  │   │   ├── edit.html
  │   │   └── create.html
  │   ├── __init__.py
  │   ├── models.py
  │   ├── routes.py
  │   └── forms.py
  │
  ├── migrations/
  │
  ├── venv/ (optional)
  │
  ├── .gitignore
  ├── requirements.txt
  └── README.md

### Technology Stack
  Backend: Flask
  Database: SQLAlchemy (SQLite)
  Frontend: HTML, SCSS

### Connect with Me

[![GitHub](https://img.shields.io/badge/GitHub-ziadbensaada-181717?style=for-the-badge&logo=github)](https://github.com/ziadbensaada)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Ziad%20Ben%20Saada-0A66C2?style=for-the-badge&logo=linkedin)](https://www.linkedin.com/in/ziad-ben-saada-850219226/)

### License
This project is licensed under the MIT License - see the LICENSE file for details.


