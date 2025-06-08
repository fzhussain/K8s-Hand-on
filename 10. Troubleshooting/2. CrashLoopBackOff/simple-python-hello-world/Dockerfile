# Use Python image as the base
FROM python:3.9-slim

# Set working directory in container
WORKDIR /app

# Copy the requirements and install them
COPY requirements.txt .
RUN pip install -r requirements.txt

# Copy your application code
COPY app.py .

# Command to run the Flask app
CMD ["python", "app.py"]

