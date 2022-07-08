FROM ghcr.io/mooreryan/ocaml_alpine:4-14-2022-07-04-81d01c2

USER root

RUN apk add git

USER runner

RUN opam install \
    ocamlfind

WORKDIR /home/runner
