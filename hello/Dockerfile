FROM ghcr.io/mooreryan/ocaml_alpine:4-14-2022-07-04-81d01c2

# Installs enough to build docs for bio_io package.

USER root

RUN apk add git

USER runner

RUN opam install \
    ocamlfind

WORKDIR /home/runner
