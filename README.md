# test_jupyter_notebook

## 起動
$ source activate py3k
(py3k) am-no-MacBook-Air:pkgs am$ jupyter notebook

## ノートを作成
Jupyter Notebookをインストール後、ターミナルで

$ jupyter notebook

実行され、現在のディレクトリ上でノートが作成できます。

[New]タブから[Python3]を選択します。

## Tips
### 数式表記
Code -> Markdown
$$
\begin{align}
\sum_{k=1}^{\infty} \frac{1}{k^2} = \frac{\pi^2}{6}
\end{align}
$$

### jupyter notebook 内でのグラフ表示
Code
%matplotlib inline
import matplotlib.pyplot as plt
import numpy as np
x = np.linspace(0, 10, 100)
y  = np.sin(x)
plt.plot(x, y)

## ipynb形式で保存
そのノートの[File]→[Download as]→[Notebook (.ipynb)]へと進むと、Macでしたら勝手にダウンロードされるはずです。

## Github Gistにアップロード
ファイルをGithub Gistにドラッグ＆ドロップしてアップロードし、[Create Public Gist]をクリックします。

