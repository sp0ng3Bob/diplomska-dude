---
title: TITLE_YO
posts:
  0:
    title: First Post
  1:
    title: Second Post
---

# {{ page.title }}

## Custom Posts List:
{% for post in page.posts %}
- {{ post[1].title }} (ID: {{ post[0] }})
{% endfor %}

## Aplications:
<details><summary>App trunk</summary>
  
**bla bla bla**  
</details>

## Notes

<details open><summary><em>Shopping list</em></summary>
  
* Vegetables
* Fruits
* Fish
</details>

### lol

<div class="i"> **HELLO** <span>**yo**</span></div>

[link *foo **bar** `#`*](/uri)

> [!NOTE]  
> Highlights information that users should take into account, even when skimming.

> [!TIP]
> Optional information to help a user be more successful.

> [!IMPORTANT]  
> Crucial information necessary for users to succeed.

> [!WARNING]  
> Critical content demanding immediate user attention due to potential risks.

> [!CAUTION]
> Negative potential consequences of an action.
