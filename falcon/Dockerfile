#TODO: define original image

#TODO: expose port 80
RUN apt-get update
RUN apt-get install python-pip --assume-yes

RUN python -m pip install pip==9.0.1
#TODO: Use pip install to install falcon gunicorn falconjsonio kafka-python and cassandra-driver

COPY ./app /app
WORKDIR /app

#TODO: use CMD to launch gunicorn -b 0.0.0.0:80000 bdr:app
