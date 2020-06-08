# Problem Set 0 🌟

## 第一题

### 关于梯度和Hessians矩阵

#### (a)$ f(x) = \frac{1}{2}x^TAx+b^Tx$ ,求$f(x)$的梯度

​			$\nabla f(x)=Ax+b$

####  (b) 梯度的链式关系

​			$\nabla [g(h(x))] = g'(h(x))\nabla h(x)$

####  (c) 二次型的Hessians矩阵

​			$\nabla ^2f(x) = A$

#### (d) 梯度的链式关系

​			$\nabla f(x)=g'(a^Tx)a$

​			$\nabla ^2f(x) = g''(a^Tx)A$

## 第二题

### 关于正定半正定矩阵

- 正定矩阵A：任意x!=0,有$,x^TAx>0$即$A\succ0$
- 半正定A：任意x有$x^TAx\geq0$即A$\succeq0$

#### (a) pass

#### (b) 

N(A) = {[0,0,...0]}

r(A) = 1

#### (c) 半正定矩阵的衍生性质

当$A\succeq0$，B属于任意矩阵（维度要对）,则$BAB^T\succeq0$

## 第三题

### 特征根和谱分解相关

#### （a)

​	如果方阵A可对角化，$A=T\Lambda T^{-1}$

​	则T的列向量对应$\Lambda$的对角元素构成特征向量和特征值

#### （b)

​	与(a)类似

#### （c)

​	A是PSD，则A实对称，则A可谱分解，然后利用PSD性质取不同的X即可依次证明A的$\lambda_i>0$

























