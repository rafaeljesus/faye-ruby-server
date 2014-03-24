faye-ruby-server
================

This is a simple Ruby Faye Server to make WebSockets and a Ruby base app works on Heroku

Setup
-----

* git clone https://github.com/rafaeljesus/faye-ruby-server.git
* cd faye-ruby-server
* bundle

Deploy
------

Deploy at Heroku:

* heroku create
* git push heroku master
* heroku labs:enable websockets
* heroku restart

Maintaners
----------

* [Rafael Jesus](https://github.com/rafaeljesus)
