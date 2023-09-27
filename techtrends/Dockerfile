FROM python:3.8-alpine
LABEL maintainer="Thai Son Tran"

EXPOSE 3111/tcp

COPY . /app
WORKDIR /app

RUN pip install -r requirements.txt

CMD ["python" , "app.py"]
