### Installation
1. python -m pip install -r requirements.txt
2. python manage.py makemigrations
3. python manage.py migrate
4. python manage.py runserver
5. python manage.py createsuperuser 


```
* After creating the superuser go to the admin panel and add the 'plans'
* Then go to ```http://127.0.0.1:8000/company/``` and add some companies
* After creating some companies ```http://127.0.0.1:8000/company/<int:pk>/``` (here int:pk is the company id)
* Then you can go to the ```http://127.0.0.1:8000/customer/``` and provide the customer name and the system will generate a random phone number from the companies that you have provided. 
* For customer details ```http://127.0.0.1:8000/customer/<int:pk>/``` (int:pk is the users phone number)
* For subscription ```http://127.0.0.1:8000/customer/<int:pk>/subs/```
* For subscription cancellation ```http://127.0.0.1:8000/customer/<int:pk>/subs/cancel```

