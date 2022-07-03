# BB-heights

主目录下thesis.pdf文件为博士论文。code目录下为论文中所需要的长代码。本论文中使用的计算软件为Magma（也有部分使用SageMath），主要原因是Magama可以计算Abel-Jacobi map.

本论文的主要结果为Introduction中的Theorem 1.1-1.3.

Theorem 1.1是对$\langle\Delta,\Delta\rangle$值域的研究，Theorem 1.2是关于$\langle\Delta,\Delta\rangle$奇异性的一个判别法则。此外，我们还给出了Proposition 2.53中contraction lemma部分的全新证明（见论文53页）。下面重点介绍Theorem 1.3中的计算。

我们计算$射影$平面曲线$$\mathfrak{C}:−X^3Y + X^2Y^2 − XY^2Z + Y^3Z + X^2Z^2 + XZ^3 = 0$$的Gross-Schoen cycle的高度$\langle\Delta,\Delta\rangle$。计算的主要理论依据是Theorem 4.38.
1. 我们在5.1-5.2节证明了该曲线满足使用Theorem 4.38的条件。
2. 我们在5.3-5.4节计算了Theorem 4.38中三项的值（除了$\lambda(\mathfrak{C}_{\mathbb{C}})$）。
3. 根据Remark 2.89, 我们只需计算$\delta$
