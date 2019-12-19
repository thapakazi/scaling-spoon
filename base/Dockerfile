FROM ubuntu:18.04

ENV DEBIAN_FRONTEND=noninteractive

RUN apt-get update --fix-missing && \
    apt-get upgrade && apt install -y \
    curl \
    git \
    wget \
    make \
    sox \
    automake \
    autoconf \
    bzip2 \
    build-essential \
    cmake \
    unzip \
    pkg-config \
    ffmpeg \
    vim \
    gcc-7 \
    g++-7 \
    libxmu-dev \
    libxi-dev \
    libglu1-mesa \
    libglu1-mesa-dev \
    libjpeg-dev \
    libpng-dev \
    libtiff-dev \
    libavcodec-dev \
    libavformat-dev \
    libswscale-dev \ 
    libv4l-dev \
    libxvidcore-dev \
    libx264-dev \
    libgtk-3-dev \
    libopenblas-dev \
    libopencv-dev \
    libatlas-base-dev \
    liblapack-dev \
    libtool \
    gfortran \
    openjdk-8-jdk \
    libhdf5-serial-dev \
    unzip \
    zlib1g-dev \
    python3-dev \
    python3-tk \
    python-imaging-tk \
    python-opencv \
    python-numpy \
    python-pycurl \
    python-opencv \
    python3-yaml \
    python3-matplotlib \
    && rm -rf /var/lib/lists/*
