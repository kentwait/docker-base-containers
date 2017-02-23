# Alpine Linux + s6-overlay + glibc

Minimal Docker image based on Alpine Linux with a process supervisor and glibc.
Based on [alpine-base](https://github.com/kentwait/alpine-base).

## Download

    docker pull kentwait/alpine-glibc

## Run

    docker run -it kentwait/alpine-glibc bash  # starts bash in /

## Specifications

- OS: Alpine Linux v3.4 from `gliderlabs/alpine:3.4`
- Directly based on `kentwait/alpine-base`
- Additional installed packages:
  - glibc