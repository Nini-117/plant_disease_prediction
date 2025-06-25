FROM python:3.10-slim

WORKDIR /app

COPY . /app

# ✅ Debug: Check what's inside the /app folder
RUN ls -la /app

RUN pip install --no-cache-dir -r requirements.txt

CMD ["python", "main.py"]

