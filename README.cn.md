# carvel-kapp

[English version](./README.md)

kapp is a simple deployment tool focused on the concept of "Kubernetes application" — a set of resources with the same label

![carvel-kapp](https://repo.x-cmd.io/carvel-kapp.svg?lang=zh)

## 安装

```sh
x install carvel-kapp
```

## 代码洞察

合计: **1,152,677** 行代码（覆盖前 5 种语言、共 **4273** 个文件）。

| 语言 | 代码 | 注释 | 空行 | 文件数 |
|------|-----:|-----:|-----:|------:|
| Go | 1,006,204 | 215,551 | 108,835 | 4111 |
| Yaml | 127,038 | 1,967 | 589 | 42 |
| Protobuf | 8,803 | 22,790 | 4,981 | 70 |
| AssemblyGAS | 6,870 | 371 | 1,789 | 48 |
| Json | 1,760 | 0 | 0 | 2 |

## OpenSSF Scorecard 评分

总评分: **6.3 / 10**

评分最低的几项:

- **Token-Permissions** (0/10) — detected GitHub workflow tokens with excessive permissions
- **CII-Best-Practices** (0/10) — no effort to earn an OpenSSF best practices badge detected
- **Fuzzing** (0/10) — project is not fuzzed

## 源代码

- **上游仓库**: <https://github.com/vmware-tanzu/carvel-kapp>
- **官网**: <https://carvel.dev/kapp>
- **许可证**: Apache-2.0

## 发布

- **最新版本**: `v0.65.4` (2026-08-25)
- **最近提交**: 2026-08-17
- **Release 含资产**: 8 个

## 流行度

- **Star**: 1,082 · **Fork**: 134 · **开放 issue**: 379 · **贡献者**: 81

## 累计统计

- **发布数**: 111 · **已合并 PR**: 451 · **开放 PR**: 19 · **已关闭 issue**: 269 · **开放 issue**: 110 · **提交数**: 1066

## 最近活动

| 时间窗口 | 起始 | 发布 | 已合并 PR | 开放 PR | 已关闭 issue | 开放 issue | 提交 |
|---|---|---:|---:|---:|---:|---:|---:|
| 30d | 2026-08-13 | 1 | 0 | 0 | 0 | 0 | 0 |
| last60d | 2026-07-14 | 1 | 0 | 0 | 0 | 0 | 0 |
| 90d | 2026-06-14 | 1 | 0 | 0 | 0 | 0 | 0 |
| last180d | 2026-03-16 | 3 | 0 | 0 | 0 | 0 | 0 |
| 360d | 2025-09-17 | 5 | 0 | 0 | 0 | 0 | 0 |
| last720d | 2024-09-22 | 8 | 0 | 0 | 0 | 0 | 0 |

## Release 资产

| 资产 | 大小 | 目标平台 |
|------|-----:|----------|
| [checksums.txt](https://github.com/vmware-tanzu/carvel-kapp/releases/download/v0.65.4/checksums.txt) | 423 B | `other` |
| [checksums.txt.pem](https://github.com/vmware-tanzu/carvel-kapp/releases/download/v0.65.4/checksums.txt.pem) | 3.2 KiB | `other` |
| [checksums.txt.sig](https://github.com/vmware-tanzu/carvel-kapp/releases/download/v0.65.4/checksums.txt.sig) | 92 B | `other` |
| [kapp-darwin-amd64](https://github.com/vmware-tanzu/carvel-kapp/releases/download/v0.65.4/kapp-darwin-amd64) | 77.0 MiB | `native/darwin/x64` |
| [kapp-darwin-arm64](https://github.com/vmware-tanzu/carvel-kapp/releases/download/v0.65.4/kapp-darwin-arm64) | 73.3 MiB | `native/darwin/arm64` |
| [kapp-linux-amd64](https://github.com/vmware-tanzu/carvel-kapp/releases/download/v0.65.4/kapp-linux-amd64) | 74.6 MiB | `native/linux/x64` |
| [kapp-linux-arm64](https://github.com/vmware-tanzu/carvel-kapp/releases/download/v0.65.4/kapp-linux-arm64) | 70.3 MiB | `native/linux/arm64` |
| [kapp-windows-amd64.exe](https://github.com/vmware-tanzu/carvel-kapp/releases/download/v0.65.4/kapp-windows-amd64.exe) | 75.4 MiB | `native/win/x64` |

## 改进这些数据

carvel-kapp 的安装元数据由 [x-cmd/install](https://github.com/x-cmd/install) 索引维护——这是一份由 x-cmd 在安装时读取的精选 YAML 包列表。如果 `carvel-kapp` 缺失、过期，或安装行为有问题，欢迎在该 repo 提 issue 或 PR：

- **提交 issue**: <https://github.com/x-cmd/install/issues/new>
- **编辑包条目**: <https://github.com/x-cmd/install/edit/main/carvel-kapp.yml>（或索引实际使用的路径）

本页面的数据（card / loc / scorecard / release）由 [x-cmd-install-action](https://github.com/x-cmd-install/x-cmd-install-action) 自动采集，每日重新生成。**安装行为**（版本选择、平台差异、依赖处理）的改进应提交到上游索引。

_数据快照: `data/card/260912.yml` · 2026-09-12T04:53:01Z._
