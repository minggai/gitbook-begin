# 运行

以管理员身份运行cmd，避免权限问题导致报错。

## gitbook init {#gitbook-init}

首先，创建如下目录结构：

```
$ tree book/
book/
├── README.md
└── SUMMARY.md

```

## gitbook serve {#gitbook-serve}

书籍目录结构创建完成以后，就可以使用`gitbook serve`来编译和预览书籍了：

```
$ gitbook serve

```

`gitbook serve`命令实际上会首先调用`gitbook build`编译书籍，完成以后会打开一个 web 服务器，监听在本地的 4000 端口。



