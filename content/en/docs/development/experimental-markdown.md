---
layout: default
author: irosyadi
title:  Experimental Markdown
date: 2020-11-26 21:10:40
category: development
tags: ["markdown"]
draft: false
---

#  Experimental Markdown

Experimental markdown to check Markdown parser compatibility between VNote+Viki, Gatsby-starter-bee, and Gitbook.  

## Internal Link Reference
### Type 1
[About Me](/blog/about-me)
In VNote App `/blog/about-me` refer to `C://blog/about-me`
In github.io and netlify, it successfully goes to about-me page. It was fail in gitbook.

- [Interactive and Explorable Sites](/app/interactive-explorable-web)
- [Machine Learning Interactive Visualization](/research/ml-visualization)
- [Interactive Books](/book/interactive-book)
- [Data Visualization](/note/data-visualization)

Success in Netlify. Success in Github. Fail in Gitbook.

### Type 2
- [Interactive and Explorable Sites](../app/interactive-explorable-web.md)
- [Machine Learning Interactive Visualization](../research/ml-visualization.md)
- [Interactive Books](../book/interactive-book.md)
- [Data Visualization](../note/data-visualization.md)

Fail in Netlify. Success in Github. Success in Gitbook.

### Type 3
- [Interactive and Explorable Sites](/app/interactive-explorable-web.md)
- [Machine Learning Interactive Visualization](/research/ml-visualization.md)
- [Interactive Books](/book/interactive-book.md)
- [Data Visualization](/note/data-visualization.md)

Fail in Netlify. Fail in Github. Success in Gitbook.

### Type 4
- [Interactive and Explorable Sites](../app/interactive-explorable-web)
- [Machine Learning Interactive Visualization](../research/ml-visualization)
- [Interactive Books](../book/interactive-book)
- [Data Visualization](../note/data-visualization)

Netlify. Github. Gitbook.

## Number and Bullet

1. One
2. Two
- Three
    - Three.a
    - Three.b

4. Four
5. Five


- List A
2. List B
- List C

## Keyboard
<kbd>imron</kbd>

## Comment
`<!-- Write your comments here -->`

Here is the comment:  
<!-- Write your comments here -->

## Symbol List

💬 speech  
🌏️ globe  
⭐️ star  
🚀 rocket  
👣 footprints  
⚓️ anchor  
🔥 fire  
🎯 target  
📌 pin  
⛔ stop  
‼️ double warning  
❗️ warning
⁉️ question  
✔️☑️ check mark  
❌ cross  
ℹ️ info  
📧 email  
🌐 web  
▶▷ triangle  
⚠️ warning  
💥 danger  
📝 note  
☝️ remember  
⚡️ flash

## Image Hosting in Github

![QR Code Image-small](https://raw.githubusercontent.com/irosyadi/vnote.image/master/1608464780_20201220183102525_18817.png)

## Tittle YAML
- Cannot use `:` in tittle

## Content
- Cannot use `% {` in github.io
- Cannot use `|` in github.io


## SVG
github.io and gitbook.io cannot render svg

![crocodile](https://snapsvg.io/assets/images/crocodile.svg)


The probability of getting \\(k\\) heads when flipping \\(n\\) coins is:
$$\tag*{(1)} P(E) = {n \choose k} p^k (1-p)^{n-k}$$

Inline equation with one dollar sign: $ E=mc^2 $ (worked in VNote and Gatsby).  
Inline equation with two dollar sign: 
$$ E=mc^2 $$  
(worked in Gatsby, Jekyll and Gitbook).  

### New Paragraph
 
- Newline equation with two dollar signs.  

$$ \sin(\alpha)^{\theta}=\sum_{i=0}^{n}(x^i + \cos(f)) $$

$$a+b=5$$


## 23. Latex

### 23.1. Inline Equation
- Equation with one dollar sign `$` works inline in VNote
- Equation with two dollar signs `$$` works inline in Jekyll and Gitbook, but not in VNote

***markdown***

```
Inline equation with one dollar sign: $E=mc^2$ (worked in VNote and Gatsby).  
Inline equation with two dollar sign: $$E=mc^2$$ (worked in Gatsby, Jekyll and Gitbook).
```

***display***  

Inline equation with one dollar sign: $E=mc^2$ (worked in VNote and Gatsby).  
Inline equation with two dollar sign: $$E=mc^2$$ (worked in Gatsby, Jekyll and Gitbook).  

### 23.2. Newline Equation

***markdown***

```
Newline equation with two dollar signs.

$$\sin(\alpha)^{\theta}=\sum_{i=0}^{n}(x^i + \cos(f))$$
```

***display***

Newline equation with two dollar signs.  
$$\sin(\alpha)^{\theta}=\sum_{i=0}^{n}(x^i + \cos(f))$$

