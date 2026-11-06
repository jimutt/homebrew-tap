# jimutt/homebrew-tap

Homebrew casks for [spov](https://github.com/jimutt/spov), which runs coding agents in disposable cloud sandboxes.

```sh
brew install jimutt/tap/spov
```

The cask installs spov alone; install OpenCode 2 with its own installer (`curl -fsSL https://opencode.ai/v2/install | bash`), or use spov's install script, which brings the version spov expects:

```sh
curl -fsSL https://github.com/jimutt/spov/releases/latest/download/install.sh | sh -s -- --with-opencode
```

The casks here are written by spov's release workflow; do not edit them by hand.
