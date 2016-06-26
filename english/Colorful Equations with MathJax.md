# 丰富多彩的mathjax方程

stuart riffle对傅里叶变换给出了一个很好的解释。在他的声明中有很多精彩的直观的东西。但是其中最尖端的内容则是他关于离散傅里叶逆变换公式的解释。

![Mou icon](figure1.png)

多么精彩的陈述。我的第一个想法是，更多的方程式应该有这样优雅的解释来贴近读者的理解。我希望能够以这种风格来给出清晰的解释。

为了发现特定频率下的能量，在该频率下，旋转你的信号围成一个圈，沿着该路径平均地做大量的点。

$$\textcolor{Purple}{X}_\textcolor{Green}{k}
=\textcolor{Magenta}{\frac{1}{N}\sum_{n=0}^{N-1}}
\textcolor{Blue}{x_n}
\textcolor{Red}{e}^
{\textcolor{Red}{i}\textcolor{Orange}{2\pi} 
\textcolor{Green}{k}
\textcolor{Magenta}{\frac{n}{N}}
}.$$

**To find   ,    , and .**

**Remark:**

1.  Html color setting

2.  The raw equation is $$X_k=\frac{1}{N}\sum_{n=0}^{N-1}x_ne^{i2\pi k \frac{n}{N}}.$$

3.  Reference: [Colorful Equations With MathJax](http://adereth.github.io/blog/2013/11/29/colorful-equations/)