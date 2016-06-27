# Colorful Equations with MathJax

Stuart Riffle wrote up a great explanation of the Fourier transform. There are a number of great visualizations in his post, but the climax is his explanation of the inverse discrete Fourier transform formula:

![Mou icon](figure1.png)

What a brilliant representation! My first thought was that more equations should have such elegant explanations that focus on the comprehension of the reader. I’d love to be able to produce such clear explanations in this style:

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

1.  The raw equation is $$X_k=\frac{1}{N}\sum_{n=0}^{N-1}x_ne^{i2\pi k \frac{n}{N}}.$$
2.  Reference: [Colorful Equations With MathJax](http://adereth.github.io/blog/2013/11/29/colorful-equations/)