# 原神《神秘的书页》风格花边 Enigmatic Pages

## 简介 Introduction

![神秘的书页 Enigmatic Pages](https://gi.yatta.moe/assets/UI/UI_ItemIcon_120577.png) 
![拉伸版 Streched](./fig/stretched.png)

一个自定义的 LaTeX 宏包, 用于绘制游戏《原神》中《神秘的书页》系列文本风格的 A5 页面花边.  
A custom LaTeX package for drawing A5 page borders in the style of the "Enigmatic Pages" from the game Genshin Impact.

## 使用方法 Usage

使用人所需要的文件仅有 `enigmatic_pages_border.sty` 一个. 其余文件作解释和介绍用.  
The user only need `enigmatic_pages_border.sty`. The other files are for explanation and introduction.

下载并将 `.sty` 文件放在你的 `.tex` 同级目录下, 并在 `.tex` 文件的在导言区添加 `\usepackage{enigmatic_pages_border}`, 一如 `./exempli/ex.tex` 所示.  
Download and place the `.sty` file in the same directory as your `.tex` file, add `\usepackage{enigmatic_pages_border}` at the preamble of your `.tex` file, as shown in `./exempli/ex.tex`.

## 依赖项目 Reliances

```tex
\RequirePackage{tikz}
\usetikzlibrary{calc}
\RequirePackage{eso-pic}
```

## 致谢 Acknowledgements

> 《神秘的书页》图标取自网站 [安柏计划 (Project Amber)](https://gi.yatta.moe), 在此予以感谢.  
> The icon of “Enigmatic Pages” is from website *[Project Amber](https://gi.yatta.moe)*, hereby acknowledging.
