FROM python:3.7.2-slim

COPY . /app
WORKDIR /app

RUN pip install --upgrade pip
RUN pip install --proxy=http://proxy-ap.shell.com:80 flask


ENTRYPOINT ["python", "app.py"]
