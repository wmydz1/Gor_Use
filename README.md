Visit http://github.com/wendal/gor

## License

Released under the [MIT License](http://www.opensource.org/licenses/MIT)

### 图片写法

```

![Alt text]({{urls.media}}/mz.jpg) 

```

对应目录
/assets/media/mz.jpg

把文件拷贝到 /assets/media/ 目录就可以了

执行gor compile  

再执行 gor http


## 命令 例子
gor post "day2" /Users/samchen/Documents/APP/gor/example.com/img/mz.jpg

### gor -- Golang 编写的静态博客引擎

gor是使用 Go 实现的类 Ruhoh 静态博客引擎（Ruhoh like），基本兼容 ruhoh 1.x 规范。 相当于与 ruhoh 的官方实现（ ruby 实现），有以下优点：

速度完胜 -- 编译 wendal.net 近200篇博客,仅需要1秒
安装简单 -- 得益于 golang 的特性，编译后仅一个可运行程序，无依赖  

```
Visit http://github.com/wendal/gor

```