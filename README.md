# Caret Homebrew tap

Homebrew cask for [Caret](https://github.com/Fast-Editor/Caret), the Cursor-class AI code editor with a Rust core.

```sh
brew tap fast-editor/caret
brew trust fast-editor/caret   # Homebrew 7 asks once before loading a third-party tap
brew install --cask caret
```

Upgrade with `brew upgrade --cask caret`. Releases are ad-hoc signed until a Developer ID is configured, so the cask
clears the quarantine attribute after installing; see the Caret [install guide](https://github.com/Fast-Editor/Caret/blob/main/docs/INSTALL.md).

The cask previously lived in `fast-editor/lynkr`; that copy is deprecated and points here.
