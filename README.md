# Todolist User Authentication Django

A Django application for managing a to-do list with user authentication features such as sign-up, login, and logout.

## Features

- User Registration (Sign up)
- User Login & Logout
- Create, View, and Manage To-Do Items
- User-specific To-Do Lists
- Simple and intuitive UI for managing tasks

## Prerequisites

Before you begin, ensure you have the following installed on your local machine:

- Python 3.x
- Django
- A virtual environment tool (e.g., `venv` or `virtualenv`)

## Installation

# Step 1: Clone the Repository
```
git clone https://github.com/Mohammed-Haarish/Todolist_User_Authentication_django.git
cd Todolist_User_Authentication_django

```
# step2: For Windows:
```python -m venv env
env\Scripts\activate

# For macOS/Linux:
```
python3 -m venv env
source env/bin/activate

# Step 3: Install Dependencies
```
pip install -r requirements.txt

```
# Step 4: Set Up the Database
```
python manage.py migrate

```
# Step 5: Create a Superuser (Optional)
```
python manage.py createsuperuser

```
# Step 6: Run the Development Server
```
python manage.py runserver

```
# Visit the following URL in your browser:
```
# http://127.0.0.1:8000/

```
## screenshots

![image](https://github.com/user-attachments/assets/862dafcb-7422-4d38-b2c4-9efe55cb66da)

![image](https://github.com/user-attachments/assets/1750e3a3-715d-4140-b964-65cf458b647b)

![image](https://github.com/user-attachments/assets/3e22cf64-fdaf-4226-abc8-85f997c15540)

## Contributing
We welcome contributions! If you'd like to contribute to this project:

- Fork the repository.
- Create a new branch (git checkout -b feature-branch).
- Make your changes.
- Commit your changes (git commit -am 'Add feature').
- Push to the branch (git push origin feature-branch).
- Open a pull request.

## License
This project is open-source and available under the MIT License.






