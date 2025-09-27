# MkDocs Community Discussion 模板

访问 https://github.com/mkdocs/mkdocs/discussions/new 选择 "Show and tell" 类别，然后复制以下内容：

---

**标题**: 🎉 New Plugin: mkdocs-excel-plugin - Render Excel files as beautiful HTML tables

**内容**:

Hi MkDocs community! 👋

I'm excited to share a new plugin I've developed: **mkdocs-excel-plugin**

## 🚀 What it does

This plugin allows you to render Excel files directly in your MkDocs documentation as beautiful HTML tables with complete style preservation.

## ✨ Key Features

- 🎨 **Complete Style Preservation**: Maintains Excel's background colors, fonts, borders, and alignment
- 📊 **Merged Cell Support**: Perfect handling of colspan and rowspan
- 🔄 **Multi-sheet Processing**: Render single sheets or all sheets at once
- ⚡ **Smart Caching**: Built-in caching for improved performance
- 🎯 **Size Control**: Configurable row/column limits for large files
- 🌓 **Theme Compatibility**: Works seamlessly with Material and other MkDocs themes

## 📦 Installation & Usage

```bash
pip install mkdocs-excel-plugin
```

```yaml
# mkdocs.yml
plugins:
  - excel
```

```markdown
# In your markdown files
{{ render_excel_sheet('data.xlsx', 'Sheet1') }}
{{ render_excel_all_sheets('report.xlsx') }}
{{ list_excel_sheets('workbook.xlsx') }}
```

## 🔗 Links

- **PyPI**: https://pypi.org/project/mkdocs-excel-plugin/
- **GitHub**: https://github.com/Wangjunyu/mkdocs-excel-plugin
- **Documentation**: Complete usage examples in README

## 🎯 Use Cases

Perfect for:
- Financial reports and dashboards
- Data analysis documentation
- Business intelligence docs
- Any documentation that needs to display Excel data

Would love to hear your feedback and see how you use it! 🙌

---