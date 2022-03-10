---
layout: post
excerpt_separator: <!--more-->
title: CSS buttons done right
description: Do not make the user angry
date: 2022-03-10
categories: ["ux"]
tags:
- UX
---

<pre>
<code>
button {
    background: #ffeb3b;
    border: none;
    cursor: pointer;
    height: 40px;
    outline: none;
    padding: 0;
    width: 80px;
    font-size: 20px;
    border-radius: 2px;
}
</code>
</pre>


### Button padding

1 : 2 is ideal

### Font-size

button height * 0.9

### Button border radius

Font-size / 10
Keep the corners minimal unless it is an icon

### Icon buttons

border-radius : 28%
OR
circle

### Animated buttons

Twitter like animation

### FAB Floating action Buttons

Do not use unless necessary

Tumblr, Naver, Pinterest, Launchers 

### Outlines and Borders