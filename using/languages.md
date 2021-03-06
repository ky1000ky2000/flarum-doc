# 添加语言

在 Flarum 中添加一种新的语言十分容易，只需按照下述的流程下载并安装你选择的语言包即可。

你添加一个语言包之后，你可以[把它设置成你的论坛的默认语言](#setting-the-default)。不论何时你感觉不需要其中一个安装过的语言包了，你都可以[禁用它](#disabling)。

如果你正在使用任何第三方的扩展，一定要在开始动手之前[读这部分](#third-party-extensions)。

## 语言包的安装

第一步，访问 Flarum 社区网站的[Extensions > Language](http://discuss.flarum.org/t/languages)标签，并找到你想要安装的语言包。一定要确保下载的ZIP文件是符合你正在运行的 Flarum 版本的。

1. 解压ZIP文件并阅读附上的**readme.txt**文件中的说明。
2. 通过SSH，FTP，或者你的服务提供商的控制面板来登录到你的服务器。
3. 跳转到你的Flarum安装的**extensions/**目录。
4. 创建一个新的子目录。*按照说明里指出的那样来命名！*
5. 上传解压出的文件夹里的所有东西到你刚刚创建的子目录。
6. 用浏览器跳转到管理界面的**Extensions**页面。
7. 选择你刚刚安装的语言包并启用它。

这就是你要做的所有的事！你现在应该已经能够使用网站的头部的语言选择器，切换你论坛的显示语言至新的语言。


## 设置默认语言

在你安装了新的语言包并确认它能顺利工作后，你可能想要把它设置为用户的默认显示语言。你可以在管理员面板的 Basic 页面设置这一选项。

## 禁用语言包

如果你最终决定停止支持一个特定的语言，你可以把它关掉。只需要在管理界面里定位到**Extensions**页面里的语言包并禁用它。

当你的站点只支持一个语言而且你不希望网站的头部出现一个语言选择器，禁用掉一个语言是很有用的。当只启用了一个语言的时候，语言选择器是隐藏的。

## 第三方扩展

尽管从 Flarum 社区网站上下载的语言包会一般包括所有和 Flarum 捆绑的扩展的翻译，他们*不会*是一个在你安装的第三方扩展上也起作用的规则。由开发者来决定是否提供并维护他们的扩展的翻译。

所以当你安装一个第三方扩展之前，你应该检查一下来确保它包含有适用于你所安装的所有语言包的翻译。如果你发现一个扩展不支持你需要的一个语言，请直接联系开发者并协商添加必要的翻译。

> 译者：[@imcaffrey](https://github.com/imcaffrey)
> Updated by ttnl 17/1/21
