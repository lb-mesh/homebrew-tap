# LBMesh Homebrew Tap

Official [Homebrew](https://brew.sh) tap for the `lbmesh` CLI.

## Install

```bash
brew install lb-mesh/tap/lbmesh
```

Or tap once, then install by name:

```bash
brew tap lb-mesh/tap
brew install lbmesh
```

## Upgrade

```bash
brew update && brew upgrade lbmesh
```

## How this tap is maintained

`Formula/lbmesh.rb` is generated and pushed by [GoReleaser](https://goreleaser.com)
from the [`lb-mesh/lbmesh`](https://github.com/lb-mesh/lbmesh) release pipeline
on every `v*` tag. Don't edit it by hand — changes are overwritten on the next release.
Pre-release tags (e.g. `v1.1.0-rc.1`) are not pushed here.
