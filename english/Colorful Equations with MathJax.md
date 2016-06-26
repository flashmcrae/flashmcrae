<script type="text/x-mathjax-config">
  MathJax.Hub.Config({ TeX: { extensions: ["color.js"] }});
</script>

<script type="text/javascript" src="http://cdn.mathjax.org/mathjax/latest/MathJax.js?config=TeX-AMS-MML_HTMLorMML"></script>

# 丰富多彩的mathjax方程

Stuart Riffle 对傅里叶变换给出了一个很好的解释。在他的声明中有很多精彩的直观的东西，但是其中最尖端的东西则是他关于离散傅里叶逆变换公式的解释。

![Mou icon](figure1.png)

多么精彩的陈述。我的第一个想法是，更多的方程式应该有这样优雅的解释来贴近读者的理解。我希望能以这种风格来给出清晰的解释：

$$\textcolor{Purple}{X}_\textcolor{Green}{k}
=\textcolor{Magenta}{\frac{1}{N}\sum_{n=0}^{N-1}}
\textcolor{Blue}{x_n}
\textcolor{Red}{e}^
{\textcolor{Red}{i}\textcolor{Orange}{2\pi} 
\textcolor{Green}{k}
\textcolor{Magenta}{\frac{n}{N}}
}.$$
**为了发现 </font> <font color=Green>特定频率下的</font><font color=Purple>能量，</font>  <font color=Green>在此频率下</font> <font color=Orange>围绕一个圆</font> ，<font color=Red>旋转</font> <font color=Blue>你的信号，</font>并且, <font color=Magenta>沿着该路径平均分配一束点</font>.**

**Remark:**

1. Html color setting  
		<font color=Blue>Blue</font> 
		 <font color=Brown>Brown</font> 
		 <font color=Cyan>Cyan</font> 
		 <font color=Green>Green</font> 
		 <font color=Grey>Grey</font> 
		 <font color=Magenta>Magenta</font> 
		 <font color=Orange>Orange</font> 
		 <font color=Yellow>Yellow</font> 
		 <font color=Purple>Purple</font> 
2. The raw equation is $$X_k=\frac{1}{N}\sum_{n=0}^{N-1}x_ne^{i2\pi k \frac{n}{N}}.$$
3. Reference: [Colorful Equations With MathJax](http://adereth.github.io/blog/2013/11/29/colorful-equations/)