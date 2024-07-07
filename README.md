
Installation Steps:


	pull source code from git 

	git clone https://github.com/surajurm/task-application

	git checkout master
	
	pip install -r /path/to/requirements.txt

 	cd taskmanager
	
  Creating database schema and migrate table
 	
	python manage.py makemigrations
	python manage.py migrate

  Run Application
	python manage.py runserver
