# Spacecoin RPC Documentation Generator

This tool extracts and formats the help text for each of the Spacecoin RPC calls. 

See the `script` directory for the `spacecoin.go` script that generates the output and template.

### How to use

Ensure that you have Go installed and a working and running a `spacecoind` or `komodod` instance. From the `script` directory simply run `go run spacecoin.go` and the documentation will be produced for all Spacecoin RPC calls and styled according to the template in `template.html`.
