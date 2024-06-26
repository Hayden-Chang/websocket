# gorilla/websocket

![testing](https://github.com/Hayden-Chang/websocket/actions/workflows/test.yml/badge.svg)
[![codecov](https://codecov.io/github/gorilla/websocket/branch/main/graph/badge.svg)](https://codecov.io/github/gorilla/websocket)
[![godoc](https://godoc.org/github.com/Hayden-Chang/websocket?status.svg)](https://godoc.org/github.com/Hayden-Chang/websocket)
[![sourcegraph](https://sourcegraph.com/github.com/Hayden-Chang/websocket/-/badge.svg)](https://sourcegraph.com/github.com/Hayden-Chang/websocket?badge)

Gorilla WebSocket is a [Go](http://golang.org/) implementation of the [WebSocket](http://www.rfc-editor.org/rfc/rfc6455.txt) protocol.

![Gorilla Logo](https://github.com/gorilla/.github/assets/53367916/d92caabf-98e0-473e-bfbf-ab554ba435e5)


### Documentation

* [API Reference](https://pkg.go.dev/github.com/Hayden-Chang/websocket?tab=doc)
* [Chat example](https://github.com/Hayden-Chang/websocket/tree/main/examples/chat)
* [Command example](https://github.com/Hayden-Chang/websocket/tree/main/examples/command)
* [Client and server example](https://github.com/Hayden-Chang/websocket/tree/main/examples/echo)
* [File watch example](https://github.com/Hayden-Chang/websocket/tree/main/examples/filewatch)
* [Write buffer pool example](https://github.com/Hayden-Chang/websocket/tree/main/examples/bufferpool)

### Status

The Gorilla WebSocket package provides a complete and tested implementation of
the [WebSocket](http://www.rfc-editor.org/rfc/rfc6455.txt) protocol. The
package API is stable.

### Installation

    go get github.com/Hayden-Chang/websocket

### Protocol Compliance

The Gorilla WebSocket package passes the server tests in the [Autobahn Test
Suite](https://github.com/crossbario/autobahn-testsuite) using the application in the [examples/autobahn
subdirectory](https://github.com/Hayden-Chang/websocket/tree/main/examples/autobahn).
