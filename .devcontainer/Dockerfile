# Dockerfile
FROM mcr.microsoft.com/devcontainers/javascript-node:0-12

# Install the xz-utils package
RUN apt-get update && apt-get install -y xz-utils

WORKDIR /usr/src/app

COPY . .

EXPOSE 3000

CMD ["node", "index.js"]