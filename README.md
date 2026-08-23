# LK Vector

[中文](#中文) | [English](#english)

LK Vector 是一款面向分子生物学和基因工程工作的桌面 DNA 序列编辑器。本仓库仅用于发布可安装版本，不包含应用源代码。

LK Vector is a desktop DNA sequence editor for molecular biology and genetic engineering workflows. This repository distributes installable builds only and does not contain the application source code.

## 中文

### 软件简介

LK Vector 用于查看、编辑和分析 DNA、质粒及其他核酸序列。它将环形质粒图、线性图和碱基序列视图整合在同一工作区中，适合质粒设计、载体检查、Feature 标注和序列比对等日常工作。

### 主要功能

- 环形质粒图、线性图和碱基序列视图
- DNA 序列创建、编辑、导入、导出和保存
- Feature、引物、开放阅读框及酶切位点查看与管理
- 内置 1,363 条标准 Feature 数据及完整 DNA 序列
- 标准 Feature 搜索、详情查看和序列插入
- 基于完整序列匹配的自动注释
- 基于 NCBI BLAST+ 的模糊同源自动注释
- 一致性、覆盖度、E-value 和最大命中数筛选
- 正向链、反向互补链及环状序列跨原点匹配
- 中文和英文界面切换
- 本地运行 BLAST，查询序列无需上传到在线服务

### 下载与安装

目前 Beta 版本仅提供 **Windows x64** 安装包。

1. 打开 [Releases](https://github.com/new-agent-lk/lk-vector-releases/releases) 页面。
2. 下载最新版本的 `LK-Vector-*-x64.exe`。
3. 运行安装程序并按照提示完成安装。

Linux 和 macOS 版本正在评估中，发布时间待定。

### 系统要求

- Windows 10 或 Windows 11
- 64 位 x86 处理器
- 建议至少 4 GB 内存
- BLAST 搜索速度取决于序列长度和处理器性能

### Beta 说明

当前版本属于公开测试版，适合功能体验和一般序列分析。重要实验数据请保留原始文件和独立备份，并在用于实验决策前人工复核自动注释结果。

### 文件校验

每个 Release 同时提供 SHA-256 校验文件。可在 PowerShell 中验证安装包：

```powershell
Get-FileHash .\LK-Vector-0.1.0-beta.1-x64.exe -Algorithm SHA256
```

将输出值与 Release 中的 `SHA256SUMS-*.txt` 对比。

### 源代码说明

LK Vector 当前以闭源方式发布。本仓库仅包含 README 和编译后的发行附件，不提供应用源代码。

## English

### About

LK Vector is a desktop application for viewing, editing, and analyzing DNA, plasmid, and other nucleotide sequences. Circular plasmid maps, linear maps, and base-level sequence views are combined in one workspace for plasmid design, vector inspection, feature annotation, and sequence comparison.

### Key Features

- Circular plasmid, linear, and base-level sequence views
- Create, edit, import, export, and save DNA sequences
- View and manage features, primers, open reading frames, and restriction sites
- Built-in library of 1,363 standard features with complete DNA sequences
- Search standard features, inspect metadata, and insert sequences
- Exact-match automatic feature annotation
- Fuzzy homology annotation powered by NCBI BLAST+
- Identity, coverage, E-value, and maximum-hit filters
- Forward strand, reverse-complement, and circular origin-spanning matches
- Chinese and English user interfaces
- Local BLAST execution without uploading query sequences to an online service

### Download and Installation

The current Beta is available for **Windows x64 only**.

1. Open the [Releases](https://github.com/new-agent-lk/lk-vector-releases/releases) page.
2. Download the latest `LK-Vector-*-x64.exe` installer.
3. Run the installer and follow the setup prompts.

Linux and macOS builds are under evaluation and do not have release dates yet.

### System Requirements

- Windows 10 or Windows 11
- 64-bit x86 processor
- At least 4 GB RAM recommended
- BLAST performance depends on sequence length and processor performance

### Beta Notice

This is a public Beta intended for evaluation and general sequence-analysis work. Keep original files and independent backups of important experimental data. Automatically generated annotations should be reviewed before they are used for experimental decisions.

### Verify a Download

Each Release includes a SHA-256 checksum file. Verify the installer in PowerShell with:

```powershell
Get-FileHash .\LK-Vector-0.1.0-beta.1-x64.exe -Algorithm SHA256
```

Compare the result with the corresponding `SHA256SUMS-*.txt` file from the Release.

### Source Code

LK Vector is currently distributed as proprietary software. This repository contains only this README and compiled release assets; application source code is not published here.

## Releases

[Download the latest LK Vector release](https://github.com/new-agent-lk/lk-vector-releases/releases/latest)
