# Homebrew Tap for Entroly

Token-saving proxy and context compression engine for AI coding agents.

- **Main repo:** https://github.com/juyterman1000/entroly
- **Website:** https://entroly.dev
- **Cookbook:** https://github.com/juyterman1000/entroly/tree/main/cookbook

## Install

```bash
brew tap juyterman1000/entroly
brew install entroly
```

Then:

```bash
cd /your/repo
entroly go
```

## Update

```bash
brew update
brew upgrade entroly
```

## Uninstall

```bash
brew uninstall entroly
brew untap juyterman1000/entroly
```

## What's in this repo

| Path | Purpose |
|---|---|
| [`Formula/entroly.rb`](Formula/entroly.rb) | The Homebrew formula |
| [`.github/workflows/test.yml`](.github/workflows/test.yml) | CI: runs `brew test entroly` on every push |

The formula is generated from the canonical source in
[`packaging/homebrew/entroly.rb`](https://github.com/juyterman1000/entroly/blob/main/packaging/homebrew/entroly.rb)
of the main repo. On every release, the formula here is bumped to the new
PyPI sdist + sha256 (manually for now; consider
[`mislav/bump-homebrew-formula-action`](https://github.com/mislav/bump-homebrew-formula-action)
to automate).

## Issues with the formula?

Open an issue on the main repo:
https://github.com/juyterman1000/entroly/issues

## License

Apache-2.0 (matches the upstream package).
