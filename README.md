# hub.zhangqi.net

张琦的个人站点,部署在 GitHub Pages。

## 技术栈

- 静态站点:[Hugo](https://gohugo.io/) extended
- 主题:[PaperMod](https://github.com/adityatelange/hugo-PaperMod)
- 部署:GitHub Pages,自定义域名 `hub.zhangqi.net`

## 本地开发

```bash
hugo server -D     # -D 含草稿
```

访问 http://localhost:1313/

## 构建

```bash
hugo --minify      # 输出到 public/
```

## 目录结构

```
.
├── content/             # Markdown 文章
│   ├── about.md        # 关于页
│   └── posts/          # 博客文章
├── themes/PaperMod/    # 主题源码(vendored)
├── static/             # 静态资源
├── hugo.toml           # Hugo 配置
└── CNAME               # 自定义域名(部署必需)
```

## 备份分支

2022 年的旧 Hexo 版本已备份至 `hexo-backup-20260618-184843` 分支。
