# Dockerfile
FROM mcr.microsoft.com/vscode/devcontainers/javascript-node:0-16-buster

# Install extra tooling into the environment via the following command
RUN apt-get update && apt-get install vim

RUN apt-get update && export DEBIAN_FRONTEND=noninteractive \
    && apt-get -y install git

WORKDIR /usr/src/app

COPY . .

EXPOSE 3000

CMD ["node", "index.js"]
