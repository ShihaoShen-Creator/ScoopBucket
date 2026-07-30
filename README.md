# Scoop Bucket

[![Tests](https://github.com/ShihaoShen-Creator/ScoopBucket/actions/workflows/ci.yml/badge.svg)](https://github.com/ShihaoShen-Creator/ScoopBucket/actions/workflows/ci.yml) [![Excavator](https://github.com/ShihaoShen-Creator/ScoopBucket/actions/workflows/excavator.yml/badge.svg)](https://github.com/ShihaoShen-Creator/ScoopBucket/actions/workflows/excavator.yml)

A bucket for [Scoop](https://scoop.sh), the Windows command-line installer.

## How do I install these manifests?

Run the following:

```pwsh
scoop bucket add extras
scoop bucket add games
scoop bucket add nerd-fonts
scoop bucket add nirsoft
scoop bucket add sysinternals
scoop bucket add java
scoop bucket add nonportable
scoop bucket add php
scoop bucket add versions
scoop bucket add shihao https://github.com/ShihaoShen-Creator/ScoopBucket
scoop install shihao/<manifestname>
```

## How do I contribute new manifests?

To make a new manifest contribution, please read the [Contributing
Guide](https://github.com/ScoopInstaller/.github/blob/main/.github/CONTRIBUTING.md)
and [App Manifests](https://github.com/ScoopInstaller/Scoop/wiki/App-Manifests)
wiki page.
