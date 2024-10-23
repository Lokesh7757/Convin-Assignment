**Overview**
The Expense Sharing Application is designed to help users manage and share their expenses with friends and family. This application allows users to create, track, and settle expenses in a user-friendly interface.

**Features**
- **User Authentication**: Secure login and registration.
- **Expense Management**: Create, update, and delete expenses.
- **Group Sharing**: Share expenses with friends and family.
- **Settlement Tracking**: Keep track of who owes what.
- **Responsive Design**: Works on both desktop and mobile devices.

**Tech Stack**
- **Backend**: Django
- **Frontend**: HTML, CSS, JavaScript
- **Database**: SQLite (or your choice of database)
- **Version Control**: Git

**Installation**

**Prerequisites**
- Python 3.x
- pip

**Clone the Repository**
git clone https://github.com/Lokesh7757/Convin-Assignment
cd expense_sharing

**Set Up Virtual Environment**
python -m venv .venv
On Windows use .venv\Scripts\activate

**Install Dependencies**
pip install -r requirements.txt

**Run Migrations**
python manage.py migrate

**Start the Development Server**
python manage.py runserver
Navigate to http://127.0.0.1:8000/ in your web browser to access the application.
