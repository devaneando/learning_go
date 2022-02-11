# Start

## Documentation

- [Go](https://go.dev)
- [Go Documentation](https://go.dev/doc/)
- [Tutorial: Get started with Go](https://go.dev/doc/tutorial/getting-started)

## Installation

For more information, check [Install the latest version of Go](https://go.dev/learn/) and [Download and install](https://go.dev/doc/install).

Download the lastest Go version (_in this case, go1.17.7.linux-amd64.tar.gz_).

```bash
sudo rm -rf /usr/local/go && sudo tar -C /usr/local -xzf go1.17.7.linux-amd64.tar.gz
```

Add go binaries to your path, by adding the lines below to your `.bashrc` file:

```bash
if [ -d "/usr/local/go/bin" ]; then
    export PATH="/usr/local/go/bin:${PATH}"
fi
```

Check if go is installed:

```bash
go version
$ go version go1.17.7 linux/amd64
```

Add your environment variables to your `.bashrc` file:

```bash
export GOPATH="${HOME}/Development/Go"
export GOROOT="/usr/local/go/bin"
```
