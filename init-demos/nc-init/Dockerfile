FROM busybox:1.28

ENTRYPOINT ["/bin/sh", "-c", "until nc -zv ya.ru 80; do echo waiting; sleep 2; done"]
