---
title: Using a CSS reset
description: What's a CSS reset? What does it do? What should I use?
tags: CSS
---

## What's a reset?

A CSS reset is a set of rules that you can include in your code that usually provides better defaults. In a way, it provides a blank canvas to start your project on. [This reset from Josh Comeau](https://www.joshwcomeau.com/css/custom-css-reset/#the-css-reset-1) is an example. [This reset from Andy Bell is an another example](https://piccalil.li/blog/a-more-modern-css-reset/)

## What does it do?

It provides better defaults depending on the type of project. Most resets typically share some lines of code and it doesn't matter that much depending on the type of project. What I mean by "type of project" is text-heavy sites like blogs, heavily-customized sites like landing pages, sites that use a different CSS approach like Atomic CSS.

A code example that can be normally found in most resets is this:

```css
*,
*::after,
*::before {
  box-sizing: border-box;
}
```

## What should I use?

If your site is more text-heavy and similar to blogs, use [Andy Bell's](https://piccalil.li/blog/a-more-modern-css-reset/). If your site is more customized and similar to landing pages, use [Josh Comeau's](https://www.joshwcomeau.com/css/custom-css-reset/#the-css-reset-1). You might have heard of other resets like [meyerweb](https://meyerweb.com/eric/tools/css/reset/) or [normalize](https://www.npmjs.com/package/normalize.css/v/3.0.3) but they're quite old and not that much used anymore. 

**Don't forget that you can always customize the resets by yourself!**

