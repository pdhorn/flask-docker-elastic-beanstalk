I followed https://runnable.com/docker/python/docker-compose-with-flask-apps to get a Flask app with Redis in a Dockerized package.

To run, use `docker-compose up` (or `docker-compose up -d` to reset the counter). Use `docker-compose down` to quit, or `CTRL-C`.

Deploy to AWS Elastic Beanstalk
I ran `eb init` then `eb create`.
