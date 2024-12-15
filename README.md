# 上海海洋大学研究生论文LaTeX模版

格式要求见《上海海洋大学研究生学位论文格式排版》

推荐的编译命令为`latexmk -xelatex -synctex=1 main.tex`。
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

overleaf使用xelatex编译

字数统计可以使用如下命令:
```
texcount -total  data/*.tex
```
## 参考资料

- CTeX
- 杭州电子科技大学硕士学位论文模版hduthesis


