FROM gethue/hue:latest

#RUN apt-get update && apt-get -y install python3 python3-setuptools python3-pip

#RUN pip3 install sqlalchemy

RUN rm -rf sqlalchemy-drill

RUN git clone https://github.com/JohnOmernik/sqlalchemy-drill && cd sqlalchemy-drill && ../build/env/bin/python setup.py install