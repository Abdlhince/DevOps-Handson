FROM python:alpine
COPY . /app
WORKDIR /app

ENV MYSQL_DATABASE_HOST database
ENV MYSQL_DATABASE_USER clarusway
ENV MYSQL_DATABASE_PASSWORD Clarusway_1
ENV MYSQL_DATABASE_DB todo_db

RUN pip install -r requirements.txt
EXPOSE 80
CMD python ./to-do-api.py