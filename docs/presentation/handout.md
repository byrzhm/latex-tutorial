---
title: Handout
parent: Presentation
---

# 制作 Handout

Handout 会省略动态效果, 会让 slides 更加紧凑, 适合学生复习使用.

```latex
\documentclass[handout]{beamer} 
```

## 只在 Presentation 中展示的内容

```latex
\mode<beamer>{ Only show up in presentation mode }
```

## 只在 Handout 中展示的内容

```latex
\mode<handout>{ Only show up in handout mode }
```
