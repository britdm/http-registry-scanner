# registry-scanner
alpha repository

Scripts are created to scan an insecure private Docker registry at port `5000` with the basic authentication from `brittanym/registry:2.0`.

## quick start
To start, clone this repository.

### go
- In the local directory build the module `go build`
- To add the module to the `$GOPATH/bin` run `go install`, this will build and move the module in a single step

### python
- see the [registry-scanner-python](https://github.com/britdm/http-registry-scanner-python) project

## future goals
- Enable input for variables `registry url`, `username`, and `password`.
- Binary files to simplify installation and use of the scanner.