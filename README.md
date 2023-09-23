# LinuxFontsSettings
本仓库用于Linux系统字体修改，修正中文字体乱码，汉字显示异常等。

## 所需字体
- [Noto字体](https://packages.debian.org/trixie/fonts-noto)
- [更纱黑体](https://github.com/be5invis/Sarasa-Gothic)

Debian12系统环境下，安装Noto字体：`sudo apt install fonts-noto`，更纱字体需要下载解压缩至`/usr/share/fonts/*`文件夹中，打开shell刷新字体缓存即可`fc-cache -fv`。

## fonts.conf文件
`fonts.conf`文件直接存放在`~/.config/fontconfig/`路径下即可。

## 参考文章
[基本根据这篇文章来设置](https://szclsya.me/zh-cn/posts/fonts/linux-config-guide/)
[参考文件路径的设置](https://ivonblog.com/posts/linux-fontconfig/)
