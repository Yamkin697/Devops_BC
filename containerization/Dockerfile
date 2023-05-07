FROM python:3.8-slim-buster

WORKDIR /app

ADD requirements.txt requirements.txt
RUN pip3 install -r requirements.txt
EXPOSE 5000
ENV INCONTEINER True
COPY . .

ENTRYPOINT [ "python3", "app.py" ]