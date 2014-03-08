# Python Application

New Python demo application. 

## Requirements

First you'll need to have [python package](http://www.python.org/download/).

Then install `pip` : 
	
	// download get-pip.py
	https://raw.github.com/pypa/pip/master/contrib/get-pip.py
	// Then install pip
	python get-pip.py

and `virtualenv` :

	sudo pip install virtualenv


## Create virtualenv

Create a virtual environnement :

	virtualenv venv --distribute
	source venv/bin/activate

Install Flask :

	pip install Flask


## Starting

Launch your app :

	foreman start