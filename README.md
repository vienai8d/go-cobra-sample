# go-cobra-sample

CLI with [Cobra](https://github.com/spf13/cobra).


## How to create CLI

Four steps to create CLI as below.

1. Install Cobra.
  ```bash
  go get -u github.com/spf13/cobra/cobra
  ```
2. Create `go.mod`.
  ```bash
  go mod init github.com/vienai8d/go-cobra-sample
  ```
3. Create CLI template.
  ```bash
  cobra init --pkg-name github.com/vienai8d/go-cobra-sample --author vienai8d
  ```
4. Edit `cmd/root.go`.


## How to install CLI

There are three ways to install and execute CLI.

1. `go build && ./go-cobra-sample`
2. `go install && go-cobra-sample`
3. `go get github.com/vienai8d/go-cobra-sample && go-cobra-sample`
