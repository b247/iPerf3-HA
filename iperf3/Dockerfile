ARG BUILD_FROM=ghcr.io/home-assistant/amd64-base:latest
FROM $BUILD_FROM

# Install iPerf3 into Alpine Linux
RUN apk add --no-cache iperf3

# Copy startup script
COPY run.sh /
RUN chmod +x /run.sh

CMD [ "/run.sh" ]
