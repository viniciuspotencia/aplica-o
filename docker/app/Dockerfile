FROM python:3.9-slim

WORKDIR nextgenZ

COPY /nextgenZ/requirements.txt requirements.txt

RUN pip install --no-cache-dir -r requirements.txt

COPY nextgenZ/ .

EXPOSE 5000

CMD ["python", ]