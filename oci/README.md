# OCI compliant container image

## BUILD
`podman build -t quay.io/toughiq/dump1090:latest .`

## RUN
Has yet to be tested with compliant USB DVB-T device

`podman run -it --rm --privileged -v /dev/bus/usb:/dev/bus/usb quay.io/toughiq/dump1090:latest`


