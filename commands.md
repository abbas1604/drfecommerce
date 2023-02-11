pip freeze > requirements.txt
pip install -r requirements.txt
pip install python-dotenv
pip install djangorestframework
pip install drf-spectacular
pip install pytest
pip install coverage
pip install pytest-cov
pip install pytest-factoryboy

pytest
coverage run -m pytest
coverage html

py manage.py shell
from django.core.management.utils import get_random_secret_key
print(get_random_secret_key())

./manage.py createsuperuser
./manage.py spectacular --file schema.yml
