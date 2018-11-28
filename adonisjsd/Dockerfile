FROM ubuntu

RUN apt update && \
    apt upgrade -y && \
    apt install nodejs -y && \
    apt install npm -y && \
    nodejs -v && npm -v && \
    npm i --global @adonisjs/cli && \
    rm -rf /var/lib/apt/lists/*

WORKDIR /app

CMD ["adonis"]