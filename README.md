# carvel-kapp

[中文版本](./README.cn.md)

kapp is a simple deployment tool focused on the concept of "Kubernetes application" — a set of resources with the same label

![carvel-kapp](https://repo.x-cmd.io/carvel-kapp.svg)

## Install

```sh
x install carvel-kapp
```

## Code insight

Total: **1,152,677** lines of code across **4273** files in the top 5 languages.

| Language | Code | Comments | Blanks | Files |
|----------|-----:|---------:|-------:|------:|
| Go | 1,006,204 | 215,551 | 108,835 | 4111 |
| Yaml | 127,038 | 1,967 | 589 | 42 |
| Protobuf | 8,803 | 22,790 | 4,981 | 70 |
| AssemblyGAS | 6,870 | 371 | 1,789 | 48 |
| Json | 1,760 | 0 | 0 | 2 |

## OpenSSF Scorecard

Overall score: **6.3 / 10**

Lowest-scoring checks:

- **Token-Permissions** (0/10) — detected GitHub workflow tokens with excessive permissions
- **CII-Best-Practices** (0/10) — no effort to earn an OpenSSF best practices badge detected
- **Fuzzing** (0/10) — project is not fuzzed

## Source

- **Upstream**: <https://github.com/vmware-tanzu/carvel-kapp>
- **Homepage**: <https://carvel.dev/kapp>
- **License**: Apache-2.0

## Release

- **Latest**: `v0.65.4` (2026-08-25)
- **Last commit**: 2026-08-17
- **Assets in release**: 8

## Popularity

- **Stars**: 1,082 · **Forks**: 134 · **Open issues**: 379 · **Contributors**: 81

## Totals (cumulative)

- **Releases**: 111 · **Merged PRs**: 451 · **Open PRs**: 19 · **Closed issues**: 269 · **Open issues**: 110 · **Commits**: 1066

## Recent activity

| Window | Since | Releases | Merged PRs | Open PRs | Closed issues | Open issues | Commits |
|---|---|---:|---:|---:|---:|---:|---:|
| 30d | 2026-08-13 | 1 | 0 | 0 | 0 | 0 | 0 |
| last60d | 2026-07-14 | 1 | 0 | 0 | 0 | 0 | 0 |
| 90d | 2026-06-14 | 1 | 0 | 0 | 0 | 0 | 0 |
| last180d | 2026-03-16 | 3 | 0 | 0 | 0 | 0 | 0 |
| 360d | 2025-09-17 | 5 | 0 | 0 | 0 | 0 | 0 |
| last720d | 2024-09-22 | 8 | 0 | 0 | 0 | 0 | 0 |

## Release assets

| Asset | Size | Target |
|-------|-----:|--------|
| [checksums.txt](https://github.com/vmware-tanzu/carvel-kapp/releases/download/v0.65.4/checksums.txt) | 423 B | `other` |
| [checksums.txt.pem](https://github.com/vmware-tanzu/carvel-kapp/releases/download/v0.65.4/checksums.txt.pem) | 3.2 KiB | `other` |
| [checksums.txt.sig](https://github.com/vmware-tanzu/carvel-kapp/releases/download/v0.65.4/checksums.txt.sig) | 92 B | `other` |
| [kapp-darwin-amd64](https://github.com/vmware-tanzu/carvel-kapp/releases/download/v0.65.4/kapp-darwin-amd64) | 77.0 MiB | `native/darwin/x64` |
| [kapp-darwin-arm64](https://github.com/vmware-tanzu/carvel-kapp/releases/download/v0.65.4/kapp-darwin-arm64) | 73.3 MiB | `native/darwin/arm64` |
| [kapp-linux-amd64](https://github.com/vmware-tanzu/carvel-kapp/releases/download/v0.65.4/kapp-linux-amd64) | 74.6 MiB | `native/linux/x64` |
| [kapp-linux-arm64](https://github.com/vmware-tanzu/carvel-kapp/releases/download/v0.65.4/kapp-linux-arm64) | 70.3 MiB | `native/linux/arm64` |
| [kapp-windows-amd64.exe](https://github.com/vmware-tanzu/carvel-kapp/releases/download/v0.65.4/kapp-windows-amd64.exe) | 75.4 MiB | `native/win/x64` |

## Improve this data

Install metadata for carvel-kapp lives in the [x-cmd/install](https://github.com/x-cmd/install) index — a curated YAML package list that x-cmd consumes at install time. If `carvel-kapp` is missing, out of date, or installs incorrectly, please open an issue or PR there:

- **Open an issue**: <https://github.com/x-cmd/install/issues/new>
- **Edit the package entry**: <https://github.com/x-cmd/install/edit/main/carvel-kapp.yml> (or whichever path the index uses)

The data on this page (card / loc / scorecard / release) is auto-collected by [x-cmd-install-action](https://github.com/x-cmd-install/x-cmd-install-action) and is regenerated daily. Improvements to *install behaviour* (which version gets installed, platform-specific quirks, dependencies) belong upstream in the index.

_Snapshot: `data/card/260912.yml` · 2026-09-12T04:53:00Z._
