python --version (3.11.7)

py -m venv venv

venv\Scripts\activate

py -m pip install --upgrade pip

pip freeze > requirements.txt
pip install -r requirements.txt