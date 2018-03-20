---
layout: post
title: 'Initial post! 数学公式测试FIXED'
subtitle: '测试LATEX效果'
date: 2018-03-20
categories: 测试
cover: 'http://on2171g4d.bkt.clouddn.com/jekyll-theme-h2o-postcover.jpg'
tags: LaTeX
---

# 测试博客是否正常运行
## 需要研究下MathJax下面基本的数学公式如何输入
### 分隔符和Katex不一样




a =  $A^2$

B = $C_N$




$$
S_n = \dfrac{a}{b}

\sum_{i=1}^n a_i=0

f(x)=x^{x^x}

\delta = \mathbb{B}


\mathbb{A} ,\mathbb{Z}
$$




$$
\text{显示文本对任意的x>0, 有 f(x)>0.}


\text{分数 :}  \frac{a}{b} 

\text{开平方,开根号 :}  \sqrt{b}

\text{开n次方 :}  \sqrt[n]{c}
$$

### \ldots 表示跟文本底线对齐的省略号；\cdots 表示跟文本中线对齐的省略号，
比如：

$$
f(x_1,x_2,\ldots,x_n)
$$

### 积分运算符（integral operator）用\int 来生成

$$
\int u \frac{dv}{dx}\,dx=uv-\int \frac{du}{dx}v\,dx
$$

### 花括号显示分组情况

$$
P_(r-j)=
 \begin{cases}
  0                    &  \text{表述文字1 }
   \\
  r!\,(-1)^{(r-j)/2}   &  \text{表述文字2 }
  \end{cases}
$$

### 用 \left来表述左括号（ 再用\right来描述右括号）
### 意思是用大括号，对比下面的2个公式效果看，第二个是默认的小括号

$$
f(x,y,z) = 1y^n z  \left( 123 + \frac{666x (i+j)}{1 + y^3} \right)

f(x,y,z) = 2y^n z       ( 123 + \frac{666x (i+j)}{1 + y^3}       )
$$

### \text{ 圆括号表示的矩阵/向量}
### 本质就是用  大号\left 和\right 来显示 对应的小括号
### 指定 竖线，分割线 {cc|c}

$$
\text{ the 3 }\times 3~matrix


\mathbf{X} = \left( 
    \begin{array}{cc|c}
        a_1 & b_1 & c_n \\
        a_2 & e_2 & f_x \\
        a_3 & h_3 & i_n 
    \end{array} 
\right)
$$

### 正常表示的矩阵
### 本质就是用  大号\left 和\right 来显示 对应的竖线！
### 看样子并没有专门的符号来表示 矩阵

$$
\left| 
    \begin{array}{ccc}
        a & b & c \\
        d & \overrightarrow{e} & f \\
        g & h & i 
    \end{array} 
\right|

$$

### 向量箭头表示 \overrightarrow{AB} ， 向量点积\cdot

$$
\overrightarrow{AB}

\overleftarrow{BA}


\vec a\cdot\overrightarrow{AB}
$$

### \neq不等号，不等于符号，Not equal 

$$
a^x+\quad\quad\quad y \neq a^{x+y}
$$

$$
\Gamma(n) = (n-1)!\quad\forall n\in\mathbb N
$$


### 在箭头的上下方写文字

$$
U \xrightarrow[XXX]{\lambda(i)+(j)} W
$$
