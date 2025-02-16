# Music App

## Overview
This is a music streaming web application built using Django. The application allows users to register, log in, and stream music seamlessly.

## Features
- User authentication (signup, login, logout)

- Music upload and streaming

- Playlist creation and management

- Social authentication via Google

- Responsive UI

## Technologies Used

- Backend: Django, Django REST Framework

- Frontend: HTML, CSS, JavaScript

- Authentication: Django Allauth, Google OAuth

## Installation

### Prerequisites

Ensure you have the following installed:

- Python 3.x

- Virtualenv

## Setup Instructions

1. Clone the Repository
   ``` bash
   git clone https://github.com/Abhaysinh031/Music_App.git
   cd Music_App
   ```

2. Create a Virtual Environment
   ``` bash
   python -m venv venv
   ```

3. Activate the Virtual Environment
- Windows:
   ``` bash
   venv\Scripts\activate
   ```

- Mac/Linux:
  ``` bash
   source venv/bin/activate
  ```
4. Install Dependencies
   ``` bash
   pip install -r requirements.txt
   ```

5.Set Up Environment Variables
Create a .env file in the project root and add:
   ```bash
   GOOGLE_CLIENT_ID=your_google_client_id
   GOOGLE_CLIENT_SECRET=your_google_client_secret
   ```

6. Apply Migrations
   ``` bash
   python manage.py migrate
   ```

7. Create a Superuser
   ``` bash
   python manage.py createsuperuser
   ```
Follow the prompts to create an admin user.

8. Run the Development Server
   ``` bash
   python manage.py runserver
   ```
   
Access the application at http://127.0.0.1:8000/.












