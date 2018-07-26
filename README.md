# Niltalk
http://niltalk.com

April 2015; License: AGPL3

Niltalk is a simple, private, persistence-free web based multi-room chat server + client  written in Go that uses Websockets for communication.

### Installation
`go get github.com/goniltalk/niltalk`

You can download the package dependencies by switching to the `niltalk` directory in your GOPATH and running `go get ./...`

### Usage
- Have a Redis instance running
- Configure the necessary values in `config.json`
- Ensure that `config.json`:`url` is set to the hostname as visible by the client, otherwise you will receive 'unknown error'
- Execute `./run` in the `niltalk` directory in your GOPATH (You may have to set the permission to 755 by doing `chmod 755 ./run`)
