FROM Ubuntu

RUN apt-get update
RUN apt-get install python

RUN pip install flask
RUN pip install flask-mysql

COPY . /opt/src/

ENTRYPOINT FLASK_APP=/opt/src/app.py flask run