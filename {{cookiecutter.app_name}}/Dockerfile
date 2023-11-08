# Use the official Python base image
FROM python:3.9

# Set the working directory in the container
WORKDIR /usr/src/app

# Copy only the necessary files (in this case, app.py) to the container
COPY app.py .

# Install Flask
RUN pip install Flask

# Expose the port on which the Flask app will run (8080)
EXPOSE 8080

# Define the command to run your Flask application
CMD ["python", "app.py"]
