# Dockerfile
FROM mcr.microsoft.com/devcontainers/javascript-node:0-18
RUN apt-get update && export DEBIAN_FRONTEND=noninteractive \
    && apt-get -y install git
WORKDIR /usr/src/app

COPY . .

EXPOSE 3000

CMD ["node", "index.js"]
