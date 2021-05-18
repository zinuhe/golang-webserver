# Golang WebServer
Simple Golang WebServer

Webserver is now running. Try interacting with it using curl

```console
curl http://localhost:3080
```
Hello, /

&nbsp;

```console
curl http://localhost:3080/jimmy
```
Hello, jimmy

Docker
$ docker build -t golang-webserver .

$ docker images

$ docker run -d -p 3080:3080 golang-webserver
