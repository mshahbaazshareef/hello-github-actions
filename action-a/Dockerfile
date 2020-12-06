FROM debian:9.5-slim

ADD entrypoint.sh /entrypoint.sh
RUN git --version
RUN cat /etc/os-release
RUN chmod +x /entrypoint.sh
ENTRYPOINT ["/entrypoint.sh"]
