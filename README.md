# TDK CLI public binaries

This repository intentionally contains **compiled release assets only**.

The TDK CLI source code is private. GitHub's automatic "Source code" downloads for this repository only contain this README, because this repository is only a public release channel.

## Install

```sh
curl -fsSL https://tdk-landscape.github.io/install.sh | sh
```

## Download binaries

Latest release:

https://github.com/tdk-landscape/tdk-cli-releases/releases/latest

Current assets:

- `tdk-cli-v1.1.0-binaries.zip` - all compiled binaries in one zip
- `tdk-linux-amd64` - Linux x86_64 / AMD64
- `tdk-linux-arm64` - Linux ARM64 / AArch64
- `tdk-darwin-amd64` - macOS Intel
- `tdk-darwin-arm64` - macOS Apple Silicon
- `checksums.txt` - SHA-256 checksums

## Docker Compose

Use the Docker Compose example if you do not want to install the binary on your host:

```sh
git clone https://github.com/tdk-landscape/tdk-docker-compose-example.git
cd tdk-docker-compose-example
docker compose run --rm tdk tdk --version
docker compose run --rm tdk tdk project --yes
```

Example repo:

https://github.com/tdk-landscape/tdk-docker-compose-example

