---
marp: true
theme: presentation_theme
math: katex
---


<!-- class: title _class: lead -->

## タイトル

### サブタイトル

<br>

Name
Address
Date

---
<!--
class: slides
_footer: 'Photo by Michal Vasko　on Unsplash'
paginate: true
-->


# グラデーションのタイトル文
## 直下に各スライドのリード文をh2 `##` で入れる。

本文の表示位置は変えていません。

- 箇条書きなどは
- このとおり
- hello world
  - インデントも下げれます

---
<!-- class: slides -->

# 数式

* 数式も$\KaTeX$で入れることが可能
$$
\begin{align*}
y &= mx + b \\
z &= ax^2 + bx + c
\end{align*}
$$

* **太字で強調**すると自動で設定した色に変更されます


---
# フォントの調整
<!-- class: small-text -->
* `<!-- class: small-text -->`を入れると指定したページのスライドのフォントを小さくすることも可能

<!-- class: large-text -->
* 逆に，`<!-- class: small-text -->`を入れると指定したページのスライドのフォントが大きくなる

---
<!-- class: slides -->

# コードブロックの挿入

* プログラムコードもブロックとして挿入可能
  - Markdown記法と同様にバッククォート3つで囲む


```{r}
library(tidyverse)
```

