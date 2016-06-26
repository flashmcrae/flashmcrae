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


与机械化翻译公式的结合：在翻译比较长的句子的时候，我们首先要抓住主干，即主谓宾三个重要部分。然后我们将注意力集中到其他修饰成分，如果存在长定语或者长的状语，我们把他们进行整理，然后根据倒序的原则，一一进行翻译，最后与主谓宾结合起来，附加适当的连接词，使得语句通顺，那么我们的翻译就成功了。而为了能够详细清晰地划分句子的各个成分，我们就需要用到色彩标注法，我们可以用不同颜色来标记不同的句子成分，看起来条理清楚，方便我们进行修饰的排序和主干的分析。

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