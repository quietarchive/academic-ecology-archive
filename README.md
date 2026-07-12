# academic-ecology-archive

学术生态观察与公开资料档案。An archive of public discussions and materials on academic culture and higher education.

## 上线流程

1. 在网站填写表单，提交 GitHub Issue
2. 审核通过后，给 Issue 打上 `approved` 标签
3. GitHub Actions 会把条目写入 `data/entries.json` 并推送；GitHub Pages 随后自动更新

首次使用前，请在仓库 **Issues → Labels** 中新建标签 `approved`。

存档优先使用 [互联网档案馆 Wayback Machine](https://web.archive.org/)；微信文章常被拦截，请改用 [archive.ph](https://archive.ph/)。

## 相关讨论截图

1. 把截图放进 `media/issue-<编号>/`
2. 在 `data/entries.json` 对应条目里加 `discussion` 数组，例如：

```json
"discussion": [
  "media/issue-4/01.png",
  "media/issue-4/02.png"
]
```

主页会显示「相关讨论」按钮，点击可查看截图。
