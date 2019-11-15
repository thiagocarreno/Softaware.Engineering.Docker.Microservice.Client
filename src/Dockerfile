FROM python:3.6-alpine
ADD /app /app
WORKDIR /app
ADD requirements.txt requirements.txt
RUN pip3 install -r requirements.txt
CMD ["python", "server.py"]

