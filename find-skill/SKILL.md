---
name: find-skill
description: 根据需求在本技能库中快速定位合适的技能（skill）。当用户说"找一个能做 XX 的技能"、"有没有处理 XX 的 skill"、"我该用哪个技能"时使用。
---

# Find Skill - 技能查找器

帮助用户在技能库中找到完成当前任务所需的技能。

## 查找步骤

1. **理解需求**：从用户描述中提取关键词（平台、动作、产物类型）。
2. **查索引**：读取本仓库 `README.md` 中的「技能总索引」表格，按「触发场景」列匹配。
3. **给方案**：向用户返回——技能名、安装/加载方式、一句话用法示例。
4. **没有匹配时**：告知未找到，并建议：
   - 到 SkillHub / 技能市场搜索
   - 用 skill-creator 流程自己创建一个
   - 把需求记录到本仓库 `TODO.md`，留待补充

## 技能分类速查

| 需求类型 | 关键词 | 对应技能 |
|---------|--------|---------|
| 代码托管 | GitHub、clone、push、PR | github-connector |
| 设计稿 | Figma、设计还原 | figma-connector |
| 内部代码平台 | 工蜂、git.woa.com | gongfeng-connector |
| 桌面自动化 | 截图、点击、GUI | computer-use / cloud-computer |
| 文档创作 | Word、docx、研报 | workbuddy-docx / workbuddy-office-routing |
| 演示文稿 | PPT、pptx、幻灯片 | workbuddy-pptx |
| 表格处理 | Excel、xlsx、csv、对账 | workbuddy-sheetagent / xlsx |
| 在线发布 | 网站、应用、上线 | sites / library |
| 定时任务 | 定时、自动化、周期 | automation-task-manager |
| 办公文件编辑 | 本地 doc/xls/ppt 编辑 | workbuddy-local-office-edit |
| 资料管理 | 知识库、网盘、资料库 | library / baidu-netdisk |

## 维护约定

- 每新增一个技能，在 `README.md` 索引表和本文件的分类速查表中各加一行
- 技能详情快照存放在 `snapshots/` 目录（如有）
