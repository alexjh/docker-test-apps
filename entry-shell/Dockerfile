FROM ubuntu

RUN \
    apt-get -qy update && \
    apt-get -qy install python && \
    rm -rf /var/lib/apt /var/cache/apt && \
    true

RUN /bin/true

ENTRYPOINT /usr/bin/python -m SimpleHTTPServer $PORT
