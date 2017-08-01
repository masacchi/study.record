---
  layout: layout
  title: 研究記録
---

# masacchiの勉強部屋

```java
public static void main(String[] args){
  System.out.println("Hello World!");
}
```

## 投稿
<ul>
{% for post in site.posts %}
  <li>
    <a href=".{{ post.url }}">{{ post.date | date_to_long_string }} : {{ post.title }}</a>
  </li>
{% endfor %}
</ul>
