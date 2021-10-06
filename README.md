## Installing and runing project at your local host
1. Download project to you local computer 
   + Download project 
     + __git clone https://github.com/alasgar88/blog.git__
   + Go to directory __blog__
     + __cd blog__
      
2. Create virtual environment (e.g with the module of venv) 
   + create virtual environtment
     + __virtualenv myenv__
   + activate virtual environment
     + __Windows (myenv\Scripts\activate), unix (source myenv/bin/activate)__
   + install dependencies
     + __pip install -r requirements.txt__ 

3. Create sqlite database
   + Run command below to create sqlite database
     + __python manage.py migrate__
   + Fill sqlite database with data from datadump.json
     + __python manage.py loaddata datadump.json__

---
+ ___Login to admin panel as superuser___
  + __http://localhost:8000/admin/__
  + __login: superuser__
  + __password: superuser__


