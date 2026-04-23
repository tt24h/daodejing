从 Typst 代码到 pdf 至少有两种途径：1. 本地编译，2. 在线编译。

### 1. 本地编译

本地编译需要安装 vscode 及 相应插件，网上有教程。

搭建好环境后，用 vscode 打开本地的「编译用代码/」内的 `main.typ` ，完成。

可能还需要安装 Noto Serif CJK SC、Noto Sans CJK SC 这两款字体。或者修改代码，使用本地已安装的其他字体。

### 2. 在线编译

需要注册 Typst 官方免费账号，无任何安装，手机上也能操作。

1. 注册免费账户：https://typst.app/ 
2. 新建项目：找到 Empty document 大按钮，点击，先随便输入个项目名称。
3. 上传资源：将本地「编译用代码/」里的所有内容，上传至新建的项目。
4. 指定预览文件：在侧边栏选中 `main.typ` 文件，右键设为预览文件（或者点击“👁”图标）。
5. 完成：导出 pdf。

上传后，项目页面 Files 栏内，大概这样子：

```less
📂代码
📂数据
DaoDeJingExt-Light.ttf
main.typ 👁
main1.typ
```

点亮各 `main*.typ` 文件的👁，查看不同形式的输出。

* `main.typ` 输出 老子道德经：四种原文表.pdf。
* `main1.typ` 仅输出各表首行的 校订文。

本仓库 [Releases](https://github.com/tt24h/daodejing/releases) 内的 `code_logic.pdf` ，介绍了此文档项目内各个文件、函数的调用关系。

