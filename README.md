# ecnu-thesis

坑还没有踩完。。。欢迎一起来填坑 rgtjf1 [at] 163 [dot] com

## 踩坑记

1. 毕业论文模板

pdflatex 编译运行，编码问题，用 Notepad++ 改为 UTF8 编码后编译运行。在 Winedit 里编译出现乱码，改为命令行可以。

2. Template_ECNU_jypan_201608

华师大 2016 年模板，直接 ctex 编译报错，ctexset不存在，以下几个尝试：

- miktex 里重装 xecjk，各种错，可能 miktex 版本过于老了
- 安装最新版本 ctex，各种不行，放弃
- 安装 texlive, 命令行编译通过，感动。。修改 winedit 设置，[参考](http://tieba.baidu.com/p/4132469168)， 最后发现 pdflatex 无法运行，赶紧切回 ctex
- 据说 14级 童大神 latex 版本被打回来重改了，改为word吧。

3. BUAAThesis-master
  texlive 可以
  
4. nju-thesis-master
   不知道南大学生怎么用的。。。

## 第一次更新：踩坑记
2018.03.17

准备通过 bibtex 来生成 word 版本的引用，毕业论文需要 GB/T7714-2015 格式:

1. GBT7714-2005-BibTeX-Style
https://github.com/Haixing-Hu/GBT7714-2005-BibTeX-Style

  - 使用
 
  ```
  \bibliographystyle{gbt7714-2005}
  ```

2. GB/T 7714-2015 BibTeX Style
https://github.com/zepinglee/gbt7714-bibtex-style.git


单独把 bst 放到上面的仓库中。。。

没踩坑。。欢迎踩完坑的来补一下~~~


## 参考

1. [华东师大 2016](http://www.latexstudio.net/archives/8789)
