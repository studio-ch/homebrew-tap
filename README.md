# studio-ch/homebrew-tap

Homebrew formulae for Cloud Console tools.

```bash
brew install studio-ch/tap/cloudconsole
```

`brew tap studio-ch/tap` resolves to this repository — Homebrew expands
the short form to `github.com/<user>/homebrew-<repo>`, which is why the
name carries the `homebrew-` prefix.

## Casks

| Cask | Description |
|---|---|
| `cloudconsole` | Command-line interface for the Cloud Console — see [studio-ch/cloudconsole-cli](https://github.com/studio-ch/cloudconsole-cli) |

Casks rather than formulae: Homebrew reserves formulae for software it
builds from source, and uses casks for pre-built binaries — which is what
these are.

## About this repository

Everything under `Casks/` is **generated**. GoReleaser writes and commits
each cask as part of a release, so a cask here always matches a published
artifact and its checksum.

Do not edit casks by hand: the next release overwrites them. Report
problems against the tool's own repository instead.
