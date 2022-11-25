# web-service in node

使用 node 原生寫法 建立 web service

參考

- [Express v0.0.1 的 source code](https://github.com/expressjs/express/blob/0.0.1/lib/express/core.js)
- [Node入門 » 一本全面的Node.js教學課程](https://www.nodebeginner.org/index-zh-tw.html)
- [上面這一本的英文版](https://www.nodebeginner.org/)

## 練習

用瀏覽器送出請求，做出操作讀寫檔案的功能。

(不行的話，做 Echo 也可以)。

> Echo 回傳請求的內容。

使用 [http.createServer](https://nodejs.org/dist/latest-v18.x/docs/api/http.html#httpcreateserveroptions-requestlistener) 之類的

### JSON

`application/json` 

並且建立以下幾個 API

- GET
- POST

### Form Data

沒有上傳檔案的 Form Data

上傳檔案 API

`content-type: multipart/form-data` 

觀察請求的 body 有什麼不一樣

