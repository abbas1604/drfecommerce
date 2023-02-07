pip freeze > requirements.txt
pip install -r requirements.txt
pip install python-dotenv
pip install djangorestframework

pytest

py manage.py shell
from django.core.management.utils import get_random_secret_key
print(get_random_secret_key())
