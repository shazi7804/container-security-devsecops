FROM public.ecr.aws/bitnami/python:3.7.12

RUN pip install flask

ENV FLASK_APP app.py

WORKDIR /app

COPY . /app/

CMD ["python", "app.py"]
