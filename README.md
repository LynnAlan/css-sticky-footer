# css-sticky-footer
搞web页面开发的时候会遇到一个页面内容很少的时候，footer 会飘起来，处在页面的半腰间，这样会看上去很丑。
但是当内容很多的时候，又希望footer处在内容的底部，不是屏幕底部。
## 两个demo使用纯css实现footer固定在内容底部
#### 实现原理
##### 方法一
* ```html body ``` 标签必须设置高度为"100%",同时将其余盒子的``` margin padding ```全部移除，我用了最简单粗暴的方式 ```  *{margin:0;padding:0}```
* 