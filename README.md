# Gravey158/homebrew-cdripper

Homebrew Tap for [cdripper](https://github.com/Gravey158/cdripper) — audio CD ripper
with MusicBrainz tagging and AccurateRip verification.

## Install

```sh
brew tap gravey158/cdripper
brew install --cask cdripper
```

The DMG is pulled from `flatpak.x2-pandora.de`, signed via Sparkle EdDSA.
Updates either via `brew upgrade --cask cdripper` or the built-in Sparkle
24h-check from inside the app.

## Source of the Cask

The canonical Cask formula lives in the [main cdripper
repo](https://github.com/Gravey158/cdripper/blob/main/homebrew/Casks/cdripper.rb).
This tap repo mirrors it on each release via
`scripts/publish-mac-release.sh`.
