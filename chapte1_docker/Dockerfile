# Pull base image
FROM python:3.9.10
# Set environment variables
ENV PYTHONDONTWRITEBYTECODE 1
ENV PYTHONUNBUFFERED 1
# Set work directory
WORKDIR /chapte1_docker
# Install dependencies
COPY requirement.txt /chapte1_docker/
RUN pip install -r requirement.txt
# Copy project
COPY . /chapte1_docker/
