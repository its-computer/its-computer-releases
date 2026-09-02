# its.computer — releases

**Every agent needs a computer. This is its.** Make software, content and the routines of a business in real apps, with an agent in an isolated Linux desktop, on your real files. Website: https://its.computer · Docs: https://its.computer/docs/

This repository is the public home for:

- **Releases** — signed, notarized builds of the macOS app (Apple silicon). Download the latest `.dmg` from [Releases](https://github.com/its-computer/its-computer-releases/releases), or install with Homebrew:

  ```bash
  brew install --cask its-computer/tap/computer
  ```

- **Issues** — bug reports and feedback for the early builds.

The app's source code is in a private repository for now. Guest images are not stored here: the app downloads them on first run, and each release carries a `guest.json` manifest with the image URL, size and checksum.

Status: early access. Requires macOS on Apple silicon.
