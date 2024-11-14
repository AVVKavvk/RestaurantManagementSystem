``` python
python -m venv venv
```
``` python
source venv/bin/activate 
```
```
 pip install django django-extensions
 ```
 ```
 django-admin startproject orm . 
 ```

 ```
python manage.py startapp core
 ```

### After every model updation we have to migrate

```
python manage.py makemigrations
```

```
python manage.py migrate
```





# References

https://docs.djangoproject.com/en/4.2/ref/databases/
https://docs.djangoproject.com/en/4.2/ref/models/fields/
https://docs.djangoproject.com/en/4.2/topics/migrations/
https://docs.djangoproject.com/en/4.2/ref/models/fields/#enumeration-types