---
layout: default
title: promise的小站喵~
---

# promise

promise的学习笔记喵。

## 最新笔记

<ul>
  {% for post in site.posts limit: 5 %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
      <small>{{ post.date | date: "%Y-%m-%d" }}</small>
    </li>
  {% endfor %}
</ul>

## 学习分类

{% assign categories = site.categories | sort %}
{% for category in categories %}
  <h3>{{ category[0] }}</h3>
  <ul>
    {% for post in category[1] %}
      <li>
        <a href="{{ post.url }}">{{ post.title }}</a>
        <small>{{ post.date | date: "%Y-%m-%d" }}</small>
      </li>
    {% endfor %}
  </ul>
{% endfor %}

## 关于我

<div style="text-align: center;">
  <img src="{{ '/image/avatar.png' | relative_url }}" alt="我的头像" style="width: 150px; height: 150px; border-radius: 50%; object-fit: cover; margin-bottom: 1rem;">
</div>

杭电网安喵，主要学习方向是量子计算。

## QCQI

>这是QCQI的的学习笔记


## 概率论与数理统计


## 数学建模