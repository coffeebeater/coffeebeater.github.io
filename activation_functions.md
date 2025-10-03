# 活性化関数

## ステップ関数 step function

$$
h(x) = 
  \begin{cases}
  1 & (x > 0) \\
  0 & (else)
  \end{cases}
$$

```python
import numpy as np

(x > 0).astype(np.int)

```
## 標準シグモイド関数 sigmoid function

$$
h(x) = \frac{1}{1 + exp(-x)}
$$

[ロジスティック関数とシグモイド関数 - 北野坂備忘録](https://kenichia.hatenablog.com/entry/2017/03/04/122551)
