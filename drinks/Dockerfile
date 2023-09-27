FROM python:3

ENV PYTHONUNBUFFERED 1

RUN mkdir /api

WORKDIR /api

ADD . /api/

RUN pip install -r requirements.txt
