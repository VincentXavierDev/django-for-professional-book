FROM python:3.9.10

ENV PYTHONDONTWRITEBYTECODE 1
ENV PYTHONUNBUFFERED 1

WORKDIR /chapter2_postgreSQL

COPY requirement.txt /chapter2_postgreSQL/
RUN pip install -r requirement.txt

COPY . /chapter2_postgreSQL/