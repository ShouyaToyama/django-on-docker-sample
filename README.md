# Django on docker
This project is sample to deploy Django with docker-compose.
Database is postgres, Web server is nginx.
All docker image is made from alpine linux.

# How to start
```
$ cd your_path/django-on-docker
$ docker-compose up -d --build
```
*In the case of windows, Modify newline character of app/entrypoint.sh from CRLF to LF.*

# Reference
[Dockerizing Django with Postgres, Gunicorn, and Nginx](https://testdriven.io/blog/dockerizing-django-with-postgres-gunicorn-and-nginx/)