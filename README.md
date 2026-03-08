# Fabre

使用 Rust 编写的 Ragnarok Online 游戏服务器。

> 项目处于早期开发阶段，API 和配置格式可能随版本变化。

## 特性

- **单文件部署** — 解压即用，无需安装运行时
- **SQLite / MySQL 双数据库支持** — 小型服务器零依赖启动，大规模部署可切换 MySQL
- **兼容 rAthena 数据文件** — 可直接加载 rAthena 格式的游戏数据
- **多语言界面** — 内置中文和英文，可扩展

## 支持平台

| 平台 | 架构 |
|------|------|
| Windows | x64 |
| macOS | ARM64 (Apple Silicon) |

## 快速开始

1. 从 [Releases](https://github.com/MidgardLabs/Fabre/releases) 下载对应平台的压缩包
2. 解压到任意目录
3. 按需修改 `config.toml` 配置
4. 运行 `fabre`（Windows 下为 `fabre.exe`）

```
fabre-v0.1.0-windows-x64/
├── fabre.exe          # 服务器主程序
├── config.toml        # 服务器配置
├── locales/           # 多语言文件
└── db/                # 游戏数据文件
```

## 更新日志

查看 [CHANGELOG.md](./CHANGELOG.md)。

## 许可证

本项目为闭源软件，仅通过 Release 提供编译后的二进制文件。
