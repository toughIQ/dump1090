FROM debian:latest

RUN apt update && apt install -y git make build-essential pkg-config rtl-sdr librtlsdr-dev

RUN git clone https://github.com/toughIQ/dump1090.git && cd dump1090

RUN make


