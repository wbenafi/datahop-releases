# DataHop downloads

This repository hosts the public landing page and official binary releases of DataHop, a local-first PostgreSQL desktop explorer.

Visit [datahop.vercel.app](https://datahop.vercel.app) to learn more.

## Download

Open the [releases page](https://github.com/wbenafi/datahop-releases/releases) and choose the build for your Mac:

- `arm64` for Apple silicon Macs
- `x64` for Intel Macs

Each release includes `SHA256SUMS.txt` for integrity verification.

```sh
shasum -a 256 -c SHA256SUMS.txt
```

## About this repository

This is a distribution repository. It contains the public landing page, release artifacts, and release notes—not the DataHop application source code.
