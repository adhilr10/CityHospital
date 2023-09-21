# City Hospital Django Application
This is a project I developed during my Django learning journey.
**Live Demo**: [City Hospital Web Application](http://adhilrahman8589.pythonanywhere.com/)

City Hospital is a web application developed using the Django framework in Python. It serves as a platform for managing doctor details, booking appointments, exploring different departments, learning about the hospital, and contacting the staff. This README file provides an overview of the application and instructions for setting it up.

## Table of Contents
1. [Features](#features)
2. [Prerequisites](#prerequisites)
3. [Installation](#installation)
4. [Usage](#usage)
5. [Project Structure](#project-structure)
6. [Contributing](#contributing)

## Features <a name="features"></a>
City Hospital offers the following features:

1. **Doctor Details**: Users can view detailed information about doctors, including their name, specialty, qualifications, and contact information.

2. **Booking Appointments**: Patients can book appointments with their preferred doctors by selecting a date and time slot.

3. **Departments**: The application categorizes doctors into different departments, making it easy for users to find specialists in specific medical areas.

4. **About Us**: Provides information about the hospital, its mission, and history.

5. **Contact Us**: Users can get in touch with the hospital administration or support staff using the contact form.

## Prerequisites <a name="prerequisites"></a>
Before you begin, ensure you have the following installed on your system:

- Python 3.x: https://www.python.org/downloads/
- Django 3.x: https://docs.djangoproject.com/en/stable/intro/install/
- Pip (Python package manager): https://pip.pypa.io/en/stable/installation/

## Installation <a name="installation"></a>
Follow these steps to set up and run the City Hospital application on your local machine:

1. Clone this repository to your local machine using Git:
   ```bash
   git clone https://github.com/yourusername/city-hospital.git
   ```

2. Navigate to the project directory:
   ```bash
   cd city-hospital
   ```

3. Install the required Python packages using pip:
   ```bash
   pip install -r requirements.txt
   ```

4. Create the database and apply migrations:
   ```bash
   python manage.py makemigrations
   python manage.py migrate
   ```

5. Create a superuser account to access the Django admin panel:
   ```bash
   python manage.py createsuperuser
   ```

6. Start the development server:
   ```bash
   python manage.py runserver
   ```

7. Open your web browser and go to http://localhost:8000/admin/ to log in with the superuser account. Here, you can add doctors, departments, and manage other content.

8. To access the main application, visit http://localhost:8000/.

## Usage <a name="usage"></a>
- Use the navigation menu on the City Hospital website to explore and interact with the features.
- As an admin, you can add, update, and delete doctors and departments via the Django admin panel.

## Project Structure <a name="project-structure"></a>
The project structure is organized as follows:

- `city_hospital/`: Main Django project directory.
- `hospital/`: Django app containing the website's core functionality.
- `static/`: Static files (CSS, JavaScript, images).
- `templates/`: HTML templates used for rendering web pages.
- `requirements.txt`: List of Python packages required for the project.
- `manage.py`: Django's command-line tool for various tasks.
- `README.md`: This README file.

