# vscode 配置过程  

[教程](https://code.visualstudio.com/docs/cpp/config-mingw#_configure-bash-console-to-use)

``` 
1. 安装vscode(自行解决)
```
[点这里](https://code.visualstudio.com/)

```
2.安装插件
```
![](https://i.loli.net/2019/07/17/5d2ed9eb6d64d99081.png)

```
3.编译器（MINGW-W64）
```
[地址](http://mingw-w64.org/doku.php)

```
4.编译路径
```
> 右键‘此电脑’点击‘属性’出现下图
![](https://i.loli.net/2019/07/17/5d2edb58cc0ec78634.png)
![](https://i.loli.net/2019/07/17/5d2edb9cbace627436.png)
![](https://i.loli.net/2019/07/17/5d2edbb9bec1323467.png)  
然后更改为自己MINGW/bin/gdb如图
![](https://i.loli.net/2019/07/17/5d2edc1a4f41a66499.png)  

__*记得改为自己的文件目录*__

```
5.创建文件夹
```
文件夹中要有 *.vscode* 子文件夹
中间要有如下文件  
![](https://i.loli.net/2019/07/17/5d2edd820045028598.png)


```
6.可以开始愉快的做题了qwq
```

```
附：代码
```
> [c_cpp_properties.json](https://github.com/happyztw/code/blob/master/c_cpp_properties.json)  
> [launch.json](https://github.com/happyztw/code/blob/master/launch.json)  
> [settings.json](https://github.com/happyztw/code/blob/master/settings.json)  
> [tasks.json](https://github.com/happyztw/code/blob/master/tasks.json)
