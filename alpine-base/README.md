# Alpine Linux + s6-overlay

Minimal Docker image based on Alpine Linux with a process supervisor.
S6-overlay is a process supervisor that cleans up zombie processes and
kills the container when things fail while su-exec provides a way to
execute programs with different privileges.

## Download

    docker pull kentwait/alpine-base

## Run

    docker run -it kentwait/alpine-base bash  # starts bash in /

## Specifications

- OS: Alpine Linux v3.4 from `gliderlabs/alpine:3.4`
- Installed packages:
  - s6-overlay v1.18.1.5
  - bash

## Other customizations

- `LC` and `LANG` set to `C.UTF-8`