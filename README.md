lab-notebook
============

IPython notebook deployed to a Vagrant box via dokku

Installation
------------

First, make sure you can deploy to your Vagrant box with dokku (https://github.com/RyanBalfanz/dokku-vagrant-example). Then deploy this application

	git remote add dokku dokku@dokku.me:lab-notebook
	git push dokku master

For extra goodies e.g. numpy, scipy. pandas:

	pip install -r requirements-goodies.txt
