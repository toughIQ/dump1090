# OCI compliant container image

## BUILD
`podman build -t quay.io/toughiq/dump1090:latest .`

## RUN
Has yet to be tested with compliant USB DVB-T device

`podman run -it --rm --privileged -p 8080:8080 -v /dev/bus/usb:/dev/bus/usb quay.io/toughiq/dump1090:latest`

Within the container start `dump1090` via: `./dump1090 --net`

Connect on your local browser to `http://localhost:8080` 


