FROM busybox:1.28
WORKDIR /
EXPOSE 8000

ENTRYPOINT ["/bin/sh", "-c", "until nslookup ya.ru; do echo waiting; sleep 2; done"]
