FROM python:3.13-slim

WORKDIR /app

COPY . /app

RUN pip install --no-cache-dir -r /app/requirements.txt

EXPOSE 3000
EXPOSE 6000

CMD ["python3", "main.py"]