---
layout: default
title: "CHU의 블로그 자동화 실험실"
---

# 🧠 CHU의 블로그 자동화 실험실

안녕하세요! 이 블로그는 자동화된 AI 콘텐츠로 매일매일 업데이트됩니다.  
GPT로 생성된 글, 자동 생성 이미지, 그리고 하루하루 기록들이 올라와요.  
재밌게 봐주세요! 😊

---

## 📚 최근 글 보기

<ul>
  {% for post in site.posts limit:5 %}
    <li>
      <a href="{{ post.url }}">{{ post.date | date: "%Y-%m-%d" }} - {{ post.title }}</a>
    </li>
  {% endfor %}
</ul>

---

_자동화는 로망이다..._
