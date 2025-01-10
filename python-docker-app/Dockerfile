# Dockerfile

# Use official Python image from Docker Hub
FROM python:3.9-slim

# Set the working directory in the container
WORKDIR /usr/src/app

# Copy the current directory contents into the container
COPY python-app /usr/src/app

# Install dependencies (if any)
# RUN pip install --no-cache-dir -r requirements.txt

# Command to run the Python script
CMD ["python", "app.py"]
