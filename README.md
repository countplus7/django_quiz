## Getting started with development

Dependencies:

- Python 3.6.x
- Django 1.11.x
- Ubuntu 17.04 or later or Linux Mint 18.2 or later

### 1. Clone this repository

```bash
git clone https://github.com/akashgiricse/lets-quiz.git
cd lets_quiz
```

### 2. Install [Pipenv](https://pipenv.pypa.io/en/latest/)

### 3. Create the virtualenv

```bash
## run following command from `lets_quiz` directory
pipenv shell
```

### 4. Install python packages

```bash
pip install -r requirements.txt
```

### 5. Setup the database

_TODO - Add instructions for this when I start using MySQL database._

### 6. Run database migrations

```bash
cd lets_quiz
python manage.py migrate
```

### 7. Create superuser

```bash
python manage.py createsuperuser
```

### 8. Run development server

```bash
python manage.py runserver
```

## License

MIT License

Copyright (c) 2022 Akash Giri.
