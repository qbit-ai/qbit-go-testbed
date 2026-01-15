# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with this repository.

## Project Overview

This is a minimal Go testbed project (`qbit-go-testbed`) used for experimenting with Go code and testing tooling integrations.

## Common Commands

| Action | Command |
|--------|---------|
| Run | `go run main.go` |
| Build | `go build -o qbit-go-testbed main.go` |
| Test | `go test -v ./...` |
| Format | `go fmt ./...` |
| Lint | `go vet ./...` |

## Project Structure

- `main.go` - Main application entry point
- `go.mod` - Go module definition (module: qbit-go-testbed, Go 1.25)
- `.qbit/` - Qbit tool configuration
- `.vtcode/` - VTCode tool configuration

## Code Style

- Follow standard Go conventions and idioms
- Use `go fmt` for formatting
- Use `go vet` to check for common issues
- No external dependencies - uses only Go standard library
