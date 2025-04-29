---
# Jekyll 的 Front Matter（元数据）
layout: home
title: 欢迎来到我的博客
description: 这里是技术分享与生活思考的空间
---

![个人头像](/assets/images/avatar.jpg){: .profile-image }

## 👋 你好，我是 [你的名字]

一名热爱技术的开发者，专注于 **Web开发** 与 **开源项目**。  
这里记录我的学习笔记、项目经验和生活感悟。

---

## 📌 最新文章

{% for post in site.posts limit:5 %}
- [{{ post.title }}]({{ post.url }}) - {{ post.date | date: "%Y-%m-%d" }}
{% endfor %}

[查看全部文章](/archive){: .button}

---

## 🛠️ 技能栈

- **编程语言**: JavaScript / Python / Java
- **前端框架**: React / Vue.js
- **工具**: Git / Docker / VS Code
- **其他**: Linux / MySQL / AWS

---

## 🌐 社交链接

- [GitHub](https://github.com/你的用户名)
- [Twitter](https://twitter.com/你的用户名)
- [Email](mailto:你的邮箱)

---

## 🎯 近期目标

- [x] 完成个人博客搭建  
- [ ] 学习 Rust 语言  
- [ ] 开发一个开源 CLI 工具

---

> **座右铭**: Stay hungry, stay foolish.  
> 保持好奇，持续探索！
