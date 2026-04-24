# `marquesds/tap` — Homebrew formulae

Install with:

```bash
brew tap marquesds/tap
```

## `kaizen-cli`

[![kaizen](https://img.shields.io/badge/source-marquesds%2Fkaizen-0366d6)](https://github.com/marquesds/kaizen)

```bash
brew install marquesds/tap/kaizen-cli
# or after tapping:
brew install kaizen-cli
```

Puts the `kaizen` binary on your `PATH`. The formula tracks [GitHub Releases](https://github.com/marquesds/kaizen/releases); after each release, checksums in `Formula/kaizen-cli.rb` are updated to match the published `kaizen-v*-*.tar.gz` assets.

If `brew install` fails with a checksum error, a new release may have shipped — open an issue on [kaizen](https://github.com/marquesds/kaizen) or bump the formula SHAs to match the release page.

## Not in homebrew-core

This is a [third-party tap](https://docs.brew.sh/Taps), not the default `homebrew/core` list.
