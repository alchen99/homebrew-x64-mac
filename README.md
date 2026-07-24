# homebrew-x64-mac
A Homebrew tap for Intel Macs with Homebrew API metadata whose url defaults to the MacOS Intel installer.

# Why this tap exists

Tools that use the Homebrew API don't always check the `variations` before just downloading from the `url`. This makes the `url` default to the MacOS Intel installer.

---

## Quickstart

```bash
# 1. Add this tap
brew tap alchen99/x64-mac

# 2. Install a cask (example: Bruno)
brew install --cask bruno

# 3. Or install using the fully-qualified name
brew install --cask alchen99/x64-mac/bruno

# 4. Keep casks up to date
brew update && brew upgrade --cask
```

---

## Available Casks

Browse all current entries in `Casks/`.

```bash
# List all tokens in this tap
ls Casks | sed 's/\.rb$//'
```

### Popular Casks in this Tap

These are examples of widely known apps available here:
is practically useful:

- bruno

