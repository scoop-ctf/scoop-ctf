# 🛡️ scoop-ctf

[![GitHub Stars](https://img.shields.io/github/stars/scoop-ctf/scoop-ctf?style=flat-square)](https://github.com/scoop-ctf/scoop-ctf/stargazers) [![GitHub License](https://img.shields.io/github/license/scoop-ctf/scoop-ctf?style=flat-square)](LICENSE) [![Auto Sync](https://img.shields.io/badge/Auto%20Sync-Enabled-blue?style=flat-square&logo=github-actions)](.github/workflows/sync-buckets.yml)

这是一个专门为安全研究人员和 CTF 玩家设计的 Scoop bucket 集合，每日从多个顶级安全仓库自动同步更新。

## 🚀 快速开始

```bash
# 添加 bucket
scoop bucket add scoop-ctf https://github.com/scoop-ctf/scoop-ctf

# 搜索工具 (例如 fscan)
scoop search fscan

# 安装工具
scoop install scoop-ctf/fscan
```

## 📊 统计信息

目前仓库共包含 **434** 个安全工具清单。

### 来源仓库

| 仓库名称 | 来源地址 |
| :--- | :--- |
| **sec** | [tldro/scoop-security](https://github.com/tldro/scoop-security) |
| **ar** | [arch3rPro/PST-Bucket](https://github.com/arch3rPro/PST-Bucket) |
| **ctftools** | [kengwang/scoop-ctftools-bucket](https://github.com/kengwang/scoop-ctftools-bucket) |
| **main** | 🛡️ 本地维护工具 |

## 🛠️ 手动添加软件

如果你想手动添加新的工具清单，请直接将 `.json` 文件放入 `buckets/` 目录并提交 PR。

> [!NOTE]
> 数据最后更新于: `2026-01-31 09:21:51`

