# markppt

项目源码 <https://github.com/fritx/markppt>

<img width="140" src="screenshots/2015-04-11 02.09.47.png">
&nbsp;&nbsp;<img width="403" src="screenshots/2015-04-10 23.17.37.png">

## 一篇markdown，一份ppt。

- 一个读取markdown文件，生成网页幻灯片(即ppt)的工具
- 很多时候，我们用markdown来书写我们的人生
- 很多时候，我们需要有一份ppt来向世界分享观点
- 网页实现，处处发布，随机背景色，css3动画切换
- 超响应式布局，自动缩放，不再畏惧屏幕尺寸

点击查看演示

- [My Talk](examples/mytalk/talk.md.html)
- [gulp-eol bug之总结](examples/gulpeol/gulp-eol-bug.md.html)

```shell
$ npm i -g markppt   # 从npm安装
$ markppt mytalk/talk.md   # markdown路径
```

将会在[原目录](https://github.com/fritx/markppt/tree/master/examples/mytalk/)

```plain
- mytalk/
  - Desert.jpg
  - talk.md
```

生成`ppt_`文件夹，和一份`talk.md.html`，打开即可[浏览ppt](examples/mytalk/talk.md.html)

```plain
- mytalk/
  - ppt_/ (√)
  - Desert.jpg
  - talk.md
  - talk.md.html (√)
```