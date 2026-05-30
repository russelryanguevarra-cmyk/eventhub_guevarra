FROM mcr.microsoft.com/devcontainers/python:3.11

# Installa Node.js 18 e Angular CLI
RUN curl -fsSL https://deb.nodesource.com/setup_18.x | bash - \
    && apt-get install -y nodejs \
    && npm install -g @angular/cli