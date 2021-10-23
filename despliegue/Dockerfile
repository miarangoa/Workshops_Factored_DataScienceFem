FROM tiangolo/uvicorn-gunicorn-fastapi:python3.9-slim

WORKDIR /app

EXPOSE 80

COPY requirements2.txt .

RUN ["pip", "install", "-r","./requirements2.txt"]

COPY . .

CMD ["python3","main.py"]