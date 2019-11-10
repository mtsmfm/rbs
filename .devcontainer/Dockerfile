FROM rubylang/ruby:master-nightly-bionic

RUN useradd --create-home --user-group app && mkdir /app && chown app:app /app

RUN apt-get update -q && apt-get install -y less zsh curl gnupg

WORKDIR /app

USER app
