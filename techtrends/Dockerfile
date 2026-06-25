# Use a Python 3.8 base image.
# NOTE: The project brief asks for "Python version 3.8". The starter
# requirements.txt originally pinned Flask 3.1.0, which dropped Python 3.8
# support, so Flask is pinned to 3.0.3 (the latest release that supports 3.8).
FROM python:3.8

LABEL maintainer="TechTrends Platform Engineer"

# Working directory inside the container
WORKDIR /app

# Copy the TechTrends application source into the image
COPY . /app

# Install the Python packages defined in requirements.txt
RUN pip install --no-cache-dir -r requirements.txt

# Initialize the database with the pre-defined posts
RUN python init_db.py

# Expose the application port
EXPOSE 3111

# Run the application when the container starts
CMD ["python", "app.py"]
