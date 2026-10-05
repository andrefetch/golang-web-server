# Golang Web Server

A web server built in Go to handle some basic routes and form validation, built for learning more about HTTP Clients & Servers.

### Usage & Installation

Install go @ [go.dev](https://go.dev/dl/)

Clone This Project:

```sh
$ git clone https://github.com/andrefetch/golang-web-server.git
```

Run inside parent directory:
```sh
$ ./golang-web-server
```

Open where the port is listening, in this we are listening on port **8080** (localhost:8080)

### Architecture

Project:
```sh
[] static
   -- form.html
   -- index.html
go.mod
golang-web-server (executable)
main.go
```

Routes:
```sh
/
/hello
/form
```
