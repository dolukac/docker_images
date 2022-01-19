FROM scratch

LABEL mantainer = "domo"
LABEL description = "super matrix"
ADD alpine-minirootfs-3.15.0-x86_64.tar.gz /

RUN apk add cmatrix

CMD ["/usr/bin/cmatrix"]
