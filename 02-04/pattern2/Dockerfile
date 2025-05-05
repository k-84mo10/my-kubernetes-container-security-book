FROM ubuntu:22.04

COPY PASSWORD ./PASSWORD

RUN echo Use credential: $(cat ./PASSWORD)

RUN rm ./PASSWORD

CMD ["/bin/sh", "-c", "while :; do sleep 10; done"]