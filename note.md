---
marp: true
title: 
author: Winson
theme: gaia
backgroundColor: white
color: black
style: |
    section {
        font-size: 25px;
    }
math: katex
paginate: true
---
# <div style="text-align: center; font-size:60px;">This is Title</div>

<div style="text-align: center; font-size:70%; font-family: 'Times New Roman'; ">

![](note.assets/jerry.png)
You can add title to a pic, title font size can be modified.
</div>

Use `---` to make a page.

<!--
This is comment, only visible to lecturer.
-->

<!-- 
Multiple comments okay.
 -->
---
# Title of a page

Like markdown, different numbers of # are titles.

Add a `<br/>` as empty line.

<br/>

Most attractive thing is that almost everything in markdown can be put into marp slides.

**Bold contents** is ok.

*Italic* and ~~deleted~~ too.

Latex Math Content:

$$
\sin^2a + \cos^2a = 1 \\
\sin2a = 2\sin a \cos a
$$

---
Codes:

``` Python
def fun():
    print("hello")
```

Inline math and code:

If $\mathbf{a}$ and $\mathbf{b}$ are catheti, $\mathbf{c}$ is hypotenuse, $a^2+b^2=c^2$ is always right.

`echo hello` print hello in bash.
 
Tables:

| ColA   | ColB | ColC |
| ------ | ---- | ---- |
| apple  | ae   | pl   |
| orange | aoe  | rng  |

---

An inline image:

![w:200 contrast:200%](note.assets/jerry.png)

One page can contains multiple inline images:

![w:200 h:200](note.assets/tom.png)

---

![bg 40%](note.assets/jerry.png)

You can also use w/h to resize width and height of 
a BackGround like inline image. 

---

![bg left:50% 40%](note.assets/jerry.png)

This is a List

1. You can put BG left or right. 
2. You can put multiple images in BG

This is a List one by one.

1) For more image syntax visit
2) https://marpit.marp.app/image-syntax

---
<!-- 
_backgroundImage: url(note.assets/jerry.png);
_backgroundPosition: 75% 75%;
_backgroundSize: 30%;
-->
Unordered List: 

+ You can also set BG with Directives. 
+ In this way position and size are configurable. 

Unorderd one by one:

* One
* Two

---

If you want to add many pic and set their positions, you can use HTML.

<img title="" 
src="note.assets/jerry.png" 
alt=""
style="position:absolute;
width:20%;
height:;
top:200px;
left:20%;
">

<img title="" 
src="note.assets/tom.png" 
alt=""
style="position:absolute;
width:30%;
height:;
top:200px;
right:20%;
">



---

Above is  the tip of a substantial iceberg, try marp and VISIT https://marp.app/ to explore more! 
