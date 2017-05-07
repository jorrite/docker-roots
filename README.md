# docker-roots

## Purpose

This image was created specifically for usage with continuous integration systems, and contains the minimum requirements to generate a static website with [roots](https://roots.cx). 

## Details

### Base Image

* [node (boron)](https://hub.docker.com/r/library/node/) - The latest Node LTS (Boron) image

### Additional Node Modules

* [Roots](https://github.com/jescalan/roots) - Roots CLI.

## Colophon

Inspired by [docker-firebase](https://github.com/devillexio/docker-firebase).
