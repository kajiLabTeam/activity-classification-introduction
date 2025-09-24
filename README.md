# Activity Classification Introduction
行動分類において基本となる手順およびコードをまとめたリポジトリです．
`walk` `sit` `stop` `others` の4クラス分類を例に `RandomForest` `XGBoost` `LightGBM` の4つのモデルを用いて分類を行います．

## セットアップ
仮想環境の作成
```shell
$ python -m venv .venv
```

仮想環境の有効化
```shell
$ source .venv/bin/activate
```

依存関係のインストール
```shell
$ pip install -r requirements.txt
```

## 流れ
1. [前提](0-prerequisites.md)
2. [前処理](1-preprocess.ipynb)
3. [学習](2-train.ipynb)
4. [評価](3-evaluate.ipynb)
