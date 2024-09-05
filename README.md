
# DegreeBoosters Project

This project is a web-based application built using the Flask framework in Python. Below are the instructions on how to set up and use the project.

## Prerequisites

Before running this project, ensure you have the following installed:

- **Python** (preferably 3.6+)
- **pip** (Python package manager)
- **Flask** (web framework)
- **A virtual environment** tool like `venv` or `virtualenv` (optional but recommended)

## Setup Instructions

### 1. Clone or Download the Project
Make sure the project folder is downloaded or cloned into your working directory.

### 2. Create a Virtual Environment (Optional)

It's a good practice to create a virtual environment to manage your project dependencies. Run the following commands:

```bash
# On macOS and Linux
python3 -m venv venv

# On Windows
python -m venv venv
```

Activate the virtual environment:

```bash
# On macOS and Linux
source venv/bin/activate

# On Windows
venv\Scripts\activate
```

### 3. Install Required Python Packages

Install the Flask framework and any other necessary packages by running the following command:

```bash
pip install Flask
```

### 4. Run the Flask Application

In the terminal, navigate to the project folder where `main.py` is located, and run the Flask application:

```bash
# On macOS and Linux
export FLASK_APP=main.py

# On Windows
set FLASK_APP=main.py

# Run the Flask app
flask run
```

This will start a local server, and you should see output similar to:

```
* Running on http://127.0.0.1:5000/ (Press CTRL+C to quit)
```

### 5. Access the Application

Once the application is running, open your browser and go to:

```
http://127.0.0.1:5000
```

### 6. Directory Structure

Here’s a simplified view of the folder structure of the project:

```
degreeboosters-master/
│
├── main.py                # Main entry point of the application
├── templates/             # HTML files for the frontend
│   ├── add.html
│   ├── admin.html
│   ├── adminremove.html
│   ├── base.html
│   ├── course.html
│   ├── faculty.html
│   ├── login.html
│   ├── registration.html
│   └── success.html
└── static/                # Static files like CSS, JavaScript
```


