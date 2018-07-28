docker build ./<Directory>/

docker run --rm -it -v <appdir>:<containerdir> <image>

Example:

docker build ./elixir/
docker run --rm -it -v ~/docker/elixir:/app 3e4c24a76153