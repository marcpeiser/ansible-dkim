FROM debian:stretch

ADD build /build

RUN /build/prepare.sh && \
	/build/install.sh && \
	/build/cleanup.sh

ENTRYPOINT ["/sbin/init"]
