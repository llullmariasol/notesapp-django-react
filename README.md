# Django & React Notes App

### Overview
Notes App created using:
- [Django](https://www.djangoproject.com/) and [Django Rest Framework](https://www.django-rest-framework.org/) (backend - "api" folder)
- [React](https://react.dev/) (frontend - "frontend" folder)

### Features
<img width="400" height="540" alt="List of notes" src="https://github.com/solllull/notesapp-django-react/assets/50931383/66e13b96-8843-45da-b5fb-a6be9aebda8d">

<img width="400" height="540" alt="Create a note" src="https://github.com/solllull/notesapp-django-react/assets/50931383/87f0cdcb-da02-432e-853b-c19a564c3ff1">


### Installation and use

- Clone the repository:
```
git clone https://github.com/solllull/notesapp-django-react.git
```

- Move into the directory where the project files are:
- Install requirements.txt:
```
cd notesapp-django-react
```

- Create a virtual environment:
```
# If you are on Windows
virtualenv env
# If you are on Linux or Mac
python -m venv env
```

- Activate the virtual environment:
```
# If you are on Windows
.\env\Scripts\activate
# If you are on Linux or Mac
source env/bin/activate
```

- Install requirements.txt:
```
pip3 install -r requirements.txt
```

- Create and apply migrations:
```
python3 manage.py makemigrations
python3 manage.py migrate
```

- Run the app at http://127.0.0.1:8000/:
```
python3 manage.py runserver
```


