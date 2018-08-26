首先构建静态页面：

`gitbook build`

下一个步骤使用了`gh-pages`这个工具，它可以将文件夹一键发布到 GitHub 项目下的`gh-pages`分支中。

首先先安装`gh-pages`工具：

```
npm install -g gh-pages
```

然后输入以下指令：

```
gh-pages -d _book
```

然后 \_book 下的所有文档都会部署到`gh-pages`分支上。

访问地址：

http://USERNAME.github.io/REPOSITORIES\_NAME

