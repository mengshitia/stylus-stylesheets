这里存放一些在 Stylus 插件上使用的自定义样式表

---

## 如何使用
首先需要安装 Stylus 插件，各主流浏览器应该都支持。
然后找到你需要的样式表（下方有列出），复制，之后打开插件，新建一个样式表，把复制的内容粘贴进去，Stylus 会提示导入使用。

导入到本地的样式表可随时修改、禁用或者删除。

## 样式表文件
### archlinux-manpage-color.css
把 Arch Linux 手册查询网站的纯黑背景和纯白文本替换为深蓝色背景和偏灰色文本。

### dark-sphinx_rtd_theme.css
针对使用 `sphinx_rtd_theme` 主题的一部分网站手写了一份自己用的深色模式，因为这个主题根本没有深色模式。

### github-no-round-avatars.css
GitHub 上的用户头像统统变成方的。个人主页上的状态小图标也换了个位置，避免遮挡用户头像。

### mdn-hide-ads.css
隐藏 MDN 文档站的横幅广告，如果已经装过反广告插件，这个样式表其实没什么用。

### restore-stylus-action-button-text.css
Stylus 新版本（v2.4.0）中把编辑器的一些按钮标签替换成图标了，无法适应。
于是按照 [这个 comment](https://github.com/openstyles/stylus/issues/2167#issuecomment-4914419195) 里的提示把标签的文本弄回来了。

### zshell-doc.css
ZShell 文档网站的深色模式。
