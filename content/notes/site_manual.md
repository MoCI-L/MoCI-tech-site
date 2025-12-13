---
title: "MoCI Tech Site 使用手册"
draft: false
---

## 站点定位

MoCI Tech Site 是一个个人技术知识库，用于：
- 学习记录
- 知识整理
- 技术复盘
- 资料长期存放

优先级顺序是：
**可用性 > 可维护性 > 美观 > 访问量**

---

## 日常使用流程


### 本地写作与预览
```bash
hugo server -D
访问：

http://localhost:1313

新增内容
新文章
hugo new posts/xxx.md

新笔记
hugo new notes/xxx.md

新资料说明页
hugo new files/xxx.md

发布上线
git add .
git commit -m "Add new content"
git push


GitHub Actions 会自动构建并部署到线上。

内容规范建议
Posts（文章）

结构完整

有明确主题

可长期复用

Notes（笔记）

不追求完整

记录真实学习过程

可随时整理或升级为文章

Files（资料）

只存有价值、可复用的文件

文件本体放在 static/files/

标签与整理策略

使用少量但明确的 tags

定期回顾 notes

将成熟内容整理为 posts

删除无价值或重复内容

关于加密内容

支持简单前端加密，用于：

私人笔记

面试复盘

临时不公开内容

不用于高安全需求。