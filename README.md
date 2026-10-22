#课程编织者

`course-weaver` 是一个面向大学生的课程资料智能整合与学习笔记生成 Skill。

它可以整合 PPT、PDF、教材、课堂记录、习题、实验指导书以及其他课程资料，生成结构清晰、内容完整、便于理解和复习的课程笔记。

## 主要功能

- 盘点并分析多种课程资料
- 建立带来源定位的课程知识点清单
- 按知识依赖关系组织章节
-生成完整的 Markdown 课程笔记
- 整理重要公式、定理、符号、条件和推导
- 生成“基础理解 → 标准应用 → 综合提高 → 拓展挑战”的阶梯式例题
- 总结易错点、知识辨析和适用边界
- 识别并记录具有教学价值的原始图片、表格和流程图
- 区分原始资料、归纳总结和智能体补充内容
- 对无法读取、无法确认或存在冲突的内容进行明确标记
- 根据新增资料增量更新已有课程笔记
- 根据原始知识点清单执行完整性检查

## 目录结构

```文本
course-weaver/
├── SKILL.md
├── agents/
│   └── openai.yaml
├── references/
│   ├── workflow.md
│   ├── note-format.md
│   └── quality-rules.md
├── templates/
│   ├── notes-template.md
│   └── exercise-template.md
├── checklists/
│   └── completeness-check.md
└── examples/
    └── example-output.md
