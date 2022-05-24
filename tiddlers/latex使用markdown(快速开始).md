- 下载[markdown宏包](https://ctan.org/pkg/markdown)
	- 注意一般发行版的(texlive,miktex)可以直接安装
- 注意编译时使用`lualatex`
- 导言区直接使用包
```latex
\usepackage[option]{markdown}
```
- 文本中直接使用`markdown`环境
```latex
\begin{markdown}
	
\end{markdown}
```
- 可以直接导入**markdown文件**
```latex
\markdownInput={filename.md}
```
- 默认情况下在`markdown`环境中不能使用`latex`语法,需要在导言区把`option`调为混合模式
```latex
\usepackage[option]{markdown}
```