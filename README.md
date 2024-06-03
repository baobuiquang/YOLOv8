py -m venv venv
venv\Scripts\activate
py -m pip install --upgrade pip
pip install -r requirements.txt

---------------------------------------------

python --version (3.11.7)
py -m venv venv
venv\Scripts\activate
py -m pip install --upgrade pip

pip install ultralytics
pip install torch==2.2.1 torchvision==0.17.1

pip freeze > requirements.txt
pip install -r requirements.txt