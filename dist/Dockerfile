# Use an official Python runtime as a parent image
FROM python:3

# Set the working directory to /app
WORKDIR /app

# Copy the contents of the current directory into the container at /app
COPY . /app

# Install any necessary dependencies
# For example, if you need to install a web server, you can use 'apt-get' or 'pip' to install it here.

# Expose the port that your web server will listen on
EXPOSE 80

# Define the command to start your services
CMD ["python3", "-m", "http.server", "80"]
