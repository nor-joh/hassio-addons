FROM ghcr.io/home-assistant/base:latest

ENV LANG C.UTF-8

# Install xcomfortd
COPY --from=karloygard/xcomfortd:latest /usr/bin/xcomfortd /usr/bin/xcomfortd
COPY --from=karloygard/xcomfortd:latest /usr/lib/libusb-1.* /usr/lib/

COPY rootfs /
