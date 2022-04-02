# Hyperion

## Creating the environment

### Windows

`py -3.10 -m venv .venv`
`.\.venv\Scripts\activate`

In the root folder

```bash
uvicorn app.main:app --reload
```

In the app folder

```bash
uvicorn main:app --reload
```

Code, commits, and comments in English
Use a spell checker

### Pip

```bash
...
pip install black
pip install flake8
pip install fastapi
pip install "uvicorn[standard]"
pip install pytest
pip freeze > requirements.txt
pip install -r requirements.txt

```

Supprimer tous les packages

```bash
pip freeze | xargs pip uninstall -y
```
