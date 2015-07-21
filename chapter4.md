# 表格 table
以下為表格`table` 的結構

```html
<table>
  <tr>
    <th>標題一</th>
    <th>標題二</th>
  </tr>
  <tr>
    <td>F5A</td>
    <td>F5B</td>
  </tr>
  <tr>
    <td>F5C</td>
    <td>F5D</td>
  </tr>
</table>
```

- `<tr>`和`</tr>`內的文本，為表格的一行。
- `<th>`和`</th>`內的文本，為表格的標題列。
- `<td>`和`</td>`內的文本，為表格的一列。


![](./image/table03.png)

# 表格框線 border
為了讓表格內容更清晰表達出來，我們可為表格加上框線。
於`<head>` `</head>` 標籤之間加入以下程式碼


```css
  <style>
    table, th, td {
        border: 1px solid black;
        border-collapse:collapse;
    }
  </style>
```
程式碼的意思大致如下：

```
<網頁風格>
    表格,行,列,{
        框線：1厚度,實線,黑色;
        框線合併;}
</網頁風格>
```

#合拼行 / 列
- 同學可利用屬性`colspan`合拼列
- 同學可利用屬性`rowspan`合拼行

例：

```html
<table>
  <tr>
    <th colspan="2">班別</th>
  </tr>
  <tr>
    <td>F5A</td>
    <td>F5B</td>
  </tr>
  <tr>
    <td>F5C</td>
    <td>F5D</td>
  </tr>
</table>
```

## 堂課1  

仿照學校網頁中 **課程 -> 各班上課時間表**，制作一個`html`文本，文本名稱為`table.html`。

``` txt
P:/
└── html
    ├── basic.html
    ├── heading.html
    ├── list.html
    └── table.html
```
提示：
1. 回到 Chapter2, 複製 堂課0 的 html 程式碼。
2. 在`<head>` `</head>`之間複製有關網頁風格的程式碼。
3. 回到 Chapter5, 同學可利用本課第一段程式碼製作堂課所需表格。
4. 緊記所有程式碼需置於`<body>` `</body>`內。


學校網頁：
![table01](./image/table01.png)

堂課結果：
![table02](./image/table02.png)
