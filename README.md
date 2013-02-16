Multi-Screen YouTube Player
===========================

* http://multiscreen-youtube.herokuapp.com
* https://github.com/shokai/sinatra-multi-screen


Install Dependencies
--------------------
Ruby 1.8.7+ or 1.9.2+ required.

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
