---
layout: home
title: "CHU의 블로그 자동화 실험실"
description: "GPT와 자동화로 돌아가는 실험형 블로그 🤖"
---

# 💡 CHU의 블로그 자동화 실험실

안녕하세요! 이 블로그는 자동화된 AI 콘텐츠로 매일매일 업데이트됩니다.  
GPT로 생성된 글, 자동 생성 이미지, 그리고 하루하루 기록들이 올라와요.  
재밌게 봐주세요! 😊

---

## 📰 최근 글 보기

{% for post in site.posts limit:5 %}

- [{{ post.title }}]({{ post.url }}) <small>{{ post.date | date: '%Y-%m-%d' }}</small>
  {% endfor %}

---

## 👤 블로그 정보

- 작성자: **{{ site.author.name }}**
- 이메일: **{{ site.author.email }}**

GPT와 자동화로 돌아가는 실험형 블로그 🤖
