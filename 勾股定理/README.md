# 说明

 刘海洋  《Latex入门》 的例子

文件说明:

gougu.tex:  tex源码

math.bib:  参考文献

xiantu.JPG: 插图

只需要上述三个文件， gougu.pdf是最终生成的结果，供参考。

另外，参考文献的引用方式修改为上标引用。


 # 编译方法

 ```
xelatex gougu.tex

bibtex gougu.aux

xelatex gougu.tex

xelatex gougu.tex
 ```

