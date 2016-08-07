FROM elasticsearch:latest

RUN apt-get update

RUN bin/plugin install license
RUN bin/plugin install marvel-agent

CMD ["elasticsearch"]
