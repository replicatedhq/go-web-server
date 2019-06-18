Go Web Server
=============


A simple go web server for deployment demos.


Running
==========

If you have go installed, you can run with

```
go run .
```

If you don't have go, but you have docker, you can run with

```
docker run -it \
  -v `pwd`:/go/src/github.com/replicatedhq/go-web-server \
  --workdir /go/src/github.com/replicatedhq/go-web-server \
  -p 4000:4000 golang:latest \
  go run .
```
