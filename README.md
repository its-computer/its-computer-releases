# its.computer — releases

**A real computer for your AI agent.** Isolated, GPU-capable Linux desktops on your Mac, on your real files, driven over MCP. Website: https://its.computer

This repository is the public home for:

- **Releases** — signed, notarized builds of the macOS app (Apple silicon). Download the latest `.dmg` from [Releases](https://github.com/its-computer/its-computer-releases/releases), or install with Homebrew:

  ```bash
  brew install its-computer/tap/computer
  ```

- **Issues** — bug reports and feedback for the early builds.
- **Site** — the source of https://its.computer lives in [`site/`](site/).

The app's source code is in a private repository for now. Guest images are not stored here: the app downloads them on first run, and each release carries a `guest.json` manifest with the image URL, size and checksum.

Status: early access. Requires macOS on Apple silicon.
