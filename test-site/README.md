1.html标记区分不区分大小写，但是文件名区分大小写，文件路径和文件名建议使用“-”来分割单词。
<br>
2.python -m http.server [port] 使用python3启动本地测试服务器.
<br>
3.margin和padding的属性值顺序：如果是1个值，代表上下左右；如果是两个值，代表上下、左右；如果是3搁个值，代表上、左右、下；如果是四个值，代表上、右、下、左（顺时针方向）
<br>
4.图片居中：因为图片不是块级元素，光使用margin: 0 auto不能使图片居中，必须给图片赋予块级元素属性
<br>
```
img {
    display: block;
    margin: 0 auto;
}
```
