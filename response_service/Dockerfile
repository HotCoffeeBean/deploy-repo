FROM python:3.11

WORKDIR /app

COPY . .

RUN pip install flask pyjwt requests flask-cors

CMD ["python", "app.py"]