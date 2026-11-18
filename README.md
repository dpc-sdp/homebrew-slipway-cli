# homebrew-slipway-cli

Homebrew tap for the Slipway CLI. The cask installs the CLI from the public releases in [dpc-sdp/slipway-cli](https://github.com/dpc-sdp/slipway-cli).

GoReleaser updates `Casks/slipway-cli.rb` on each Slipway release. Don't edit it by hand.

## Installation

```sh
brew tap dpc-sdp/slipway-cli
brew trust dpc-sdp/slipway-cli
brew install slipway-cli
```

Cask versions up to v0.35.0 download from the private `dpc-sdp/slipway` repository and need `HOMEBREW_GITHUB_API_TOKEN` set to a token that can read it. Later versions need no token.
