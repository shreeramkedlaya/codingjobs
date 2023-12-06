# Coding Jobs Platform

This project is a web application built using Django and Python to create a platform for coding job listings and applications.

## Table of Contents

- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Features](#features)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Getting Started

### Prerequisites

Make sure you have the following installed on your local machine:

- [Python 3.x](https://www.python.org/ftp/python/3.12.0/python-3.12.0-amd64.exe)
- [pip (Python package installer)](https://pip.pypa.io/en/stable/cli/pip_download/)
- [Virtualenv (optional but recommended)](https://pypi.org/project/virtualenv/)

### Installation

1. Clone the repository:

```bash
git clone https://github.com/shreeramkedlaya/codingjobs.git
cd codingjobs
```
2. Create a virtual environment (optional but recommended):

```bash
virtualenv venv
source venv/bin/activate   # On Windows, use `venv\Scripts\activate`
```
3. Install dependencies:

```bash

pip install -r requirements.txt
```
4. Apply database migrations:

```bash
python manage.py makemigrations
python manage.py migarte
```
5. Run the development server:

```bash
python manage.py runserver
```

The application should now be accessible at http://localhost:8000/.

### Features
 - Job Listings: Post, view, and search coding job listings.
 - User Authentication: Users can register, log in, and apply for jobs.
 - Admin Panel: Admins can manage job listings and user applications.
 - Email Notifications: Send notifications to users for job applications and updates.
### Usage
 - Visit http://localhost:8000/admin/ and log in with the superuser credentials to access the admin panel.
 - Create job listings and manage applications through the admin panel.
 - Users can register, log in, and apply for jobs on the main application.

### Contributing
Feel free to contribute to the project. Follow these steps:

1. Fork the project.
2. Create a new branch: git checkout -b feature/your-feature.
3. Make your changes and commit them: git commit -m 'Add some feature'.
4. Push to the branch: git push origin feature/your-feature.
5. Submit a pull request.