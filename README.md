# Django Student Study Portal

The Student Study Portal is a web application built with Django, designed to assist students in managing their study tasks, assignments, and educational resources. The application provides a platform for organizing homework, searching for book information, and accessing various learning materials.

## Features

- **Homework Management**: Add, edit, and delete homework tasks.
- **Book Information Retrieval**: Search and display book data using the Google Books API.
- **User Authentication**: Custom login, signup, and logout functionality to secure user data.

## Technologies

- **Backend**: Django, Python
- **Frontend**: HTML, CSS, JavaScript, Bootstrap 
- **Database**: SQLite (configurable for other databases)

## Setup

To get started with the project, follow these steps:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/GjurgjicaM/Django_Project_StudentStudyPortal.git
   cd Django_Project_StudentStudyPortal
Install dependencies:
bash
Copy code
pip install -r requirements.txt
Run migrations and start the server:
bash
Copy code
python manage.py migrate
python manage.py runserver
