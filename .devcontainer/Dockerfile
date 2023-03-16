FROM mcr.microsoft.com/devcontainers/base:ubuntu
# Install the xz-utils package
RUN apt-get update && apt-get install -y xz-utils
WORKDIR /app
COPY . /app
EXPOSE 5000

