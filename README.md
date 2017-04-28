# Chrome Plugin Css3 Animation

快速给页面加上炫酷css3动画的chrome插件。

## 使用
### 1.从chrome webstore下载
[chrome应用商店安装地址https://chrome.google.com/webstore/detail/lhbbbidpkalopmenjffckblgbdhcffpa](https://chrome.google.com/webstore/detail/lhbbbidpkalopmenjffckblgbdhcffpa)

### 2.直接下载crx文件
[下载地址]()

### 3.自行构建
- `npm install -g vue-cli`
- `git clone https://github.com/vace/css3-animation-generator`
- `cd css3-animation-generator && npm install`
- `npm run app`


## 样式导出规则：
1. 优先使用带有 `c3`前缀的class，如 `<span class="c3-test">animate it</span>`
2. 如果存在class，则使用class选择器，如 `<span class="fl animate">animate it</span>`
3. 如果定义了Id，则使用id选择器，如 `<span id="anim1">animate it</span>`
4. 如果都不存在，则使用内部自定义的选择器查找方案


## Remark

- [animate.css](https://github.com]daneden/animate.css)
- [magic.css](https://github.com/miniMAC/magic)
- [iview](https://github.com/iview/iview)
- [vue](https://github.com/vuejs/vue)
- [chrome developer](https://developer.chrome.com/extensions)