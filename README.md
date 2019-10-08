Sphinx で PDF 文書を書くためのテンプレート

### 環境

とりあえず動くよーな環境要件

+ TeX Live 2017
+ Pyhon 3.7

### 使い方

#### pip install

```
pip install -r requirements.txt
```

#### pdf build

```
cd document
make latexpdf
```

うまく動けば, `document/_build/_build/latex/report.pdf` が出力される...

### 書類の設定変更

`document/conf.py` で latex のプリアンブルを書ける.
