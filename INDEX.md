# 想清楚再做 PPT（think-before-slides）：skill 索引

本文件是能力和加载入口。独立 skill 的主入口为 [SKILL.md](SKILL.md)；下列是它的内置模块，不是假定平台另装的独立技能。

| 能力 | 什么时候读 | 入口 |
|---|---|---|
| 使用场景、工具一览 | 用户说“帮助”、问怎么用或某个口令怎么用 | [使用场景](references/help.md) |
| 常见问题 | 用户遇到加载、保存、续接或使用疑问 | [常见问题](references/faq.md) |
| 新手引导、理解模糊表达 | 首次使用、卡住或意图含糊 | [对话引导](references/interaction.md) |
| 理清目标 | 不明确谁向谁、希望得到什么回应 | [准备](references/prepare.md) |
| 盘材料、核对支撑 | 需要判断材料能说明什么 | [素材](references/materials.md) |
| 安排讲述路线 | 顺序混乱或需要比较路线 | [叙事](references/narrative.md)；需要选方法时读 [方法库](references/narrative-library.md) |
| 逐页写作、讲稿 | 已有路线或现稿要展开 | [写作](references/writing.md) |
| 评审、改稿 | 检查或修改已有内容 | [评审与改稿](references/review.md) |
| project 内写文档、续接、交接 | 首次写入、恢复或移交 | [文件规则](references/files.md) |
| 用户提供的外部 skill | 查看、挂载、使用或停用外部方法 | [加载规则](references/skills.md) |

## 当前 project 的临时 skill

额外技能登记在当前 project 的 `skills/INDEX.md`，不写回本发行包的索引，也不污染其他议题。第一次需要时用 [空白模板](assets/skills-index.md) 建立；没有额外 skill 就无需建文件。

开始相关模块前，检查该项目索引是否有“启用”且匹配当前用途的项。先看名称、用途、范围和入口，再按需读 SKILL.md；不要一次性加载全部外部技能。登记不等于已读，读过也不等于本轮采用，三者分开记录。

目录总索引仍由 harness 管理。本索引只提供方法入口，不承担 project 导航、后台安装或工具权限管理。
