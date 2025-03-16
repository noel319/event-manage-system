# Event Management System.
This System is a project designed for managing events using the Django framework. Users can easily clone the project, set it up on a Linux environment, and start using it to manage various events efficiently.
## How To Setup On Linux
1. Clone This Project `git clone git@github.com:noel319/event-manage-system.git`
2. Go to Project Directory `cd django-event-management`
3. Create a Virtual Environment `python3 -m venv env`
4. Activate Virtual Environment `source env/bin/activate`
5. Install Requirements Package `pip install -r requirements.txt`
6. Migrate Database `python manage.py migrate`
7. Create Super User `python manage.py createsuperuser`
8. Finally Run The Project `python manage.py runserver`

# Features
Event Creation: Users can create new events with details like date, time, location, and description.
Participant Management: Manage participants attending the events and keep track of their RSVP status.
User Authentication: Utilizes Django's built-in authentication system for secure user login and management.
Dashboard Overview: Provides a dashboard to get an overview of all upcoming events and participant details.

