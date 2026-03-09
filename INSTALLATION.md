# Installation

## Prerequisites

- [GitHub CLI](https://cli.github.com/) (`gh`) must be installed and authenticated.

### macOS (Homebrew)

```bash
brew install gh
gh auth login
```

### Linux

See the [GitHub CLI installation docs](https://github.com/cli/cli/blob/trunk/docs/install_linux.md) for distro-specific instructions.

---

## gh-dash

[gh-dash](https://github.com/dlvhdr/gh-dash) is a terminal dashboard for GitHub PRs, issues, and notifications.

### Install via gh

```bash
gh extension install dlvhdr/gh-dash
```

### Install from source

```bash
git clone https://github.com/dlvhdr/gh-dash
cd gh-dash
gh extension install .
```

### Run

```bash
gh dash
```

### Nerd Font

gh-dash uses icons that require a [Nerd Font](https://www.nerdfonts.com/). Install one for proper rendering:

```bash
# macOS
brew install --cask font-fira-code-nerd-font
```

Then set your terminal's font to the installed Nerd Font.

---

For full gh-dash configuration and usage, see the [official docs](https://www.gh-dash.dev/).
