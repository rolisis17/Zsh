# Zsh Configuration

Personal Zsh configuration for a 42 Lisboa development environment.

This repository is intentionally small: it keeps the shell setup that made the school environment easier to use, especially around path fixes and daily terminal quality of life.

## What it includes

- `.zshrc` shell startup configuration
- 42 Lisboa path adjustments
- Environment exports
- Personal aliases and shortcuts
- Local setup notes

## Usage

Review the file before sourcing it:

```bash
less .zshrc
```

Apply it in the current shell:

```bash
source .zshrc
```

Or copy the relevant parts into your own `~/.zshrc`.

## Technical highlights

- Keeps environment-specific fixes in one visible place
- Makes terminal setup reproducible
- Documents the small configuration details that are easy to forget when moving machines

## Skills demonstrated

- Shell customization
- Developer environment setup
- PATH and startup-file management
- Keeping personal tooling versioned

## Notes

This configuration is machine and school-environment specific. Check paths before using it somewhere else.
