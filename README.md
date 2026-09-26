# sch-optimise

用于通过多轮需求定制、参考项目调研、器件选型审核和双阶段验收，优化 KiCad 或嘉立创 EDA 的原理图、PCB、布线与铺铜。

## 内容

- `SKILL.md`：技能入口与完整工作流
- `references/rules.md`：已确认的原理图、PCB、采购和验收规则
- `references/project-interview.md`：工程定制访谈与审核节点
- `references/research-review.md`：参考项目调研、选型和审核包流程
- `references/delivery-rules.md`：采购、执行与交付规则
- `references/schematic-routing.md`：原理图连线技巧与验收

## 安装

将本仓库目录复制到 Codex 技能目录，并保持目录名为 `sch-optimise`：

```text
~/.codex/skills/sch-optimise/
```

确保 `SKILL.md` 位于该目录根部，并在使用时同时提供 `grill-me`/`grilling` 技能（若环境没有，则按 `references/project-interview.md` 中的等同流程执行）。

## 触发

适用于电路设计、KiCad/嘉立创 EDA 原理图与 PCB 优化、布线铺铜、布局验收、标签/图框修复和紧凑产品布局；也响应 `sch_optimise`。
