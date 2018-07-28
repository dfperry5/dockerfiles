FROM alpine

RUN apk add --update elixir

RUN mix archive.install https://github.com/phoenixframework/archives/raw/master/phx_new.ez --force
RUN mix local.hex --force
RUN mix local.rebar --force

WORKDIR /app