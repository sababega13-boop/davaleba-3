# davaleba-3
MZIURIS DAVALEBA
1. პროექტის საქაღალდეში შესვლა
cd Desktop
2. ვირტუალური გარემოს შექმნა
python -m venv venv
3. ვირტუალური გარემოს გააქტიურება:
\venv\Scripts\Activate
4. Django-ს ინსტალაცია
python -m pip install django
5. Django პროექტის შექმნა
django-admin startproject config .
6. აპლიკაციის შექმნა
python manage.py startapp shop
7. აპლიკაციის დამატება settings.py-ში
 config/settings.py და  INSTALLED_APPS.
დაამატეთ shop:
8. მიგრაციების გაშვება
python manage.py makemigrations

შემდეგ:

python manage.py migrate
9. სერვერის გაშვება
python manage.py runserver
10. ადმინისტრატორის შექმნა
python manage.py createsuperuser
