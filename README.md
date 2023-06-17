### Yatube API

The project is an API for the Yatube site

### Как запустить проект:

Clone the repository and navigate to it on the command line:

```
git clone https://github.com/Normal1One/api_final_yatube.git
```

```
cd api_final_yatube
```

Create and activate a virtual environment:

```
python -m venv .venv
```

```
source ./.venv/Scripts/activate
```

Install dependencies from the requirements.txt file and navigate to the API folder:

```
pip install -r requirements.txt
```

```
cd yatube_api
```

Perform migrations:

```
python manage.py migrate
```

Run the project:

```
python manage.py runserver
```

### How to use the project:

All documentation is available at http://127.0.0.1:8000/redoc/ (available after the project is launched)
