Multi-Screen YouTube Player
=========================

* [sinatra-multi-screen](https://github.com/shokai/sinatra-multi-screen)
* Ruby 1.8.7+ or 1.9.2+
* Sinatra1.3+


Install Dependencies
--------------------

    % gem install bundler foreman
    % bundle install


Run
---

    % foreman start

=> http://localhost:5000


Deploy Heroku
-------------

    % heroku create --stack cedar
    % git push heroku master
    % heroku open
