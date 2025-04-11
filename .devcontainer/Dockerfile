# Use a base image similar to Raspberry Pi OS (Debian-based)
FROM debian:bullseye

# Set up the environment
RUN apt-get update && apt-get install -y \
    build-essential \
    gdb \
    git \
    cmake \
    curl \
    wget \
    nano \
    pkg-config \
    libssl-dev \
    libcurl4-openssl-dev \
    python3 \
    python3-pip \
    && apt-get clean

# Set the default shell
SHELL ["/bin/bash", "-c"]
