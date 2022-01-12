# Github 图床
此文件夹用于上传图片，以提供图片外链编写 Markdown

## 用法

首先配置环境如下

1. 安装 Git，并配置 github 账号下的另一台电脑的 .ssh
2. 使用 Git bash 随便选择一个文件夹，执行 git clone
   ```
   git clone git@github.com:EndeRHoshI/Photo.git
   ```
3. 至此，文件已经被拉下来了

然后就可以对文件进行编辑，如增减图片

处理完后，推到远程仓库，在 Github 上点击图片打开图片预览，复制地址栏的地址，把地址中的 blob 改为 raw，就可以加到 markdown 中去了

示例：

以下是一张图片：

![photo](https://github.com/EndeRHoshI/Photo/raw/master/%E5%A4%B4%E5%83%8F.png "恐龙")

## 目录
* blog 用于存放博客图片
* markdown 用于存放写 markdown 笔记的图片
* other 其他
