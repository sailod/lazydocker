
FROM golang:1.26rc3

WORKDIR /go/src/github.com/samber/lo

COPY Makefile go.* ./

RUN make tools
