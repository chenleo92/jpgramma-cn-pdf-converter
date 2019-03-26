# tae-kim_cn_latex_go

一个将[《日语语法指南》](http://res.wokanxing.info/jpgramma/) 转换为pdf的小工具。此工具fork自 Philipp Kerling 写的 [Perl 工具](https://github.com/bobbens/tae-kim_latex)。

## 用法
在安装了tex、golang等环境后，直接运行：
```
make
```
## 其他

```
# 安装texlive
sudo pacman -S texlive-most texlive-langchinese

# 安装字体
sudo pacman -S ttf-linux-libertine adobe-source-han-serif-otc-fonts
```