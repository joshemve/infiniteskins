# InfiniteSkins

InfiniteSkins is a premium Minecraft skin pack store where users can 
browse, purchase, and subscribe for unlimited access to exclusive skin packs. 
This project includes a Python Flask backend, a responsive frontend, 
and Stripe integration for secure payments and subscriptions.

## Features

- Dynamic skin pack browsing and search functionality.
- Secure user authentication.
- Subscription and one-time purchase options with Stripe.
- Fully responsive design for desktop and mobile users.
- HTTPS enabled with Let's Encrypt.

## Technologies

- **Backend**: Python Flask
- **Frontend**: HTML, CSS, JavaScript
- **Web Server**: Nginx
- **Database**: SQLite (expandable to PostgreSQL)
- **SSL**: Let’s Encrypt

## Installation and Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/infiniteskins.git

## Directory

infiniteskins/
│
├── app/
│   ├── templates/        # HTML files
│   ├── static/           # CSS, JS, images
│   │   ├── css/          # CSS files
│   │   ├── js/           # JavaScript files
│   │   └── images/       # Skin pack images
│   ├── __init__.py       # Flask app setup
│   ├── routes.py         # Flask routes
│   └── models.py         # Database models
│
├── main.py               # Entry point for the app
├── requirements.txt      # Python dependencies
└── README.md             # Project overview

## Server Bash to update all code:

- cd /var/www/infiniteskins
- git pull origin main
