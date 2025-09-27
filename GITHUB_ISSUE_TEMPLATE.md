# GitHub Issue 模板

复制以下内容，然后访问 https://github.com/mkdocs/mkdocs/issues/new 创建新 Issue：

---

**标题**: Add mkdocs-excel-plugin to official plugins list

**内容**:

## Plugin Submission Request

Hello MkDocs team! 👋

I would like to add my plugin to the official MkDocs plugins list.

### Plugin Information

**Plugin Name**: mkdocs-excel-plugin
**Category**: Images, Tables, Charts & Graphs
**PyPI**: https://pypi.org/project/mkdocs-excel-plugin/
**GitHub**: https://github.com/Wangjunyu/mkdocs-excel-plugin
**Author**: Wangjunyu

### Description

A MkDocs plugin that renders Excel files as beautiful HTML tables with complete style preservation including colors, fonts, borders, and merged cells. The plugin supports:

- 🎨 Complete style preservation (background colors, fonts, borders, alignment)
- 📊 Merged cell support with proper colspan/rowspan
- 🔄 Multi-sheet processing
- ⚡ Smart caching for improved performance
- 🎯 Size control with configurable row/column limits
- 🌓 Theme compatibility (Material and other MkDocs themes)

### Suggested Wiki Entry

```markdown
### [mkdocs-excel-plugin](https://github.com/Wangjunyu/mkdocs-excel-plugin)

[![PyPI version](https://badge.fury.io/py/mkdocs-excel-plugin.svg)](https://badge.fury.io/py/mkdocs-excel-plugin)

A MkDocs plugin that renders Excel files as beautiful HTML tables with complete style preservation including colors, fonts, borders, and merged cells.

*   author: Wangjunyu [Wangjunyu](https://github.com/Wangjunyu)
*   links: [PyPI](https://pypi.org/project/mkdocs-excel-plugin/) | [Github](https://github.com/Wangjunyu/mkdocs-excel-plugin) | [Docs](https://github.com/Wangjunyu/mkdocs-excel-plugin#readme)
*   installation: `pip install mkdocs-excel-plugin`
```

### Usage Example

```yaml
# mkdocs.yml
plugins:
  - excel

# In markdown
{{ render_excel_sheet('data.xlsx', 'Sheet1') }}
{{ render_excel_all_sheets('report.xlsx') }}
```

The plugin is fully tested, documented, and ready for community use. Thank you for considering this addition!

---