# Aria2 Static

Forked from [P3TERX/Aria2-Pro-Core](https://github.com/P3TERX/Aria2-Pro-Core)

This fork adapts aria2 to version 1.37.0 and updates the dependency packages.

## Quick Start
If you just want to download the latest version of aria2-static, you can download it from the release page:
- [https://cnb.cool/flyinbug/aria2-static-build/-/releases](https://cnb.cool/flyinbug/aria2-static-build/-/releases)

## Features
- Supports HTTP/HTTPS, FTP, BitTorrent, and Metalink protocols.
- High performance and low memory usage.
- Built-in support for session management.
- Supports IPv6.
- Extensible with plugins.

## Building
Just run the build script to compile the project:
```bash
# AMD64
bash aria2-gnu-linux-build-amd64.sh
# ARM64
bash aria2-gnu-linux-cross-build-arm64.sh
# ARM
bash aria2-gnu-linux-cross-build-armhf.sh
# i386
bash aria2-gnu-linux-cross-build-i386.sh
```

## Licence

[![GPLv3](gplv3.png)](LICENSE)
