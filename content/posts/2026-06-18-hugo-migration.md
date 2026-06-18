---
title: "站点上线:老张硅语 (Hexo → Hugo)"
date: 2026-06-18T00:00:00+08:00
draft: false
tags: ["meta", "changelog"]
summary: "2026-06-18 老张硅语(hub.zhangqi.net)从 Hexo 5.4 迁移至 Hugo + PaperMod,完成长期维护性升级。"
---

## 背景

本博客(hub.zhangqi.net)上次实质内容更新是 2022 年。Hexo 5.4 + Next 主题长期未升级,Dependabot 累积了 7 个未合并的 PR,包含 19 个已知漏洞(7 high / 9 moderate / 3 low)。

## 站名:老张硅语

"硅语"取"硅上之语、芯片之言"之意,记录老张与 AI 助手协作留下的痕迹。保留原域名 `hub.zhangqi.net`,CNAME 不变。

## 升级目标

1. 摆脱 npm 生态,改为单二进制部署
2. 主题与构建系统解耦,4 年内不需要再升级
3. 保留自定义域名 `hub.zhangqi.net`
4. 保留旧 Hexo 源码(已备份至 `hexo-backup-20260618-184843` 分支)

## 新技术栈

- **Hugo v0.144.2 (extended)**:Go 写的静态站点生成器,构建时间毫秒级
- **PaperMod v8.0**:Hugo 生态主流主题,简洁,自带 RSS/搜索/暗色模式
- **GitHub Pages**:直接从 `master` 分支部署

## 未来计划

- 启用 GitHub Actions 自动部署(可选)
- 启用 HTTPS 强制(可选)
- 逐步把老 Hexo 文章迁移过来(可选,原内容已 4 年未更新,可忽略)

## 旧版本

如需查看 2022 年的旧版,访问 [hexo-backup-20260618-184843](https://github.com/zhangqi-net/zhangqi1000.github.io/tree/hexo-backup-20260618-184843) 分支。
