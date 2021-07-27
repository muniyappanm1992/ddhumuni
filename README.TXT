python -m virtualenv env
env\Scripts\activate
pip freeze > requirements.txt
pip install -r requirements.txt
python -m pip install --upgrade pip
