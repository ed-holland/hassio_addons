FROM bbernhard/signal-cli-rest-api:latest

WORKDIR /data/data/

RUN sed -i "s|/home/.local/share/signal-cli|/data/data|g" /entrypoint.sh

CMD ["-signal-cli-config", "/data/"]

VOLUME [ "/ssl", "/data"]
