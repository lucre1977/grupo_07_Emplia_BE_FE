# Use the official Python image as the base image
FROM python:3.8

# Set the working directory in the container[^1^][1]
WORKDIR /app

# Copy the application files into the working directory[^2^][2]
COPY . /app

# Install the application dependencies
RUN pip install -r requirements.txt

# Define the entry point for the container[^3^][3]
CMD ["python", "manage.py", "runserver", "0.0.0.0:8000"]
