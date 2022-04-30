# Python-blueprint is a template application for flash python
Initialize the database.

$ export FLASK_APP=app
$ export FLASK_ENV=development
$ flask init-db
Run the app.

$ flask run
Tests
To run the tests just run pytest in the project directory.

$ pytest
You can also run the tests and get a coverage report.

$ pytest --cov=app tests/
