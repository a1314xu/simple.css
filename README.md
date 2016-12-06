# simple.css

[![Build Status][travis-image]][travis-url]
[![LICENSE][license-image]][license-url]

> A simple to CSS resets

## 简介

一个简单的CSS重置。抛去冗余，追求跨浏览器的一致性。

**下载**

https://github.com/Huyunxiu/simple.css/blob/master/simple.css

## 浏览器支持

不支持IE8以下版本，包括IE8。其余浏览器全部拥有良好支持。

## 日志

1. 抹平了所有元素(包括`:after`和`:before`)的`margin`,`padding`,`outline`。
2. 统一所有元素（包括`::after和::before`）盒模型为IE盒模型。
3. H标题的字体大小统一继承自`body`，字体宽度设为默认。方便自定义调整。
4. 去除`ul`的`list-style`。
5. 去除`a`标签的下划线。
6. `iframe`的border设置为0。
7. `table`系元素相邻边框合并，并且设置行和单元格的边框在横向和纵向上的间距为0。

[travis-image]: https://travis-ci.org/Huyunxiu/simple.css.svg?branch=master
[travis-url]: https://travis-ci.org/Huyunxiu/simple.css
[license-image]: https://img.shields.io/badge/LICENSE-MIT-%2331b794.svg
[license-url]: LICENSE.md