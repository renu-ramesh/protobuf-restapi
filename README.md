# protobuf-restapi
Protocol Buffers with REST API

**Technologies Used**
- Golang
- JSON
- Protocol Buffer

## Protocol Buffers

Protocol Buffers (Protobuf) is a free and open-source cross-platform data format used to serialize structured data. It is useful in developing programs to communicate with each other over a network or for storing data. The method involves an interface description language that describes the structure of some data and a program that generates source code from that description for generating or parsing a stream of bytes that represents the structured data.

## Application Setup

To run the application file:
    go run server.go

To create proto file:
    protoc --go_out=. echo.proto