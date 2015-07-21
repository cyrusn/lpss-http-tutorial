# 嵌入工具 iframe

Google Map、YouTube、facebook 還有很多網頁都設有嵌入工具。
只要直接將**嵌入連結**貼上 html 文件內即可。

```html
<iframe src="......."></iframe>
```
## 堂課1

仿照學校網頁中**聯絡我們**，製作一個`html`文本，文本名稱為`iframe.html`。

``` txt
P:/
└── html
    ├── basic.html
    ├── heading.html
    ├── list.html
    ├── table.html
    ├── link.html
    └── iframe.html
```

***題示1*** 同學於google map 中搜尋學校名稱，然後找找嵌入地圖的連結
![iframe03](./image/iframe03.png)

學校網頁：
![iframe01](./image/iframe01.png)

堂課結果：
![iframe02](./image/iframe02.png)

##堂課2

同學製作一個`html`文本，用以嵌入影片於網頁，文本名稱為`iframe2.html`。

``` txt
P:/
└── html
    ├── basic.html
    ├── heading.html
    ├── list.html
    ├── table.html
    ├── link.html
    └── iframe2.html
```

***顯示2*** 同學於youtube中搜尋學校名稱，然後選擇搜尋結果中的其中一段影片，再找嵌入影片的連結，如下:

![](./image/iframe04.png)

利用以上的嵌入影片連結，在`iframe2.html`完成此堂課得出以下結果:

![](./image/iframe05.png)

##堂課3

同學製作一個`html`文本，用以嵌入音頻檔案於網頁，文本名稱為`iframe3.html`，而老師提供的音頻檔名稱是`Kalimba.mp3`。

``` txt
P:/
└── html
    ├── Kalimba.mp3
    └── iframe3.html
```

***顯示3*** 同學放置的檔案應如下:
![](iframe06.png)

在```<iframe src="......."></iframe>```中的適當位置填上音頻檔案全名(包括副檔名```.mp3```)，完成此堂課得出以下的結果:

![](iframe07.png)