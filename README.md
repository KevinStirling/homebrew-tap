# homebrew-tap

A [Homebrew](https://brew.sh) tap for my personal projects.

## Installation

First, add the tap:

```sh
brew tap kevinstirling/tap
```

Then install any of the casks listed below.

Alternatively, install a cask in one step without adding the tap first:

```sh
brew install --cask kevinstirling/tap/<cask-name>
```

## Available casks

| Cask | Description |
| --- | --- |
| [`scorebug`](Casks/scorebug.rb) | Live MLB scores in your terminal |

### scorebug

```sh
brew install --cask scorebug
```

Upstream: [KevinStirling/scorebug.sh](https://github.com/KevinStirling/scorebug.sh)

## Updating

```sh
brew update
brew upgrade --cask <cask-name>
```

## Uninstalling

```sh
brew uninstall --cask <cask-name>
brew untap kevinstirling/tap   # optional: remove the tap entirely
```

## License

See [LICENSE](LICENSE).
