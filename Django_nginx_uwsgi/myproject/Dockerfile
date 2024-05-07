FROM python:3.8.10
LABEL maintainer Ian
ENV PYTHONUNBUFFERED 1
RUN mkdir /app
WORKDIR /app
COPY . /app
RUN pip install -r requirements.txt

# for entry point
RUN chmod +x /app/docker-entrypoint.sh