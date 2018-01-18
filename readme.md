### Step to install

* `git clone git@github.com:thienkimlove/python-polls.git`

* `virtualenv ~/.virtualenvs/python-polls`

* `source ~/.virtualenvs/python-polls/bin/activate`

* `pip3 install -r requirements.txt`

* `cd django-polls && python setup.py sdist`

* `pip install django-polls/dist/django-polls-0.1.tar.gz`
* `python3 manage.py migrate`

* `python3 manage.py runserver 0.0.0.0:9160`

* `pip3 freeze > requirements.txt`