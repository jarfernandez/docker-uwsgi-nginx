# docker-uwsgi-nginx
Aplicación web desarrollada en [Python](https://www.python.org/) con el framework [Flask](https://flask.palletsprojects.com/) que se ejecuta en dos contenedores [Docker](https://www.docker.com/) con el servidor [uWSGI](https://uwsgi-docs.readthedocs.io/en/latest/). Se utiliza un servidor [NGINX](https://nginx.org/en/), también en un contenedor Docker, como proxy inverso y balanceador de carga entre ambos servidores uWSGI.

Para construir la imagen con el servidor uWSGI, ejecutar el siguiente comando:
```
$ docker-compose build
```

Para arrancar los contenedores, ejecutar el siguiente comando:
```
$ docker-compose up -d
```

Acceder a la aplicación con un navegador a http://localhost

---

Tags: devops, docker, flask, nginx, python, uwsgi
