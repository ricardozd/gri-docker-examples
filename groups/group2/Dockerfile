FROM python:3.8.5

WORKDIR /app

ADD requirements.txt /app
ADD app.py /app

RUN pip install -r requirements.txt

CMD ["python", "app.py"]
