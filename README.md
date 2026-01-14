# Scoop Bucket for rustledger

This bucket provides [rustledger](https://github.com/rustledger/rustledger), a fast pure Rust implementation of Beancount double-entry accounting.

## Installation

```powershell
scoop bucket add rustledger https://github.com/rustledger/scoop-rustledger
scoop install rustledger
```

## Upgrading

```powershell
scoop update rustledger
```

## Commands

After installation, you'll have access to:

| Command | Description |
|---------|-------------|
| `rledger-check` | Validate ledger files |
| `rledger-format` | Auto-format beancount files |
| `rledger-query` | Run BQL queries |
| `rledger-report` | Generate reports |
| `rledger-doctor` | Debugging tools |
| `rledger-extract` | Import from CSV/OFX |
| `rledger-price` | Fetch commodity prices |

Python beancount compatibility aliases (`bean-*`) are also included.

## Links

- [Documentation](https://rustledger.github.io)
- [GitHub](https://github.com/rustledger/rustledger)
- [Releases](https://github.com/rustledger/rustledger/releases)
