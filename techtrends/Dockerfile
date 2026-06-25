# Python 3.8 base image
FROM python:3.8

LABEL maintainer="Hari Kishan Dande"

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
