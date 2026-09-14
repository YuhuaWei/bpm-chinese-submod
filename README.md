# BPM 中文汉化 (Better Politics Mod - Simplified Chinese)

[Better Politics Mod (BPM)](https://steamcommunity.com/sharedfiles/filedetails/?id=2932134122) 的简体中文汉化 submod。

## 简介

这是 BPM 的**纯汉化子模组**（submod），不包含 BPM 本体内容，需要配合 BPM 本体一起使用。

- 覆盖 BPM 全部 97 个本地化文件（约 8500+ key）的简体中文译文
- 修复 BPM 的 GUI 硬编码英文（`raw_text`），改为标准的 `text = "key"` 本地化引用
- 对英文玩家无副作用：GUI 修复采用 key 引用方式，英文原文保留在英文侧

## 安装

1. 订阅 [Better Politics Mod](https://steamcommunity.com/sharedfiles/filedetails/?id=2932134122) 本体
2. 订阅本汉化 mod
3. 在启动器中，把本汉化 mod 排在 BPM 本体**之后**（load order）
4. 游戏语言设为简体中文

## 目录结构

```
bpm-chinese-submod/
├── localization/
│   ├── simp_chinese/    # 中文翻译（覆盖 BPM 本体中文）
│   └── english/         # GUI key 的英文值（fallback）
├── gui/                 # GUI 硬编码修复（6 个文件）
├── .metadata/
│   └── metadata.json    # mod 元数据 + 依赖声明
└── bpm-chinese-submod.mod  # descriptor（部署到 mod 目录根）
```

## 维护说明

- 本 mod 基于 BPM 2.5.43（Steam 发行版）制作
- 翻译由国人玩家主导维护
- 上游 BPM 不接受翻译合并，故以 submod 形式发布

## 许可证

翻译内容仅作学习交流用途，BPM 本体版权归其作者所有。
