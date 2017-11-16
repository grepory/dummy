# Dummy

## About

Dummy is a dummy service that responds on a /healthz endpoint on port 80. GET /healthz will return a 200
and a response body of "healthy" if the service is currently healthy. It will return a 500
and a response body of "unhealthy" if the service is unhealthy.

You can toggle the health of the service by issuing an empty POST request to the /healthz endpoint.

## Installation

You have two choices!

If you have Go, you can run `go get -u github.com/grepory/dummy`. It will then be in your
$GOPATH/bin.

Or you can [run it in Docker](https://hub.docker.com/r/grepory/dummy/).
