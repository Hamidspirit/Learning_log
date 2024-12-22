# Learning Log App

The Learning Log app is a simple web application built with the Django framework that allows users to keep track of their learning journey by logging notes based on different topics. It is designed to help individuals track their progress and reflect on what they've learned over time.

## Features

- **User Authentication**: Secure user sign-up, login, and logout functionalities.
- **Create Logs**: Add new learning logs under specific topics.
- **Topic Management**: Organize logs by different topics to keep learning structured.
- **View Logs**: View all the logs related to a particular topic and access detailed notes.
- **Edit and Delete Logs**: Modify or remove previously added logs.


## Installation

To get started with the Learning Log app, follow these steps to set it up locally:

### 1. Clone the repository

```bash
git clone https://github.com/yourusername/learning-log-app.git
```
```bash
cd learning-log-app
```

### 2. Create a virtual environment
```bash
python -m venv venv
```

### 3. Activate the virtual environment
* On Windows:
```bash
venv\Scripts\activate
```
* On macOS/Linux:
```bash
source venv/bin/activate
```

### 4. Install dependencies
```bash
pip install -r requirements.txt
```

### 5. Apply database migrations

```bash 
python manage.py migrate
```

### 6. Creat super user
```bash
python manage.py createsuperuser
```
Follow the prompts to create the superuser.

### 7. Run devolopment server
```bash
python manage.py runserver
```

Open browser and go to 
> http://127.0.0.1:8000/