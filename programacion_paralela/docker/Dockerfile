# Esta imagen es para usar sólo en desarrollo, para más info leer: https://hub.docker.com/r/nvidia/cuda
FROM nvidia/cuda:12.8.0-devel-ubuntu24.04

RUN apt update
RUN apt install -y \
  curl \
  git \
  neovim \
  vim \
  wget

WORKDIR /app
