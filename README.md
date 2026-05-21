# shaowen-ye

生态学研究者，关注 AI 辅助科研工作流、深度调研工具、科研数据处理与文献管理效率工具。我的 GitHub 仓库主要围绕生态学与环境科学研究、Deep Research 工作流、Claude Code / Codex skills、Zotero 插件，以及可复用的科研工具展开。下面按主题方向整理，方便快速了解不同仓库之间的关系。

Ecology researcher working on AI-assisted research workflows, deep-research tooling, scientific data workflows, and reference-management utilities. My repositories mainly focus on ecology and environmental research, Deep Research workflows, Claude Code / Codex skills, Zotero plugins, and reusable tools for research work. The list below is organized by theme and purpose.

## 近期重点 / Current Focus

- **Deep Research 工作流**：构建从 DR 提示词设计、联网调研、报告归档、引用抽取与规范化到视觉提示词规划的工具链。
- **Claude Code / Codex skills**：把高频科研任务沉淀成可复用 skill，例如稿件审阅、图表数据提取、项目知识沉淀、DR prompt builder、DR bibliography builder 和图像提示词构建。
- **Zotero 文献库效率工具**：围绕导入去重、重复条目合并、文件夹结构管理、位置查看和阅读布局优化，开发一组保守、安全、可撤回的 Zotero 插件。

- **Deep Research workflows**: building a toolchain from DR prompt design and web research to report archiving, citation extraction and normalization, and visual prompt planning.
- **Claude Code / Codex skills**: turning recurring research tasks into reusable skills, including manuscript review, figure data extraction, project knowledge capture, DR prompt building, DR bibliography extraction, and image-prompt construction.
- **Zotero productivity tools**: developing conservative, reversible Zotero plugins for import deduplication, duplicate merging, collection management, location lookup, and reading-layout optimization.

## 仓库地图 / Repository Map

### AI 辅助科研与 Codex/Claude Code 工具 / AI-Assisted Research and Coding Tools

这一组仓库把 AI 工具用于科研阅读、图表数据提取、稿件审阅、编码工作流和多 provider 联网研究。

- [manuscript-review-skill](https://github.com/shaowen-ye/manuscript-review-skill)
  Claude Code 技能：模拟多位专家进行学术稿件审阅，生成中英双语彩色批注文档、评分矩阵和修改优先级。

- [FigDataX](https://github.com/shaowen-ye/FigDataX)
  Claude Code 技能：从论文图表中提取数值数据，支持柱状图、折线图、散点图、箱线图、热力图等常见科学图表。

- [smart-model](https://github.com/shaowen-ye/smart-model)
  Claude Code 智能模型选择工具，根据任务复杂度推荐更合适的模型档位。

- [project-knowledge-pipeline](https://github.com/shaowen-ye/project-knowledge-pipeline)
  Claude Code 项目知识沉淀 skill，用 `DECISIONS.md` 记录关键决策，并提供可选的会话绑定方案，支持长期项目的迁移、归档与跨机器延续。

- [deep-research-assistant](https://github.com/shaowen-ye/deep-research-assistant)
  深度研究助手 / Deep Research Assistant：多模型深度研究的本地 Python Web GUI，Gemini Deep Research / Anthropic Claude / OpenAI / DeepSeek / OpenRouter 共用面板，支持协作规划、执行多步联网研究、生成附引文报告（Markdown + PDF + ZIP）；内置自然语言报告编辑器（多轮 find/replace + 版本回滚）与一键引用规范化。

- [deep-research-prompt-builder](https://github.com/shaowen-ye/deep-research-prompt-builder)
  Claude Code Skill：为 ChatGPT Deep Research、Gemini Deep Research 等深度调研代理构建**自包含**提示词集。支持科研、政策、行业三大领域模板，并在 v1.1.0 起可选生成候选图像 brief 与多系列视觉提示词附录，帮助 DR 系列报告衔接后续插图规划。

- [dr-report-to-bibliography](https://github.com/shaowen-ye/dr-report-to-bibliography)
  Claude Code Skill：从 ChatGPT Deep Research、Gemini Deep Research 等报告或研究文档中提取参考文献，生成 RIS 导入文件、CSV 审阅表和问题清单；支持 CrossRef / 网页元数据补全、中文编码保护、中文机构作者规范处理和可选 Zotero 本地 API dry-run 推送。

- [image-prompt-builder](https://github.com/shaowen-ye/image-prompt-builder)
  Claude Code Skill：为 ChatGPT / OpenAI Images、Gemini / Nano Banana 等图像生成工具构建可复制提示词。支持科学插图、信息图、概念视觉、流程图和多系列 Markdown 图像提示词集，并对真实数据图、真实地图、真实网络拓扑和精确数值图进行红线重定向。

### 生态研究速览 / Ecology and Conservation Digests

这一组仓库用于持续整理生态学、环境科学和保护生物学领域的新论文与动态。

- [eco-research-digest](https://github.com/shaowen-ye/eco-research-digest)
  生态与环境研究前沿速览，按主题整理近期论文、摘要概括和解读点评。

- [eco-conservation-digest](https://github.com/shaowen-ye/eco-conservation-digest)
  生态保护动态速览，面向保护生物学和环境管理相关信息整理。

### Zotero 插件开发 / Zotero Plugin Development

Zotero 插件用于提升大规模文献库中的导入去重、重复条目处理、文件夹管理、文件夹辨识和条目列表阅读效率。

#### 收件箱与标签整理

- [Zotero Inbox & Tag Triage Manager Plugin](https://github.com/shaowen-ye/zotero-inbox-tag-triage-manager-plugin)
  用 Inbox 工作流整理暂时无法分类或位置不合理的文献，并支持状态标签管理、目标文件夹分配和可疑标签确认式清理。

#### 文献导入与重复处理

- [Zotero DOI Dedup Import Plugin](https://github.com/shaowen-ye/zotero-doi-dedup-import-plugin)
  导入文献时按 DOI 去重，复用已有条目，并可标识复用结果。

- [Zotero Duplicate Merge Manager Plugin](https://github.com/shaowen-ye/zotero-duplicate-merge-manager-plugin)
  查找可能重复的顶层文献条目，支持标题相同或高度相似的候选识别、结果滚动阅读、红色标识、确认式合并和移入回收站。

#### 文件夹与结构管理

- [Zotero Collection Structure Manager Plugin](https://github.com/shaowen-ye/zotero-collection-structure-manager-plugin)
  用独立管理器查看、搜索、展开/折叠、选择、移动、合并和导出 Zotero 文件夹结构。

- [Zotero Collection Location Menu Plugin](https://github.com/shaowen-ye/zotero-collection-location-menu-plugin)
  在条目右键菜单中查看条目所在的所有文件夹位置，并支持跳转、移除指定位置、只保留指定位置和批量管理。

- [Zotero Collection Quick Jumper Plugin](https://github.com/shaowen-ye/zotero-collection-quick-jumper-plugin)
  快速搜索并跳转文件夹。该插件已归档，主要功能已整合到 Collection Structure Manager。

#### 视觉辨识与阅读效率

- [Zotero Collection Color Menu Plugin](https://github.com/shaowen-ye/zotero-collection-color-menu-plugin)
  为 Zotero 文件夹添加本地背景颜色，方便在大型层级结构中快速辨识重点文件夹。

- [Zotero Item Column Layout Optimizer Plugin](https://github.com/shaowen-ye/zotero-item-column-layout-plugin)
  优化 Zotero 条目列表列宽，提供标题优先、最大化标题列、紧凑标题和均衡信息布局。

## Notes

- Zotero 插件尽量采用保守实现：优先只读或确认式修改，不直接删除文献数据；需要修改 Zotero 数据时，默认采用可撤回或低风险操作，例如移入回收站、恢复布局、保存原始状态等。
- 对没有完整 README 或描述的仓库，这里采用保守摘要；更详细的说明以后可以逐步补到各仓库自己的 README 中。
