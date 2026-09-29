# product-intro-html

将产品介绍文件、产品图片及其他资料整理成重点突出、视觉高级的 HTML 产品介绍。

## 功能概述

这个 Codex Skill 的核心流程是：

**读取资料 → 生成 5 页大纲 → 用户确认 → 补全图片 → 生成 3 个封面方案 → 用户确认风格 → 生成完整 HTML → 检查最终渲染结果**

适合用于把产品 PDF、产品图片、产品参数、产品视频、品牌资料等内容整理成适合展示和讲解的 HTML 产品介绍。

## 安装方式

把整个 `product-intro-html` 文件夹复制到本地 Codex skills 目录：

```bash
cp -R product-intro-html ~/.codex/skills/
```

安装后目录结构应为：

```text
~/.codex/skills/product-intro-html/SKILL.md
```

## 使用方式

在 Codex 中直接说：

```text
用 product-intro-html 做这个产品介绍
```

或显式引用 skill：

```text
用 $product-intro-html 做这个产品介绍
```

## 文件结构

```text
product-intro-html/
├── README.md
└── SKILL.md
```
