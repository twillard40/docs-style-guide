# AI-Augmented Docs Pipeline (Vale + GitHub Actions)

This repo demonstrates a proof-of-concept for an automated documentation workflow:
a custom Vale style guide integrated with GitHub Actions for continuous linting and style enforcement.
It’s designed as the foundation for AI-assisted content generation and standardization.

## What's Included
- **.vale.ini** – Main Vale configuration file  
- **styles/Custom/** – Custom YAML rules (e.g., enforce “log in” instead of “login”)  
- **.github/workflows/vale.yml** – GitHub Actions CI pipeline that runs Vale on every pull request  
- **docs/** – Sample Markdown files linted by Vale  
- **templates/** – Placeholder for Concept–Task–Reference and AI-assisted templates  

## How to Use

```bash
# Install Vale (macOS)
brew install vale

# Run Vale locally
vale docs/

# Run Vale via GitHub Actions
# Push or open a PR — the CI job will automatically check all Markdown files

