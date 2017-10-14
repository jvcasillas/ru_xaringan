# ru_xaringan_css

Minimalist xaringan theme for html presentations using RU style/colors

## Examples

![Title page](./img/ex/title_page.png)

Example presentation [here](http://www.jvcasillas.com/ru_xaringan_css/slides/index.html). 

## Usage

```
---
title: "Title here"
subtitle: "Sub-title here"
author: "Your Name"
date: "Rutgers University </br> `r Sys.Date()`"
output:
  xaringan::moon_reader:
    lib_dir: libs
    css: "http://www.jvcasillas.com/ru_xaringan_css/css/ru_xaringan.css"
    nature:
      highlightStyle: github
      highlightLines: true
      countIncrementalSlides: false
      ratio: "16:9"
---
```