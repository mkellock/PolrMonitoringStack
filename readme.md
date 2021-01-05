
# Polr Monitoring Stack

This project uses the kube-prometheus project (located at <https://github.com/prometheus-operator/kube-prometheus>)

## Dependencies

- **Go**, see <https://golang.org/doc/install>
- **Docker**, see <https://docs.docker.com/get-docker/>
- **Jsonnet Bundler**, after installing Go, install JB by running `go get github.com/jsonnet-bundler/jsonnet-bundler/cmd/jb`

## Building

- In PowerShell, run: `docker run --rm -v ${pwd}:/tmp --workdir /tmp quay.io/coreos/jsonnet-ci ./build.sh`
