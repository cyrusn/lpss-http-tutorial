# 甚麼是html？
- HTML是用來製作網頁的標記語言
- HTML是Hypertext Markup Language的英文縮寫，即超文本標記語言
- HTML語言是一種標記語言，需要編譯，接由瀏覽器執行
- HTML文件是一個文本文件，含了一些HTML元素，標籤等.HTML文件必須使用html或htm為文件後綴名
- HTML是大小寫不敏感的，HTML與html是一樣的。


## 堂課0:

``` html
<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf8">
    <title>網頁標題</title>
  </head>

  <body>
    <h1>標題一</h1>
    <p>內文</p>
  </body>
</html>
```
建立 `basic.html`，複製並貼上以上文字，利用瀏覽器開啟`basic.html`。

![basic01](./image/basic01.png)
﻿
現在解釋一下上面的例子

- `<!DOCTYPE html>`代表文檔類型，大致的意思就是「這個網頁是HTML文檔」。
- `<meta charset="utf8">` 代表文檔編碼為`utf-8`
- HTML文檔中，一個標籤是`<html>`。這個標簽告訴瀏覽器這是HTML文檔的開始。
- HTML文檔的最後一個標籤是`</html>`，這個標簽告訴瀏覽器這是HTML文檔的終止。
- 在`<head>`和`</head>`標籤之間的文本是頭信息.在瀏覽器窗口中，頭信息是不被顯示在頁面上的。
- 在`<title>`和`</title>`標籤之間的文本是文檔標題，它被顯示在瀏覽器窗口的標題欄。
- 在`<body>`和`</body>`標籤之間的文本是正文，會被顯示在瀏覽器中(見body標簽)。
- 在`<h1>`和`</h1>`標籤代表標題一。
- 在`<p>`和`</p>`標籤代表段落。

## 堂課1:
在 `basic.html` 的適當文字位置修改成自己的網頁，如下所示:

![](./image/basic02.png)

## 堂課2:
在 `basic.html`中可以加入背景底色，以下是其標籤碼及圖示:

```<body bgcolor = yellow>```
  