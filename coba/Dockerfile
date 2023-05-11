FROM python:3.9-alpine
COPY requirements.txt .
RUN pip install --no-cache-dir -r requirements.txt
COPY . /app
WORKDIR /app
EXPOSE 5000
CMD ["python", "app.py"]
