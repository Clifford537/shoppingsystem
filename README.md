# Django Project

Follow these steps to set up and run the application.

## Requirements

- Python 3.x
- Django 3.x or higher

## Setup and Installation

### 1. Clone the Repository

First, clone the repository to your local machine:

```sh
git clone https://github.com/Clifford537/shoppingsystem.git
cd shoppingsystem
```

### 2. Create and Activate a Virtual Environment

It is recommended to use a virtual environment to manage dependencies. Create and activate a virtual environment using the following commands:

#### On Windows

```sh
python -m venv env
.\env\Scripts\activate
```

#### On macOS/Linux

```sh
python3 -m venv env
source env/bin/activate
```

### 3. Install Dependencies

Install the required Python packages with pip:

```sh
pip install -r requirements.txt
```

### 4. Apply Migrations

Set up the database by running the migrations:

```sh
python manage.py migrate
```

### 5. Run the Development Server

Start the Django development server:

```sh
python manage.py runserver
```

### 6. Create a Superuser

Create a superuser account to access the Django admin interface and add products:

```sh
python manage.py createsuperuser
```

### 7. Access the Application

Open your web browser and go to [http://127.0.0.1:8000/](http://127.0.0.1:8000/) to view the application.

## File Structure

- `manage.py`: Django's command-line utility for administrative tasks.
- `simpleshopping/`: Contains project settings and configuration.
- `app/`: Contains the main application, including views, models, templates, etc.
- `templates/`: Directory for HTML templates.
