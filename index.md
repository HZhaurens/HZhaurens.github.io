---
# 基础配置（Jekyll/Hugo/Hexo通用）
layout: home
title: 我的个人博客
description: "技术笔记 | 生活随笔 | 学习记录"
---

<div class="header">
  ![头像](/assets/avatar.jpg){: .circle .shadow width="100" }
  <h1>你好，我是 <span class="highlight">你的名字</span></h1>
  <p>一名热爱技术的开发者，分享编程心得与生活思考</p>
</div>

---

### 📚 最新文章
{% for post in site.posts limit:3 %}
- [{{ post.title }}]({{ post.url }})  
  <small>{{ post.date | date: "%Y-%m-%d" }} | {{ post.content | strip_html | truncate: 50 }}</small>
{% endfor %}

[查看更多文章](/archive){: .btn}

---

### 🛠️ 技能与工具
- **语言**: Python/JavaScript/Go  
- **框架**: React/Django  
- **工具**: Git/Docker/VSCode  

---

### 🌐 联系我
- [GitHub](https://github.com/你的用户名)
- [Email](mailto:你的邮箱)
- [Twitter](https://twitter.com/你的用户名)

---

> "代码改变世界"  
> —— 保持好奇，持续学习
