# ShoeDen 

```
This project  with a frontend built in React & Redux and a backend built in Django API.
```

## Live Demo

**This App uses a Heroku free plan, so I am afraid that it takes time to load the pages.**

Check out [FRONTEND LIVE DEMO](https://shoeden-frontend4.herokuapp.com/) here!!

Check out [API LIVE DEMO](https://shoeden-backend4.herokuapp.com/) here!!

## ScreenShot
<img width="1217" alt="Screenshot 2022-09-07 at 8 49 16 AM" src="https://user-images.githubusercontent.com/107904572/188781781-1f39cfe5-27cf-42da-af23-18068b3b1ebf.png">


## Tech used

```
* Frontend : React & Redux
* Backend : Django
```

## How to Install

1. Git Clone

```
git clone https://github.com/jacquelinejoe/Shoe-Den-Project.git
```

2. Backend setting

```
cd backend
Python -m venv env
(For Mac) source env/bin/activate
(For Windows) env/Scripts\activate
pip install -r requirements.txt
python manage.py makemigrations
python manage.py migrate
python manage.py runserver
# Open http://127.0.0.1:8000/posts/

# To have dummy data for testing run:
python manage.py fixtures/dummy-data.json
```

3. Frontend setting

```
cd frontend
npm install
npm start
# Open http://127.0.0.1:3000/
```
