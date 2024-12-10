---
title: Common CSS Pitfalls & How to Fix Them
description: Here is a list of the common mistakes on CSS code that beginners often make.
tags: CSS
---

## 1. Using px in font-size

Using px in font-size is more inaccesible as it doesn't respect the user's browser setting on the font-size. What you should do is use `rem` instead. This applies to other typography-related properties like `line-height` and `letter-spacing`

## 2. Setting fixed-widths and heights

Let's say you have a card component that has a width of 320px or 20rem. You then set `width: 320px` on it but that is a very big mistake as it makes it unresponsive and it also causes overflow issues. What you need to do is to set it as `max-width`. So, your code will now look like this

```diff-css
- .card {
-   width: 320px;
- }

+ .card {
+   width: 100%;
+   max-width: 320px;
+ }
```

Setting max-width in this case will make your card responsive and be able to shrink or grow. `width: 100%` is used here but it depends as child elements that are centered using flex or grid width is more like `fit-content` which your probably don't want most of the time

## 3. Unnecessary specificity

## 4. Too much wrappers
