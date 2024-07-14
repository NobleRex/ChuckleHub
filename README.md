# ChuckleHub

ChuckleHub is a web application that delivers a daily dose of laughter through a curated collection of jokes. It offers features like joke rating, different joke levels, and a refreshable joke list.

## Features

- Fetch and display random jokes
- Rate jokes and store ratings
- Choose joke levels (Clean, Mild, Dark)
- Responsive design with dark mode support
- Animated transitions for a better user experience

## Requirements

- Python 3.8+
- Django 3.2+
- Requests library
- GSAP (GreenSock Animation Platform) - included via CDN
- Font Awesome - included via CDN

## Installation

1. Clone the repository:

git clone https://github.com/NobleRex/chucklehub.git
cd chucklehub

2. Create a virtual environment:

python -m venv venv

3. Activate the virtual environment:

- On Windows:
  ```
  venv\Scripts\activate
  ```
- On macOS and Linux:
  ```
  source venv/bin/activate
  ```

4. Install the required packages:

pip install -r requirements.txt

5. Apply migrations:

python manage.py migrate

6. Create a superuser (optional):

python manage.py createsuperuser

## Running the Project

1. Start the development server:

python manage.py runserver

2. Open a web browser and navigate to `http://127.0.0.1:8000/`

## Project Structure

- `Gags/` - Main application directory
- `views.py` - Contains view functions
- `urls.py` - URL configurations for the app
- `templates/Gags/` - HTML templates
- `static/` - CSS and JavaScript files
- `ChuckleHub/` - Project configuration directory
- `manage.py` - Django's command-line utility for administrative tasks

## API Used

- [icanhazdadjoke](https://icanhazdadjoke.com/api)
- [JokeAPI](https://v2.jokeapi.dev/)

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.
