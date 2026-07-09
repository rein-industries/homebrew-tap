<div align="center">

<a href="https://rein.build">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/rein-industries/rein/main/docs/assets/wordmark-dark.png">
    <img src="https://raw.githubusercontent.com/rein-industries/rein/main/docs/assets/wordmark-light.png" alt="rein" width="220">
  </picture>
</a>

**Control your coding agents from anywhere.**

</div>

Homebrew tap for [rein](https://rein.build), the bridge that connects the Rein
app to the coding agents (Claude Code, Codex, Gemini, opencode, Grok) running
on your machine.

## Install

```sh
brew install rein-industries/tap/rein
rein setup     # always-on service + sign-in + pairing QR
```

## Upgrade

```sh
brew upgrade rein
```

The formula is updated automatically on every release; it installs the same
prebuilt, checksum-verified binary as `curl -fsSL rein.build | sh` and
`npm i -g @rein-industries/rein`.

## Links

- Homepage and app download: <https://rein.build>
- Releases, changelog, and issues: <https://github.com/rein-industries/rein>
