FROM python:3.7-alpine
WORKDIR /usr/src/app/

COPY requirements.txt .
COPY app.py .

EXPOSE 5000

RUN python -m pip install --no-cache-dir -r ./requirements.txt
CMD python ./app.py

