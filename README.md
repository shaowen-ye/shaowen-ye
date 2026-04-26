# shaowen-ye

## Zotero 插件开发 / Zotero Plugin Development

这里整理我为 Zotero 文献管理工作流开发和维护的插件。目标是提升大规模文献库中的导入去重、重复条目处理、文件夹管理、文件夹辨识和条目列表阅读效率。

### 文献导入与重复处理

- [Zotero DOI Dedup Import Plugin](https://github.com/shaowen-ye/zotero-doi-dedup-import-plugin)  
  导入文献时按 DOI 去重，复用已有条目，并可标识复用结果。

- [Zotero Duplicate Merge Manager Plugin](https://github.com/shaowen-ye/zotero-duplicate-merge-manager-plugin)  
  查找可能重复的顶层文献条目，支持标题相同或高度相似的候选识别、结果滚动阅读、红色标识、确认式合并和移入回收站。

### 文件夹与结构管理

- [Zotero Collection Structure Manager Plugin](https://github.com/shaowen-ye/zotero-collection-structure-manager-plugin)  
  用独立管理器查看、搜索、展开/折叠、选择、移动、合并和导出 Zotero 文件夹结构。

- [Zotero Collection Location Menu Plugin](https://github.com/shaowen-ye/zotero-collection-location-menu-plugin)  
  在条目右键菜单中查看条目所在的所有文件夹位置，并支持跳转、移除指定位置、只保留指定位置和批量管理。

- [Zotero Collection Quick Jumper Plugin](https://github.com/shaowen-ye/zotero-collection-quick-jumper-plugin)  
  快速搜索并跳转文件夹。该插件已归档，主要功能已整合到 Collection Structure Manager。

### 视觉辨识与阅读效率

- [Zotero Collection Color Menu Plugin](https://github.com/shaowen-ye/zotero-collection-color-menu-plugin)  
  为 Zotero 文件夹添加本地背景颜色，方便在大型层级结构中快速辨识重点文件夹。

- [Zotero Item Column Layout Optimizer Plugin](https://github.com/shaowen-ye/zotero-item-column-layout-plugin)  
  优化 Zotero 条目列表列宽，提供标题优先、最大化标题列、紧凑标题和均衡信息布局。

## Development Notes

这些插件主要面向 Zotero 7、8、9，尽量采用保守实现：优先只读或确认式修改，不直接删除文献数据；需要修改 Zotero 数据时，默认采用可撤回或低风险操作，例如移入回收站、恢复布局、保存原始状态等。
