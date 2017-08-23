## vue-toast-component
* 基于 vue 2.0 开发的toast弹窗插件
* 占用内存小，性能好，样式好看




## Other

* 仿照一位Vue大牛的代码（全盘借鉴）捂脸 (github地址: [wc-messagebox](https://github.com/helicopters/wc-messagebox))
* 另外推荐一个Vue轮播图插件。占用内存小、流畅、api友好、更新维护快。(轮播图github地址: [wc-swiper](https://github.com/helicopters/wc-swiper))


## Install
```shell
npm i vue-toast-component --save
```

## Quick Start  Usage
```javascript
//main.js中引入
import Toast from 'vue-toast-component'
Vue.use(Toast)

在某个vue文件中使用
this.$toast(content, duration);

//举例
this.$toast("你好") 或者
this.$toast("你好",1500)

