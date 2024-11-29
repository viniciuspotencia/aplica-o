FROM python:3.9-slim

WORKDIR app

COPY /app/requirements.txt requirements.txt

RUN pip install --no-cache-dir -r requirements.txt

COPY app/ .

EXPOSE 5000

ENV FLASK_APP=app.py FLASK_RUN_HOST=0.0.0.0 FLASK_RUN_PORT=5000

CMD ["flask", "run"]