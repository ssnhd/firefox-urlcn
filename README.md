# Firefox 浏览器支持复制出带中文的 URL

例如复制带有中文的链接 

```
https://www.google.com/search?q=中文
```

但是粘贴后中文却变成代码 

```
https://www.google.com/search?q=%E4%B8%AD%E6%96%87
```

---
### 解决方法

1. Firefox 地址栏输入 `about:config`，接受风险并继续。
2. 输入框内输入 `browser.urlbar.decodeURLsOnCopy` 会弹出默认为 `false`，点击右侧切换为 `true`，这样复制的链接不会改变。

![](https://i.imgur.com/LDMf0w5.png)

其他浏览器如果没有安装插件，可以先复制一部分。例如复制 `ttps://www.google.com/search?q=中文`，粘贴后在前面加个 `h`。
