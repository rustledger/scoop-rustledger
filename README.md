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
| `rledger` | Main CLI (`rledger check`, `rledger format`, `rledger query`, etc.) |
| `rledger-lsp` | Language Server Protocol implementation |

For Python beancount compatibility aliases (`bean-check`, `bean-format`, etc.), run `rledger compat install`.

## Links

- [Documentation](https://rustledger.github.io)
- [GitHub](https://github.com/rustledger/rustledger)
- [Releases](https://github.com/rustledger/rustledger/releases)
