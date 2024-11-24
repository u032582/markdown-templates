---
html:
  embed_local_images: true
  embed_svg: true
  offline: false
puppeteer:
  landscape: false
  format: "A4"
  scale: 0.75
  printBackground: true
  displayHeaderFooter: true
  headerTemplate: "<div style=\"font-size: 9px; margin-left: 1cm;\"><span class='title'></span></div>"
  footerTemplate: "<div style=\"font-family: '游ゴシック体', 'Yu Gothic', YuGothic, 'ヒラギノ角ゴ Pro', 'Hiragino Kaku Gothic Pro', 'メイリオ', 'Meiryo', sans-serif; position: relative; border-top: 1px solid black; margin: 0.7cm; font-size: 9px; width: 100%;\"><div style=\"position: absolute; width: 100%; top: 0.2cm; text-align: center;\"><span>-- Copyright © 2022 xxxxxxxx Co.,Ltd. All Rights Reserved. --</span></div><div style=\"position: absolute; right: 0; top: 0.2cm;\"><span class='pageNumber'></span> / <span class='totalPages'></span></div></div>"
  margin:
    top: 50
    right: 80
    left: 80
    bottom: 100
toc:
  depth_from: 1
  depth_to: 6
  ordered: false
export_on_save:
  html: true
  puppeteer: true
markmap:
  colorFreezeLevel: 2
  maxWidth: 300
---
# Markdown Exmples
[TOC]

## Tables
| タイトル | 列1 | 列2   | 列3  |
| -------- | --- | ----- | ---- |
| aaa      | >   | >     | aaaa |
| ^        | 1   | あsだ | -    |
| ^        | 123 | qwd   | -    |
| ^        | 21  | wqwdq | -    |

## Images
@import "assets/mindmap.png"

---

## PlantUML
@import "assets/sequence.puml"

## code block
```javascript {.line-numbers}
function add(x, y) {
  return x + y;
}
```

## 引用
> We're living the future so
> the present is our past.
>

## Adomonition

!!! note This is the admonition title
    This is the admonition body

!!! info This is the admonition title
    This is the admonition body

!!! warning This is the admonition title
    This is the admonition body

!!! error This is the admonition title
    This is the admonition body

!!! success This is the admonition title
    This is the admonition body

## Marked
==marked==

## 上付き
30^th^

## 下付き
H~2~O

## link
[Markdownリファレンス](https://shd101wyy.github.io/markdown-preview-enhanced/#/ja-jp/markdown-basics?id=criticmarkup)

## iframe ＋ mindmap
<iframe src="mindmap.html?file=README.md" width="100%" height="600px" scrolling="no"/>
