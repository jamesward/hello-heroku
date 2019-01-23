Hello Flask
-----------

[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy)

Setup Local Python Environment:

(If the Python install fails, see: https://github.com/pyenv/pyenv/wiki/Common-build-problems)

```
export PYENV_ROOT=pyenv
pyenv/bin/pyenv install
eval "$(pyenv/bin/pyenv init -)"
python -m venv venv
source venv/bin/activate
pip install -U pip
pip install -r requirements.txt
```

Run the server locally:
```
FLASK_APP=web.py flask run
```

Check it out: http://127.0.0.1:5000/
