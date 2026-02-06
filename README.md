# Homebrew Argos

Homebrew tap for [Argos Panoptes](https://github.com/rvielma/argos) - Web Security Scanner for Healthcare Environments.

## Installation

```bash
brew install rvielma/argos/argos
```

Or add the tap first:

```bash
brew tap rvielma/argos
brew install argos
```

## Upgrade

```bash
brew upgrade argos
```

## Uninstall

```bash
brew uninstall argos
brew untap rvielma/argos
```

## Usage

```bash
# List available scanner modules
argos modules

# Scan a target
argos scan https://example.com

# Scan with specific modules
argos scan https://example.com --modules headers,ssl,cookies

# Scan with all modules
argos scan https://example.com --modules all
```

## Platforms

| Platform | Architecture | Status |
|----------|-------------|--------|
| macOS | Apple Silicon (arm64) | Supported |
| macOS | Intel (x86_64) | Supported |
| Linux | x86_64 | Supported |

## Alternative Installation

If you prefer not to use Homebrew:

```bash
curl -sSL https://raw.githubusercontent.com/rvielma/argos/master/install.sh | bash
```

## License

MIT
