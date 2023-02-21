.. contents::

==========
Background
==========

This is the buildout for plone5_buildout

==========
Dependency
==========

1. sudo apt-get install python3.8-dev python-dev build-essential
2. sudo apt-get -y install gcc make build-essential libssl-dev libffi-dev python-dev
3. make sure you have python > 3.8

Use this buildout
=================

install
-------

1. `$ git clone {project url}`
2. `$ cd {project_name}`
3. copy buildout.cfg.example to buildout.cfg
4. `$ virtualenv -p python3.8 .`
5. `$ ./bin/pip install -r requirements.txt`
6. `$ ./bin/buildout -v`


mysql setup
-----------
1. locally you can run ./docker-mysql-5.7.sh
2. login to that mysql: `$ mysql -h 127.0.0.1 -P 33064 -u root -p1 -A;`
3. create the database that you want for local: `$ create database plone5_test`
