# 论文添加模板

## 如何添加新论文

1. 在 `content/publication/` 下创建新文件夹，如：`my-paper-2024/`
2. 在新文件夹里创建 `index.md` 文件
3. （可选）添加论文图片，命名为 `featured.jpg` 或 `featured.png`
4. 复制下面的模板内容到 `index.md`

## 模板内容

```yaml
---
title: "论文完整标题"
authors:
  - admin          # 如果你是第一作者
  - 作者2
  - 作者3
date: "2024-01-01"  # 发表日期 YYYY-MM-DD
publication_types: ["paper-conference"]  # 会议论文，期刊论文用 ["article-journal"]
publication: "In *会议全称*"
publication_short: "会议简称"  # 如：CVPR, AAAI, NeurIPS 等

abstract: "论文摘要（英文）"

summary: ""

tags:
  - 标签1
  - 标签2

featured: true  # 是否为重点论文（true/false）

# 链接（不需要的可以删除整行）
links:
  - name: PDF
    url: "论文PDF链接"
  - name: Code
    url: "代码仓库链接"
  # 其他可选链接：
  # - name: Dataset
  #   url: "数据集链接"
  # - name: Project
  #   url: "项目主页链接"

# 论文图片（可选，如果不显示图片就设置 preview_only: true）
image:
  caption: ""
  focal_point: ""
  preview_only: true
---
```

## 示例：参考 AAAI2025-ASDN

查看 `content/publication/AAAI2025-ASDN/index.md` 作为真实例子。

