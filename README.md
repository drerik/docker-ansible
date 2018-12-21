# docker-ansible
A container based on `ubuntu:18.04` with ansible preinstalled. Workdir is set to `/ansible`

Contains the following tools:
- ansible
- git


## Usage
```
docker run --rm -it drerik/ansible bash
```

## Build
```
docker build -t drerik/ansible .
```
