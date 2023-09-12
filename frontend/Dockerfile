FROM python:3.8-slim

WORKDIR /app

COPY ./frontend /app

RUN pip install --trusted-host pypi.python.org -r /app/requirements.txt

EXPOSE 80

ENV NAME Frontend

CMD ["python", "app.py"]

