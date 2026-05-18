# Twelve Data homebrew-cli

The official Homebrew tap for the [Twelve Data CLI](https://github.com/twelvedata/twelvedata-cli).

## Install

```sh
brew install twelvedata/cli/twelvedata
```

This adds the tap on first use and installs the `twelvedata` binary.

## Upgrade

```sh
brew update && brew upgrade twelvedata
```

## Uninstall

```sh
brew uninstall twelvedata
brew untap twelvedata/cli
```

## How this tap is maintained

The formula in `Formula/twelvedata.rb` is generated and committed automatically by [GoReleaser](https://goreleaser.com) from the [`twelvedata-cli`](https://github.com/twelvedata/twelvedata-cli) repository's release workflow. Each new tag in that repo bumps the formula's version and asset checksums.

Do not edit `Formula/twelvedata.rb` by hand — changes are overwritten on the next release.
