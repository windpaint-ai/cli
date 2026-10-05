# windpaint CLI

Releases of the `windpaint` command-line client for [Windpaint](https://windpaint.ai): generate images
and video from a terminal, a script or an agent. One static binary per platform.

This repository hosts release binaries only. The source is not published here.

## Install

```sh
curl -fsSL https://get.windpaint.ai | sh
```

```sh
brew install windpaint-ai/tap/windpaint
```

Pin a version or pick the install directory:

```sh
curl -fsSL https://get.windpaint.ai | WINDPAINT_VERSION=0.1.0 WINDPAINT_INSTALL_DIR=~/bin sh
```

Or download an archive for your platform (Linux, macOS, Windows; amd64 and arm64) from
[Releases](https://github.com/windpaint-ai/cli/releases) and check it against `checksums.txt`.

## Get started

```sh
windpaint auth login --api-key aak_...
windpaint run image.generate "a lighthouse at dusk" -o lighthouse.png
```

Docs: https://docs.windpaint.ai/cli/install
