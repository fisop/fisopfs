FROM ubuntu:24.04

RUN DEBIAN_FRONTEND=noninteractive \
	apt update && \
	apt install -y tzdata

RUN apt install -y \
	git make gdb \
	libbsd-dev libc6-dev gcc-multilib linux-libc-dev \
	pkg-config libfuse2 libfuse-dev

WORKDIR /fisopfs
