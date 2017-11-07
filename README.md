# ru_xaringan

Minimalist xaringan theme for html presentations using RU style/colors

## Examples

![Title page](./img/ex/title_page.png)

Example presentation [here](http://www.jvcasillas.com/ru_xaringan/slides/index.html). 

## Usage

You can use ```lingStuff::create_project()``` or just copy and paste the css link below. 

```
---
title: "Title here"
subtitle: "Sub-title here"
author: "Your Name"
date: "Rutgers University </br> `r Sys.Date()`"
output:
  xaringan::moon_reader:
    lib_dir: libs
    css: ["http://www.jvcasillas.com/ru_xaringan/css/rutgers.css", "http://www.jvcasillas.com/ru_xaringan/css/rutgers-fonts.css"]
    nature:
      beforeInit: "http://www.jvcasillas.com/ru_xaringan/js/ru_xaringan.js"
      highlightStyle: github
      highlightLines: true
      countIncrementalSlides: false
      ratio: "16:9"
---
```