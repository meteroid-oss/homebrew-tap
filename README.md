# Meteroid Homebrew tap

Homebrew formulas for Meteroid's command line tools.

```sh
brew install meteroid-oss/tap/meteroid
```

Or tap once, then install by name:

```sh
brew tap meteroid-oss/tap
brew install meteroid
```

| Formula | Tool | Source |
|---|---|---|
| `meteroid` | The Meteroid API from the command line | [meteroid-oss/meteroid-cli](https://github.com/meteroid-oss/meteroid-cli) |

Upgrade with `brew upgrade meteroid`, remove with `brew uninstall meteroid`.

## How formulas get here

Each tool's release workflow writes its formula to `Formula/` once the release's binaries are
published, from the tool's repository: don't edit formulas here, a release overwrites them. The
[tests](.github/workflows/test.yml) install every changed formula on macOS and Linux and run it.
