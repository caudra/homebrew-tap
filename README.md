# Homebrew tap for Caudra

```sh
brew install caudra/tap/caudra
```

This installs the newest published [Caudra](https://caudra.ai) release, previews included, on macOS and Linux. It uses the release archives and the checksums from the release's `sha256sums.txt`.

Update with `brew upgrade caudra`. `caudra update` leaves Homebrew installations to Homebrew.

A scheduled workflow regenerates `Formula/caudra.rb` with `scripts/update_formula.py` after each release, then installs and tests it on macOS and Linux. Do not edit the formula by hand.

Caudra is released under the [Apache License 2.0](https://github.com/caudra/caudra/blob/main/LICENSE). Source: [github.com/caudra/caudra](https://github.com/caudra/caudra).
