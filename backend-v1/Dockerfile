FROM python:3.8-slim

WORKDIR /app

COPY ./backend-v1 /app

RUN pip install --trusted-host pypi.python.org -r /app/requirements.txt

EXPOSE 80

ENV NAME Backend-v1

CMD ["python", "app.py"]

