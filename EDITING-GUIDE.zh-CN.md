# 中文修改指南

- 分类：图片美术风格
- 界面显示名：极简杂志海报
- 风格：日系 / 韩系极简独立杂志 × 诗性纸感大留白
- Codex 调用名：`$gc-minimal-zine-poster-v0-3`
- 主要用途：把主题句、文章、情绪、物件或照片转成安静的编辑海报。

## 最常改的地方

- 固定视觉规则：修改 `references/style-system.md`。
- Prompt 结构：修改 `references/prompt-compiler.md`。
- 版式、锚点、字体、强调色变化：修改 `references/variation-engine.md`。
- 参考图分析方式：修改 `references/reference-analysis.md`。
- 合格 / 不合格标准：修改 `references/quality-gate.md`。

## 修改原则

保留“大留白、纸张质感、一个主视觉事件、克制文字、单一高彩度强调色”这组家族特征。一次只调整一个维度，并保留原版参数方便回退。

## 验证

```bash
python3 ~/.codex/skills/.system/skill-creator/scripts/quick_validate.py ~/.codex/skills/gc-minimal-zine-poster-v0-3
```

本地修改只影响当前电脑；需要长期保存时，再提交回你的 GitHub Fork。
