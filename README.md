## vue-toast-component
* 基于 vue 2.0 开发的轻量手机toast弹框
* 占用内存小，性能好，样式好看

## Demo
<!-- > [请用浏览器的手机模式查看](https://zwhgithub.github.io/vue-toast/dist/#/) -->


## Effect
<!-- ![效果](https://qiniu.epipe.cn/5465939501580804096?imageView2/1/w/320/h/568) -->


## Install
```javascript
npm i vue-toast-component --save
cnpm i vue-toast-component --save  //国内镜像
```

##  Usage
```javascript
//main.js中引入

import Toast from 'vue-toast-component';
Vue.use(Toast);



this.$toast('这是弹框哦');
this.$toast('这是两秒的弹框',2000);
```


## Other
* src下面有demo可以参考.
* 如果有其他问题或者版本上, 功能上不兼容的 邮件沟通 452216418@qq.com