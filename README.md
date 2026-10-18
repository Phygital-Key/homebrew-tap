# Phygital Key Homebrew tap

```bash
brew install phygital-key/tap/phygital-key-mcp   # for AI apps that speak MCP
brew install phygital-key/tap/phygital-key-a2a   # for agents that speak A2A
```

Each formula installs the signed release of its product from [Phygital Key MCP](https://github.com/Phygital-Key/phygital-key-mcp) or [Phygital Key A2A](https://github.com/Phygital-Key/phygital-key-a2a) and checks the SHA-256 of the download. The formulas are written by `scripts/package-manifests.sh` in each product's repository, for each release. Both products are built on [Phygital-Key/phygital-key](https://github.com/Phygital-Key/phygital-key).
