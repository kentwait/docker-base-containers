# Alpine Linux + s6-overlay + glibc + Oracle JDK 8

Minimal Docker image based on Alpine Linux with a process supervisor.
S6-overlay is a process supervisor that cleans up zombie processes and
kills the container when things fail while su-exec provides a way to
execute programs with different privileges.

## Download

    docker pull kentwait/alpine-oraclejdk8-base

## Run

    docker run -it kentwait/alpine-oraclejdk8-base bash  # starts bash in /

## Specifications

- OS: Alpine Linux v3.4 from `gliderlabs/alpine:3.4`
- Directly based on `kentwait/alpine-glibc-base`
- Installed packages:
  - Oracle JDK 1.8.45.14
