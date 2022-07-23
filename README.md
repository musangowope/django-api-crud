# django-api-crud

A basic Python Django REST CRUD API example

## Running the project
- In the terminal run `cp .env.example .env` then set `SECRET_KEY` in `.env` to secure value. Value can be generated [here](https://djecrety.ir/)


- Set up and activate virtual environment. Python 3.6 or later is required
```
python 3 -m venv venv
source venv/bin/activate
```

- Install requirements
```
pip install -r requirements.txt
```

- Run application
```
python3 manage.py runserver
```
- After application runs, you can test out endpoints

**REST Endpoints**

Visit the following links to test out the CRUD endpoints
```
Item List
Allow: GET, POST, HEAD, OPTIONS
http://localhost:8000/api/items/

Item Detail
Allow: GET, PUT, PATCH, DELETE, HEAD, OPTIONS
http://localhost:8000/api/items/<id>

Location List
Allow: GET, POST, HEAD, OPTIONS
http://localhost:8000/api/locations

Location Detail
Allow: GET, PUT, PATCH, DELETE, HEAD, OPTIONS
http://localhost:8000/api/locations/<id>
```



