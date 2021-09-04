# 简单配置

SpaceVim 提供了我们可以自定义配置的文件，就是`~/.SpaceVim.d/init.toml`文件，

所有自定义的内容都可以放到这个文件中。这个文件夹也就可以通过 git 管理起来。

以下配置可参考[我的配置文件](https://github.com/wsdjeg/DotFiles/tree/master/SpaceVim.d)

# 空格键延迟

默认按下空格键是 1 秒后显示选项，由于刚刚上手，可以设置的短一些，例如 200 毫秒

```
set timeoutlen=200
```

# 换个主题

所有支持的主题: [主题模块](https://spacevim.org/layers/colorscheme/)

```
[options]
  colorscheme = "onedark"
```

# 语言支持

有些语言我用不到，注释掉吧。（这里根据个人情况来，我主要是用 vim 来写 Python 和 Go）

![](media/15160267878835.jpg)

# 字体配置

如果仔细看，可能会发现安装后有些显示问号（？）的地方，这是因为还需要配置一些字体。

这里字体我们使用 https://github.com/ryanoasis/nerd-fonts

可以这样安装：

```
brew tap caskroom/fonts
brew cask install font-hack-nerd-font
```

对于 MacVim，安装后在配置文件中加入：

```
[options]
  guifont='Knack Nerd Font:h12'
```

Terminal.app 需要单独配置字体：

![](media/15148306746160.jpg)

iTerm2.app 也需要单独配置字体：

![](media/15148306197631.jpg)

# 总结

然后，就 MacVim 像我这样啦。

![](media/15160268125722.jpg)
