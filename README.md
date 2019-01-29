# meproxy

> A simple command line tool for proxy some web requests using socks5.


## Installation

```console
$ go get github.com/jeremaihloo/meproxy

# $GOPATH/bin/meproxy
```

## Usage

```console
$ meproxy --help

A proxy command line tool.

Usage:
  meproxy [command]

Available Commands:
  config      Config for current user.
  help        Help about any command
  serve       Serve meproxy on this machine.

Flags:
      --config string   config file (default is $HOME/.meproxy.yaml)
  -t, --toggle          Help message for toggle

Use "meproxy [command] --help" for more information about a command.
```

## LICENSE

MIT @ jeremaihloo1024@gmail.com