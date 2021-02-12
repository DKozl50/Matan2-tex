FROM ubuntu:18.04

RUN apt update \
    && DEBIAN_FRONTEND="noninteractive" apt install -y \
    texlive-full
RUN apt update && apt install -y \
    software-properties-common \
    && add-apt-repository -y ppa:git-core/ppa \
    && apt update \
    && apt install -y git
