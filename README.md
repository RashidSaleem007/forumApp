# To run the project run below commands inside project directory

1. cd forumApp
2. virtualenv venv
3. source venv/bin/active

4. pip install -r requirements.txt
5. python3 manage.py migrate
6. python3 manage.py runserver
7. open broswer http://127.0.0.1:8000/ and create user.

# you will see there no empty board,so create to create board you need to create superadmin, please run the command
8. python manage.py createsuperuser
9. Navigate http://127.0.0.1:8000/admin and login with admin that you have created recently and then create board.
9. Navigate http://127.0.0.1:8000/ and you will see the some boards on UI.

Thanks.
