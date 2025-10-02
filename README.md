# docs-style-guide
For use with Vale to lint docs

# Docs Style Guide with Vale

This repo demonstrates how to enforce a documentation style guide using [Vale](https://vale.sh).

## What’s included
- **.vale.ini** — Vale config file
- **styles/Custom/** — custom YAML rules (e.g., enforce “log in” instead of “login”)
- **docs/** — sample Markdown docs checked by Vale

## How to use
```bash
# Install Vale (macOS)
brew install vale

# Run Vale on the docs folder
vale docs/
