FROM katsuya61/unicorn:latest

LABEL maintenar "katsuya sugawara"

ENV UNICORN_WORKER_PROCESSES 3
ENV UNICORN_SOCKET_TYPE UNIX

ADD ./app ${APP_ROOT}
