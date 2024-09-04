FROM python:3.6-stretch

RUN mkdir /app

COPY . /app

RUN pip install --upgrade -r requirements.txt

ENV FLASK_APP=src/app.py

EXPOSE 5000

CMD flask run --host 0.0.0.0 --port 5000