# qbit-go-testbed

A simple Go testbed/playground project for experimenting with Go code and testing tooling integrations.

## Requirements

- Go 1.25+

## Getting Started

### Run the application

```bash
go run main.go
```

### Build a binary

```bash
go build -o qbit-go-testbed main.go
./qbit-go-testbed
```

## Development

### Format code

```bash
go fmt ./...
```

### Lint/check for issues

```bash
go vet ./...
```

### Run tests

```bash
go test -v ./...
```

## Project Structure

```
qbit-go-testbed/
├── go.mod      # Go module definition
├── main.go     # Main application entry point
├── .qbit/      # Qbit tool configuration
└── .vtcode/    # VTCode tool configuration
```

## License

[Add license information here]
