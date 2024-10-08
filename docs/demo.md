## 微信公众号格式化工具

> 使用微信公众号编辑器有一个十分头疼的问题——粘贴出来的代码，格式错乱，而且特别丑。这款编辑器能够解决这个问题。

## 微信公众号文章在线编辑工具

该工具非原创，只是基于[online-markdown](https://github.com/barretlee/online-markdown)扩展的。

演示地址：[http://md.jay.ac.cn/](http://md.jay.ac.cn/)

![图片预览](./imgs/demo.png)

## 如何运行？

- `docs`是已经编译好的文件，可以直接运行`docs`目录下的`index.html`

## 如何打包？

- `npm install -g webpack`
- `webpack`

## 如何自定义拓展？

修改完成后，在项目根目录下执行`npm i` 后执行 `webpack`，编译完成后运行`docs`目录下的`index.html`

## 如何使用？

编写完成后，点击“复制”按钮后通过ctrl + c复制，然后粘贴到微信公众号的文章发表编辑器中即可

## linux系统nginx不支持中文路径

```$xslt
yum -y install convmv
convmv -fGBK -tUTF8 -r --notest target
```
其中-f是源编码，-t是目标编码，-r是递归处理目录，--notest是不移动，实际上对文件进行改名，target是目标目录

## 关注我的公众号

<center>
<img src="./imgs/wechat.png">
</center>
