# glfetcher — releases

Prebuilt binaries for **glfetcher**, a CLI that mirrors GitLab groups into
local directories by cloning missing repositories and optionally
fast-forwarding clean checkouts.

**Configuration schemas: [agrechin.github.io/glfetcher](https://agrechin.github.io/glfetcher/)**

This repository hosts release artifacts only; the source code lives in a
private repository.

## Install

**Homebrew (macOS):**

```sh
brew install --cask agrechin/tap/glfetcher
```

**Prebuilt binaries (macOS, Linux, Windows):** download the archive for your
platform from the
[latest release](https://github.com/agrechin/glfetcher-releases/releases/latest),
extract it, and put `glfetcher` on your `PATH`.

Each release includes a `glfetcher_<version>_checksums.txt` with SHA-256 sums
for all archives.

> **Note:** releases are tested only on macOS. The Linux and Windows binaries
> are cross-compiled and published untested — they are expected to work, but
> treat them as best-effort and
> [report anything broken](https://github.com/agrechin/glfetcher-releases/issues).

## License

Binaries are distributed under the [MIT License](LICENSE).
