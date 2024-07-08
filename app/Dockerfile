FROM python:3.12-slim

WORKDIR /app

COPY . .

RUN pip install requirements.txt

CMD gunicorn --bind 0.0.0.0:5000 wsgi:app