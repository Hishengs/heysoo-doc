<p class="tip">
  静态文件功能默认不开启，你必须显式地在配置文件中开启它。
</p>

## 配置
在 `config.js` 中：
```js
module.exports = {
  static: {
    enabled: true,
    path: 'static', // 对应的映射路径
  },
}
```

## 使用
在静态文件目录下放置一张照片 `xxx.png`，打开浏览器 `http://localhost:86/static/xxx.png` 可以直接访问。