FROM ubuntu:18.04
LABEL maintainer="Alexander Belyavskiy"
LABEL Description="Ubuntu_18.04 ARM64 Swift4_2_2"

RUN set -x && apt-get update -y && apt-get install curl apt-utils -y && curl -s https://packagecloud.io/install/repositories/swift-arm/release/script.deb.sh | bash 
RUN apt-get install swift4=4.2.2 git -y