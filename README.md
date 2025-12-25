# docker
docker pull bluenviron/mediamtx:latest
docker save -o mediamtx_latest.tar bluenviron/mediamtx:latest
python3 -m http.server 8000