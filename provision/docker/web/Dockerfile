FROM python:3.6.1

MAINTAINER Luis Mayta <@slovacus>

LABEL NAME ansible-role-nginx-dev
LABEL VERSION 1.0.1

COPY ./requirements/ /usr/src/requirements/
COPY ./requirements.txt /usr/src/requirements.txt

# set working directory to /usr/src/
WORKDIR /usr/src/

RUN pip install -r /usr/src/requirements/dev.txt
