# Devamigos
chatting rooms 
Certainly! Here’s the full content ready for your GitHub README file:
<img width="1510" alt="Screenshot 2024-08-16 at 4 20 23 AM" src="https://github.com/user-attachments/assets/b918ad2b-1ded-484d-8223-1df55e6ae43d">

<img width="1510" alt="Screenshot 2024-08-16 at 4 20 31 AM" src="https://github.com/user-attachments/assets/0c5753f0-ebd7-449b-9166-c7f6dd9c1e33">
<img width="1510" alt="Screenshot 2024-08-16 at 4 20 38 AM" src="https://github.com/user-attachments/assets/715b4c3c-b0a3-48a3-ac17-c1b5dc9be97e">




```markdown
# Django Web Chat App

A simple and efficient web chat application built using Django, allowing users to create and join chat rooms with both public and private access.

## Table of Contents

- [Project Overview](#project-overview)
- [Project Details](#project-details)
- [Technologies Used](#technologies-used)
- [Installation Instructions](#installation-instructions)
- [Usage Guide](#usage-guide)
- [Project Structure](#project-structure)
- [Dependencies](#dependencies)
- [Troubleshooting](#troubleshooting)
- [Support and Contact](#support-and-contact)
- [Acknowledgments](#acknowledgments)

## Project Overview

The Django Web Chat App enables users to create and participate in chat rooms. The app supports public rooms that anyone can join and private rooms that require a password. Users must register with their email and username to use the app. Additionally, the app allows room owners to send email invitations to other users.

## Project Details

- **Project Name:** Django Web Chat App
- **Version:** 1.0
- **Authors:**P.GIRISHKUMAR 
- **Date:** 08-07-2023

## Technologies Used

- **Django Framework** (Version: 4.1.7)
  - A high-level Python web framework that simplifies the development of web applications.
  - **Usage:** Used as the core framework for building the web chat app.

- **Django Email Library** (Version: 4.1.7)
  - A module provided by Django for sending emails within applications.
  - **Usage:** Utilized to send invitations from owners to other users via email.

## Installation Instructions

To set up and run the Django Web Chat App, follow these steps:

1. **Clone the repository:**
   ```bash
   git clone https://github.com/DEVAMIGOS/DEVAMIGOS.git
   cd DEVAMIGOS
   ```
2. **Install Python 3.9 or above** (if not already installed).
3. **Create a virtual environment** using `virtualenv` or `venv`:
   ```bash
   python3 -m venv venv
   ```
4. **Activate the virtual environment:**
   - On Windows:
     ```bash
     venv\Scripts\activate
     ```
   - On macOS/Linux:
     ```bash
     source venv/bin/activate
     ```
5. **Install the required dependencies:**
   ```bash
   pip install -r requirements.txt
   ```
6. **Configure the database settings** in `settings.py`.
7. **Run database migrations:**
   ```bash
   python manage.py migrate
   ```
8. **Start the development server:**
   ```bash
   python manage.py runserver
   ```
9. **Access the app** in your web browser at `http://localhost:8000`.

## Usage Guide

### User Registration and Login

1. **Homepage:** Visit the homepage of the web chat app.
2. **Signup:** Click on the "Signup" button and provide your email and username to create an account.
3. **Login:** If you already have an account, click on the "Login" button and enter your credentials.

### Room Creation and Joining

1. **Dashboard:** After logging in, you will be redirected to the dashboard.
2. **Create a Room:** Click on the "Create Room" button under "My Rooms." Choose the room type (private or public). If it's private, set a password. Submit the form to create the room.
3. **Join a Room:** Click on the "Join Room" button and enter the room ID. If it's a private room, enter the password to join.

### Sending Invitations

1. **Private Room Owners:** Navigate to the room details page.
2. **Invite Users:** Enter the email addresses of the users you want to invite and click on the "Send Invitations" button. The selected users will receive an email invitation.

## Project Structure

```
Django Web Chat App/
├── djangochat/
│   ├── settings.py
│   ├── urls.py
│   ├── views.py
│   ├── models.py
│   ├── routing.py
│   ├── templates/
│   └── static/
├── manage.py
├── requirements.txt
└── README.md
```

- **djangochat/**: Contains the main application code.
- **manage.py**: Command-line utility to interact with the Django project.
- **templates/**: HTML templates for rendering web pages.
- **static/**: Static files like CSS and JavaScript.

## Dependencies

- **Django:** 4.1.7
- **Django Email Library (SMTP):** 4.1.7

## Troubleshooting

**Common Issues and Solutions:**

- **Database Connection Error:**
  - **Solution:** Check the database settings in `settings.py` and ensure the database server is running.

- **Email Invitations Not Sent:**
  - **Solution:** Verify the email configurations in `settings.py`, including SMTP server settings and authentication details.

## Support and Contact

For any support or inquiries, please contact us via email:  
**Email:** GIRISH5F9@gmail.com

## Acknowledgments

We would like to acknowledge the Django community for their excellent framework and the developers of the Django email library for their contributions.
```

This README file includes all the detailed sections you requested, ready to be placed on GitHub.
