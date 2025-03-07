# 上海海洋大学研究生论文LaTeX模版

该模板参考了往届信息学院毕业生的终稿格式和word版《上海海洋大学研究生学位论文格式排版》，预览请查看`SHOU_LaTeX_thesis_template.pdf`。

**如使用overleaf在线编译，请在Menu中将编译器更换为xelatex。**

**如使用overleaf在线编译，请在Menu中将编译器更换为xelatex。**

**如使用overleaf在线编译，请在Menu中将编译器更换为xelatex。**

本地编译推荐的编译命令为`latexmk -xelatex -synctex=1 main.tex`。
`latexmk`命令的运行需要系统安装有Perl解释器。
可以使用命令`latexmk -C`来删除编译产生的文件，可以使用命令`latexmk -c`来删除编译产生的临时文件。

如果系统提示找不到`.bst`文件的话，需要安装`gbt7714`宏包：
Linux或Mac OS操作系统上的TeXLive的话，在终端输入
``` bash
sudo tlmgr install gbt7714
```
Window操作系统上的TeXLive，在CMD中输入
```
tlmgr install gbt7714
```

字数统计可以使用如下命令:
```
texcount -total  data/*.tex
```

## 改动日志
- 2025.03.07 修改行距，粗体，空格行等
- 2025.03.05 修复了中英文摘要在跨页情况下页眉页脚丢失问题 / 修复了生成文档中西文字体与《上海海洋大学研究生学位论文格式排版》西文字体Times New Roman显示不一致的情况
- 2024.12.14 解决了 bicaption过长导致的不居中对齐问题 / 章节编码问题 / 目录中引言中间空格问题  
- 2024.12.13 init

## 参考资料

- CTeX
- 杭州电子科技大学硕士学位论文模版hduthesis
