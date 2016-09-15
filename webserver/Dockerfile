FROM golang:onbuild

COPY . /go/src/app
RUN go get -d -v
RUN go install -v

EXPOSE 8080
CMD ["app"]
