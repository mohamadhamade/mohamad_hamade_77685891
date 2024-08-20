FROM mcr.microsoft.com/devcontainers/universal:2-linux
# Install the xz-utils package
RUN apt-get update && \
apt-get install -y xz-utils && \
apt-get install -y mongodb-clients && \
pip install django

# Expose the default MongoDB port
EXPOSE 27017