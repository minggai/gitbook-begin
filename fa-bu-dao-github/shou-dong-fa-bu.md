### 创建仓库与分支 {#创建仓库与分支}

1. 登陆到Github，创建一个新的仓库，名称我们就命名为`gitbook-tutorial`，这样我就得到一个`gitbook-tutorial`仓库。
2. 克隆仓库到本地：`git clone git@github.com:/USER_NAME/gitbook-tutorial.git`
3. 创建一个新分支：`git checkout -b gh-pages`，注意，分支名必须为`gh-pages`。
4. 将分支push到仓库：`git push -u origin gh-pages`。
5. 切换到主分支：`git checkout master`。

经过这一步处理，我们已经创建了`gh-pages`分支了，有了这个分支，Github会自动为你分配一个网址。

> [http://USERNAME.github.io/gitbook-tutorial](http://username.github.io/gitbook-tutorial)

你可以在项目页面右下角`setting`中看到：

![](https://einverne.github.io/gitbook-tutorial/imgs/gh-pages-setting.png "Github Pages")

Image - Github Pages

