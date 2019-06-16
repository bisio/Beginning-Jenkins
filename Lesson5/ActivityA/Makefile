install:
	virtualenv testing
	./testing/bin/pip install -r requirements.txt

jenkins_test:
	./testing/bin/nosetests app/ -v
