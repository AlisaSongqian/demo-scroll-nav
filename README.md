#基于 iScroll 前端框架实现的导航条

导航条在多列表页面中非常常见，当导航条中选项很多时，需要支持横向滑动。
iScroll.js 帮我们很好的解决了这个问题，并且支持惯性弹动效果。

##这个示例以脚本方式为开发者实现

* 示例请使用 Apploader 查看。

##开发指南

**调用示例**

```js
var myScroll = new IScroll('#wrapper', {
    disableMouse: true,
    disablePointer: true
});
```

* 推荐文档[http://cubiq.org/iscroll-5](http://cubiq.org/iscroll-5)
* 推荐文档[http://www.tuicool.com/articles/vMn2u2](http://www.tuicool.com/articles/vMn2u2)