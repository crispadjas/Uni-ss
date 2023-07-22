# Uni-ss

This is a project is a web server that has a vulnerable and a unvulnerable version.

## Implementation

This project was made using **[python](https://www.python.org/)** as the *back-end* language and the standard 
HTML, CSS and JavaScript to the *front-end*.

The framework we decided to use is **[Flask](https://flask.palletsprojects.com/en/)**.

## Installation

1. Create a virtual environment for python:
```sh
python -m venv .venv
```
> You can choose any name you want for the directory.
2. Activiate the environment. (The activation steps dependo on the system
you are using).
3. Install **Flask**:
```sh
pip install Flask
```
4. Run server:
```sh
flask --app app run --debug
```

The server goes on port **5000** so just go http://localhost:5000.