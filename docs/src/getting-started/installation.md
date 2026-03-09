# Installation

## Go install (recommended)

Requires Go 1.24+:

```bash
go install github.com/fabse-hack/bbscope/v2@latest
```

## Prebuilt binaries

Download from [GitHub Releases](https://github.com/fabse-hack/bbscope/releases). Binaries are available for Linux, macOS, and Windows (amd64/arm64).

## Docker

```bash
docker pull ghcr.io/fabse-hack/bbscope:latest
docker run --rm ghcr.io/fabse-hack/bbscope:latest poll h1 --user x --token y
```

## Build from source

```bash
git clone https://github.com/fabse-hack/bbscope.git
cd bbscope
go build -o bbscope .
```
