# 
FROM python:3.11-alpine3.17

# 
WORKDIR /app

# 
COPY requirements.txt requirements.txt

# 
RUN pip install -r requirements.txt

# 
COPY . .

EXPOSE 8000

CMD ["python", "main.py"]