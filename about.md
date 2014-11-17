---
layout: page
---
##自我介绍：

- 张昂
- 学生
- 嗯，就这么多

##博客介绍：

基于 Jekyll 搭建在 github page 上，实现了文章列表以及查看文章的功能（坟蛋，但凡是个博客都这些功能），模板完全原创（摔，就几个div的堆叠吧）。

字体样式上借鉴了 [Fonts.css -- 跨平台中文字体解决方案](http://zenozeng.github.io/fonts.css/) 以及github页面对于代码字体的设定。由于使用 margin 布局，在操作 footer 置于最底的时候效果很差（是你笨好伐），所以就没有做置底。代码配色是 Jekyll 默认功能，由 Pygments 实现，配色方法选择了solarized light（修改了一下 background ），Pygments 好像没有对 `<code>` 做处理，所以自行写入了一些样式。

背景图片采用自 [subtlepatterns](http://subtlepatterns.com/geometry-2/) , favicon.ico 采用自暴走漫画的 PP 头像系列的银桑 PP 。

##样式展示：
文字：普通样式，*斜体*，**粗体**，<s>删除线</s>,`代码code`；

>这块儿就是引用样式了；

代码：

```python
def test():
   print "hello word!"
```
h1~h6：

#这是h1

##这是h2

###这是h3

####这是h4

#####这是h5

######这是h6

下面是一条分割线
***
列表：

- 普通条目1
- 普通条目2
- 普通条目3

1. 带数字的条目1
2. 带数字的条目2
3. 带数字的条目3

如果有新的在补充，[fork地址](https://github.com/angZhang/angzhang.github.io)（如果你真的不嫌弃这么简陋以及弱爆的兼容性的话）。
