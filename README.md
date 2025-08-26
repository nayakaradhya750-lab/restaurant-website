# Restaurant Website (Django)
This is a simple restaurant website built using **Django**.  
It includes a homepage and an About page where visitors can learn more about the restaurant.  
## Features
- Homepage with navigation
- About page with restaurant description and image
- Django views and URL routing
- Templates folder with HTML files
## How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/restaurant-website.git
   cd restaurant-website
2. Run the server:

python manage.py runserver


3. Open in browser:

http://127.0.0.1:8000/
http://127.0.0.1:8000/about/



## Project Structure

restaurant-website/
│
├── manage.py
├── db.sqlite3
├── restaurant_website/         # Main project folder (settings, wsgi, etc.)
│   ├── __init__.py
│   ├── settings.py
│   ├── urls.py
│   └── wsgi.py
│
├── myapp/                      # Django app folder
│   ├── __init__.py
│   ├── views.py                 # Added About view
│   ├── urls.py                  # Added /about/ route
│   └── models.py
│
└── templates/                  # HTML templates folder
    ├── home.html                # Homepage template
    └── about.html               # About page template


