---
layout:     post
title:      \( \sqrt{x^2+Δ} \)与\( \sqrt{x^2-Δ} \)，哪一个与x最接近
subtitle:   请仔细阅读
date:       2021-02-27
author:     周可名
header-img: img/post-bg-interview.jpg
catalog:    true
tags:
    - 数学研究
---

\\(\\sqrt \{\{x^2} + \\Delta } \\)，\\(\\sqrt \{\{x^2} - \\Delta } \\)与x的差值大小比较

\\(H = \\sqrt \{\{x^2} + \\Delta } \\)，\\(L = \\sqrt \{\{x^2} - \\Delta } \\).

问题：H与L中，哪个与x更接近(\\(0 \\le \\Delta  \\le {x^2}\\))？①

法一：作差法

将H，L分别与x作差，再将结果作差，得：

\\(\\left( {H - x} \\right) - \\left( {x - L} \\right) = H + L - 2x\\). 

要确定该式的符号，可计算“判别式”J：

\\(J = {\\left( {H + L} \\right)^2} - {\\left( {2x} \\right)^2} = 2\\left( {H \\cdot L - {x^2}} \\right)\\)②.

\\(\\begin{array}{l}J > 0 \\Leftrightarrow H - x > x - L;\\\\J = 0 \\Leftrightarrow H - x = x - L;\\\\J < 0 \\Leftrightarrow H - x < x - L.\\end{array}\\)

1. 当\\(\\Delta  = 0\\)时，\\(J = 0\\)，\\(H - x = x - L\\).

2. 当\\(\\Delta  > 0\\)时，

\\(\\begin{array}{l}\\frac{J}{2} = \\sqrt \{\{x^4} - {\\Delta ^2}}  - {x^2}.\\\\\\because {x^4} - {\\Delta ^2} < {x^4}\\\\\\therefore \\sqrt \{\{x^4} - {\\Delta ^2}}  - {x^2} < 0\\\\\\therefore J = 2(\\sqrt \{\{x^4} - {\\Delta ^2}}  - {x^2}) < 0.\\\\\\therefore H - x < x - L.\\end{array}\\)



法二：利用平方差公式转化

\\(\\begin{array}{l}\\frac{\\Delta }\{\{H - x}} = H + x,\\\\\\frac{\\Delta }\{\{x - L}} = L + x.\\end{array}\\)

当\\(\\Delta  = 0\\)时，\\(H = L\\).

\\(\\therefore H - x = x - L\\).

当\\(\\Delta  > 0\\)时，

\\(\\begin{array}{l}\\because H + x > L + x,\\\\\\therefore \\frac{\\Delta }\{\{H - x}} > \\frac{\\Delta }\{\{x - L}}.\\\\\\therefore H - x < x - L.\\end{array}\\)

法三③：图形法



在两个（大）直角三角形中A，C，B三点共圆，BC为弦；A，B，E三点共圆，BE为弦. 

圆的直径\\[AB\\; < AC\\]，而弦长相等，可证\\(\\alpha  > \\beta \\)，由相似得\\(\\gamma  = \\alpha  > \\beta  = \\theta \\)即\\(\\gamma  > \\theta \\). 

故\\(CG = \\sin \\theta  \\cdot BC\\)，\\(BH = \\sin \\gamma  \\cdot BE\\).

\\(\\begin{array}{l}\\because FC < CG,CG < BH,\\\\\\therefore FC < BH.\\\\\\therefore H - x < x - L.\\end{array}\\)



法四：

设\\(L = \\sqrt \{\{x^2} - \\Delta }  = x - m\\)，\\(H = \\sqrt \{\{x^2} + \\Delta } \\)，\\(N = x + m\\).

\\[\\begin{array}{l}\\therefore {L^2} = {x^2} - \\Delta  = {x^2} - 2mx + {m^2}.\\\\\\therefore \\Delta  = 2mx - {m^2}.\\\\\\because {H^2} = {x^2} + \\Delta  = {L^2} + 2\\Delta  = {x^2} + 2mx - {m^2},\\\\\\therefore H = \\sqrt \\{\\{\\{(x + m)}^2} - 2{m^2}}  < \\sqrt \\{\\{\\{(x + m)}^2}}  = x + m = N.\\\\\\therefore H < N \\Leftrightarrow H - x < N - x.\\\\\\because N - x = m = x - L,\\\\\\therefore H - x < x - L.\\end{array}\\]





法五：函数图像法



观察函数\\(f(x) = \\sqrt x \\)及其导数函数\\[f'(x) = \\frac{1}\{\{2\\sqrt x }}\\]的图像，可知随着x值的增加，\\(\\sqrt x \\)增加趋势放缓. 因此，任意抽取两段连续的x值区间，总是数值较大的区间内函数值\\(\\sqrt x \\)的变化积分量较小，即\\(H - x < x - L\\).







附录：Δ=1，10，50，100时，“判别式”J的图像

