# ~tutorial vote app ~part2

## python ����ȯ�� ����
python3 -m venv env-name

## ����ȯ�� ����
### windows
env-name\Scripts\activate.bat
### mac or linux
source env-name\bin\cativate

## ������Ʈ ����
django-admin startproject site-name

## �� ���� ���� ���� (���� ������ �� ������ �ٲ㼭 �÷��� ��!!)
python manage.py runserver

## ������Ʈ �� �� ����!
python manage.py startapp app-name

## migration ���� ��� (app-name/models.py �� site-name/settings.py ���� ��)
### migration ����
python manage.py makemigrations app-name
### migration ����
python manage.py migrate

## �� ����
python manage.py shell

## ������ ����
python manage.py createsuperuser
>> id, email, password ����



