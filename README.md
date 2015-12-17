#  <div align="center">TodoMVC Django</div>

TodoMVC Django is a to-do list web application. A REST API was built using the Django REST Framework for use with the [AngularJS TodoMVC app](http://todomvc.com/examples/angularjs/).

## <div align="center">Instructions</div>

* Before the user can run the TodoMVC Django application, the user must first clone the `todomvc-django` repo onto their computer. The user will need to create a virtual environment running Python 3 in the `todomvc-django` repo folder.
* To properly run the application, the contents of requirements.txt must be installed.
  * After navigating to the folder containing `requirements.txt`, enter `pip install -r requirements.txt` on the command-line to download the contents of requirements.txt.
* TodoMVC Django uses an SQLite database. To properly configure the database, the user must navigate to the `todomvc` folder that contains `manage.py` and enter `python manage.py migrate` on the command-line.
* The user must run a local server in order to use the application. After navigating to the `todomvc` folder which contains `manage.py`, enter `python manage.py runserver` on the command-line to start the local sever. The application can now be accessed via the user's web browser at `http://localhost:8000/`.
