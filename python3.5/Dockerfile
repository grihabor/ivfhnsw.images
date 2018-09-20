FROM python:3.5
MAINTAINER Borodin Gregory <grihabor@gmail.com>

RUN apt update \
 && apt install -y cmake make g++ swig libopenblas-dev

RUN pip install --upgrade \
        pip \
        wheel \
        setuptools
