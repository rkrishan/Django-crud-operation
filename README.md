# Django-crud-operation
This Application is perform crud operation on employee deatils
Requirement for running this application is mentioned below

first of create virtual evironment: 
    pip install virtualenv
    virtualenv my_project(Name of virtual environment)
    Activate the virtaul environment- source my_project/bin/activate
    
then after install below packges:

      Python-2.7.12
      dj-database-url==0.4.2
      Django==1.11.10
      djangorestframework==3.7.7


clone the git repostory go insite tutorial get a file name manage.py
    PYTHON MANAGE.PY RUNSERVER 
       if you get error then first run command PYTHON MANAGE.PY MIGRATE, then run Python manage.py makemigration 
       then run the above commnad application is running.
       
       
    
    when you hit the url 127.0.0.1:8000/snippets  it give all deatils of all employe and when you type     127.0.0.1:8000/snippets/1/ : this give the detail of employee whose Id is one you can delete the details of that employee also
    
Also in this app have user authentication functionlaity to secure your application I just have comment that part
   
