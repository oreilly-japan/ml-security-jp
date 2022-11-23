# セキュリティエンジニアのための機械学習

---

![表紙](mastering-machine-learning-penetration-testing-ja.png)

---

本リポジトリはオライリー・ジャパン発行書籍『[セキュリティエンジニアのための機械学習](https://www.oreilly.co.jp/books/9784873119076/)』のサポートサイトです。

## リポジトリの構成

各章のノートブックがあります。また、それぞれのノートブックはGoogle Colaboratoryを使いブラウザで実行できます。

- [2章のサンプルコード](https://github.com/oreilly-japan/ml-security-jp/blob/master/ch02/Chapter2.ipynb) / [Google Colabで開く](https://colab.research.google.com/github/oreilly-japan/ml-security-jp/blob/master/ch02/Chapter2.ipynb)

- [2章の課題](https://github.com/oreilly-japan/ml-security-jp/blob/master/ch02/Chapter2_Practice.ipynb) / [Google Colabで開く](https://colab.research.google.com/github/oreilly-japan/ml-security-jp/blob/master/ch02/Chapter2_Practice.ipynb)

- [3章のサンプルコード](https://github.com/oreilly-japan/ml-security-jp/blob/master/ch03/Chapter3.ipynb) / [Google Colabで開く](https://colab.research.google.com/github/oreilly-japan/ml-security-jp/blob/master/ch03/Chapter3.ipynb)

- [3章の課題](https://github.com/oreilly-japan/ml-security-jp/blob/master/ch03/Chapter3_Practice.ipynb) / [Google Colabで開く](https://colab.research.google.com/github/oreilly-japan/ml-security-jp/blob/master/ch03/Chapter3_Practice.ipynb)

- [4章のサンプルコード](https://github.com/oreilly-japan/ml-security-jp/blob/master/ch04/Chapter4.ipynb) / [Google Colabで開く](https://colab.research.google.com/github/oreilly-japan/ml-security-jp/blob/master/ch04/Chapter4.ipynb)

- [4章の課題](https://github.com/oreilly-japan/ml-security-jp/blob/master/ch04/Chapter4_Practice.ipynb) / [Google Colabで開く](https://colab.research.google.com/github/oreilly-japan/ml-security-jp/blob/master/ch04/Chapter4_Practice.ipynb)

- [5章のサンプルコード](https://github.com/oreilly-japan/ml-security-jp/blob/master/ch05/Chapter5.ipynb) / [Google Colabで開く](https://colab.research.google.com/github/oreilly-japan/ml-security-jp/blob/master/ch05/Chapter5.ipynb)

- [5章の課題](https://github.com/oreilly-japan/ml-security-jp/blob/master/ch05/Chapter5_Practice.ipynb) / [Google Colabで開く](https://colab.research.google.com/github/oreilly-japan/ml-security-jp/blob/master/ch05/Chapter5_Practice.ipynb)

- [6章のサンプルコード](https://github.com/oreilly-japan/ml-security-jp/blob/master/ch06/Chapter6.ipynb) / [Google Colabで開く](https://colab.research.google.com/github/oreilly-japan/ml-security-jp/blob/master/ch06/Chapter6.ipynb)

- [6章の課題](https://github.com/oreilly-japan/ml-security-jp/blob/master/ch06/Chapter6_Practice.ipynb) / [Google Colabで開く](https://colab.research.google.com/github/oreilly-japan/ml-security-jp/blob/master/ch06/Chapter6_Practice.ipynb)

- [7章のサンプルコード](https://github.com/oreilly-japan/ml-security-jp/blob/master/ch07/Chapter7.ipynb) / [Google Colabで開く](https://colab.research.google.com/github/oreilly-japan/ml-security-jp/blob/master/ch07/Chapter7.ipynb)

- [7章の課題](https://github.com/oreilly-japan/ml-security-jp/blob/master/ch07/Chapter7_Practice.ipynb) / [Google Colabで開く](https://colab.research.google.com/github/oreilly-japan/ml-security-jp/blob/master/ch07/Chapter7_Practice.ipynb)

- [8章のサンプルコード](https://github.com/oreilly-japan/ml-security-jp/blob/master/ch08/Chapter8.ipynb) / [Google Colabで開く](https://colab.research.google.com/github/oreilly-japan/ml-security-jp/blob/master/ch08/Chapter8.ipynb)

- [9章のサンプルコード](https://github.com/oreilly-japan/ml-security-jp/blob/master/ch09/Chapter9.ipynb) / [Google Colabで開く](https://colab.research.google.com/github/oreilly-japan/ml-security-jp/blob/master/ch09/Chapter9.ipynb)

## 正誤表

下記の誤りがありました。お詫びして訂正いたします。

本ページに掲載されていない誤植など間違いを見つけた方は、japan@oreilly.co.jpまでお知らせください。

### サンプルコードについて
(2022/11/23現在)Google Colabにデフォルトで入っているLightGBMのバージョンが古いため、最新のOptunaが指定している戻り値を認識できなくなり、コードがうまく動作しない事象を確認しております。
恐れ入りますが、サンプルコードのOptunaのインストール時に次のようにバージョン指定をするようお願いいたします。本事象をご指摘いただいたAVTOKYO2022のワークショップ参加者の皆さんに感謝します。

```
!pip install optuna==2.9.0
```

### 第1刷

#### ■2章 P.21 下から7行目
**誤**
```
手動で調整していく方法は、チューニングツールの仕様に比べて
```
**正**
```
手動で調整していく方法は、チューニングツールの使用に比べて
```

#### ■3章 P.52 6行目
**誤**
```
最小値はゼロ（Minimum）、最大値（Minimum）は26、
```
**正**
```
最小値（Minimum）はゼロ、最大値（Maximum）は26、
```


#### ■5章 P.139 1行目
**誤**
```
!pip install pigeonXT-jupyter
```
**正**
```
!pip install pigeonXT-jupyter==0.4.1
```

#### ■7章 P.170 6行目
**誤**
```
SQL構文の文法という一定の規則に基づいた文字列を含むため
```
**正**
```
SQL文と通常のクエリ文字列の両方を含む形となるため
```
