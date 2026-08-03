# DataHop downloads

This repository hosts official binary releases of DataHop, a local-first PostgreSQL desktop explorer.

## Download

Open the [releases page](https://github.com/wbenafi/datahop-releases/releases) and choose the build for your Mac:

- `arm64` for Apple silicon Macs
- `x64` for Intel Macs

Each release includes `SHA256SUMS.txt` for integrity verification.

```sh
shasum -a 256 -c SHA256SUMS.txt
```

## About this repository

This is a binary-only distribution repository. It contains release artifacts and release notes, not the DataHop source code.
