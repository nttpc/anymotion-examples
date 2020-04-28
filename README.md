# AnyMotion Examples

このリポジトリには、[AnyMotion](https://anymotion.nttpc.co.jp/)を利用して動作解析を実行する方法を示すサンプルコードやノートブックが含まれています。
Pythonのコードには、[AnyMotion Python SDK](https://github.com/nttpc/anymotion-python-sdk)を利用しています。

## Contents

- [画像にキーポイントを描画する](notebooks/画像にキーポイントを描画する.ipynb)
- [描画ルールを利用して描画する](notebooks/描画ルールを利用して描画する.ipynb)

## Installation

[pip](https://pip.pypa.io/en/stable/quickstart/)または[poetry](https://python-poetry.org/)を利用してライブラリをインストールします。

```sh
pip install -r requirements.txt
```

or

```sh
poetry install
```

## Run jupyter

Jupyteを起動してノートブックを開きます。
また、実行するためには、[AnyMotion Portal](https://portal.anymotion.jp/)から取得できる認証情報が必要になります。

```sh
jupyter notebook
```

or

```sh
jupyter lab
```
