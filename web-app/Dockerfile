# Use the official Python 3.9 slim image
FROM python:3.9-slim

# Set the working directory in the container
WORKDIR /app

# Copy the api source code to /app/api
COPY . /app/

RUN pip install --no-cache-dir -r api/requirements.txt

# Copy the main application file and requirements.txt
#COPY app.py /app/

#COPY requirements.txt /app/

# Install the requirements
RUN pip install --no-cache-dir -r requirements.txt

# Make port 5000 available to the world outside this container
EXPOSE 5000

# Define environment variable for Flask to run on 0.0.0.0
ENV FLASK_RUN_HOST=0.0.0.0
ENV FLASK_RUN_PORT=5000

# Run the application
CMD ["python", "app.py"]
