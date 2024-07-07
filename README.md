Clone source code from git repository

	git clone https://github.com/surajurm/task-application

	git checkout origin/master

Install application using requirement files
 
	pip install -r requirements.txt
	
Creating database schema and migrate table
 	
	python manage.py makemigrations
	python manage.py migrate

Run Application
  
	python manage.py runserver
 
Access Application on browser using below URL

	http://localhost:8000/
