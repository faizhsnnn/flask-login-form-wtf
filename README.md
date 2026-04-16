## Flask Login Form with Flask-WTF Validation

This project demonstrates how to build a login form in Flask using Flask-WTF and WTForms for input validation.

The application displays a login page where users must enter a valid email address and password. The form validates user input using WTForms validators before checking the credentials.

Bootstrap integration is used to render the form with a clean and responsive interface.

This project was built as part of the #90DaysOfCode challenge to practice backend form handling, validation, and template inheritance using Flask.

---

## Technologies Used

Python  
Flask  
Flask-WTF  
WTForms  
Bootstrap 5  
HTML5  
Jinja2 Templating  

---

## Key Concepts Demonstrated

Creating web forms using Flask-WTF

Input validation using WTForms validators

Handling GET and POST requests in Flask routes

CSRF protection for secure form submission

Rendering forms with Bootstrap styling

Conditional rendering based on authentication results

Template inheritance using Jinja

---

## Project Structure

```
project/
│
├── main.py
│
├── templates/
│   ├── base.html
│   ├── index.html
│   ├── login.html
│   ├── success.html
│   └── denied.html
```

---

## Installation

Install dependencies

```
pip install flask
pip install flask-wtf
pip install flask-bootstrap
```

---

## Run

```
python main.py
```

Open your browser and navigate to

```
http://127.0.0.1:5000
```

---

## Author

Faiz Hasan  
Python Automation & Backend Developer
