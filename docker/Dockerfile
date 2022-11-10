FROM amazonlinux:2

RUN apt-get install

USER root
ADD a b

COPY --from=nonexistant a b

ENTRYPOINT ls
ENTRYPOINT ls
CMD ls
CMD ls
