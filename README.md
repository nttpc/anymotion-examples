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

## Preparation

実行するためには、[AnyMotion Portal](https://portal.anymotion.jp/)から取得できる認証情報が必要になります。以下のように環境変数に設定することができます。

```sh
export ANYMOTION_CLIENT_ID=<your_client_id>
export ANYMOTION_CLIENT_SECRET=<your_client_secret>
```

## Run jupyter

Jupyterを起動してノートブックを開きます。

```sh
jupyter notebook
```

or

```sh
jupyter lab
```

## Using Docker

```sh
docker compose up -d
```
