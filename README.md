# Bottle Skills

这个目录用于存放 bottle-skills 这一组自定义技能。

## 目录约定

- 每个技能放在一个独立子目录中
- 每个技能子目录至少包含 `SKILL.md`
- 如果技能需要保存默认偏好或本地配置，可在自己的子目录内放配置文件
- 不同技能之间互不共享配置，避免相互影响

## 当前技能

### skill-explanation

路径：`skill-explanation/`

作用：

- 根据技能文档生成说明文档
- 支持本地文件路径、当前打开的技能文档、公开 GitHub 仓库中的技能文档链接
- 首次使用时询问说明文档默认输出目录，并保存为该技能自己的默认配置

主要文件：

- `skill-explanation/SKILL.md`
- `skill-explanation/config.json`

### notes-remaker

路径：`notes-remaker/`

作用：

- 将文本内容或 Markdown 文件整理为结构化笔记
- 运用 MECE 原则和金字塔原理进行深度拆解
- 自动生成包含摘要、逻辑重构、行动指南和标签的规范输出内容

主要文件：

- `notes-remaker/SKILL.md`

## 后续扩展建议

- 新增技能时，继续采用“一技能一目录”的结构
- 如果某个技能需要脚本、模板或参考文档，也放在该技能自己的子目录内
- 如果某个技能有独立配置，优先保存在该技能目录内，不要放到 bottle-skills 根目录
