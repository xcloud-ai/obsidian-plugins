# xcloud-ai Obsidian 插件索引

`xcloud-ai` 组织下全部 Obsidian 自研插件的总索引。新插件发版或上架社区目录后，必须在总表补一行并推送。

## 插件总表

| 插件 | 中文名 | 核心功能 | 最新版本 |
|------|--------|----------|----------|
| [table-layout-helper](https://github.com/xcloud-ai/table-layout-helper) | 表格布局助手 | 表头样式（首行/首列/颜色）+ 列宽拖拽自动记忆 + 布局对齐设置（固定列宽/自动列宽、对齐中文化），双视图实时生效，替代手写 CSS | 1.2.4 |
| [xu-homepages](https://github.com/xcloud-ai/xu-homepages) | 启动台 | 多笔记组合启动布局、按星期与时间段路由主页、恢复上次会话 | 1.0.7 |
| [xu-quiet-outline](https://github.com/xcloud-ai/xu-quiet-outline) | 大纲 | 侧边栏大纲树：点击跳转、双向定位、层级滑条、拖拽改层级、双链标题着色、彩虹缩进线与样式定制，基于 quiet-outline 裁剪重构 | 1.1.2 |
| [file-catalog](https://github.com/xcloud-ai/file-catalog) | 文件目录生成器 | 读取指定文件标题生成可点击目录树，代码块动态渲染、命令插入、快捷键定位，设置页 GitHub 操作手册入口 | 1.2.3 |
| [quick-codeblock](https://github.com/xcloud-ai/quick-codeblock) | 代码块快捷插入 | 快捷插入代码块并自动定位光标，选中文本包裹，多语言独立命令，一键跳转系统快捷键设置，默认语言 python/shell/json/yaml | 1.2.6 |
| [xu-number-headings](https://github.com/xcloud-ai/xu-number-headings) | 标题编号 | 标题多级数字编号，层级区间双滑条，frontmatter 按文档覆盖与 off 豁免，编辑 / 打开 / 外部修改（大纲拖拽联动）后自动重编号，单事务提交不污染撤销栈 | 1.1.2 |
| [xu-config-transfer](https://github.com/xcloud-ai/xu-config-transfer) | 配置搬运工 | 多库配置迁移：勾选导出导入全局设置+插件数据，逐项详情预览、冲突标注（新增/覆盖/内容相同）、键级 diff 报告、覆盖自动备份一键还原 | 1.0.1 |

## 维护约定

- 一插件一独立仓库，仓库 topic 打 `obsidian-plugin`
- 发版/上架后在总表追加或更新对应行（版本号以 manifest.json 为准）
- 每个插件的完整需求/架构/里程碑记录在 Obsidian vault 的插件详情笔记中
