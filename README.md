# python-develop-template
VSCodeのDevcontainerを使って、Pythonローカル開発用テンプレート

## プロジェクトの概要

このテンプレートは、Pythonのローカル開発を始めるためのスターターキットです。

最小限の構成で、すぐに開発を始められるように設計されています。

VSCode Dev Container を利用した開発環境を構築します。

`uv` パッケージマネージャーを利用した環境構築、Jupyter Notebook の利用をサポートしています。

## セットアップ手順

1.  リポジトリをクローンします。
    ```bash
    git clone <repository_url>
    ```
2.  [Devcontainer](https://code.visualstudio.com/docs/devcontainers/containers)を起動します。


## Pythonファイルの実行方法

### .pyを実行する時に、`uv run xxx.py`

例）

```bash
uv run samples/main.py
```

### JupyterNotebook

JupyterLabの利用

```bash
uv run --with jupyter jupyter lab
```
もしくはそのままVSCodeでjupyerを利用する

参考：[Using Jupyter from VS Code](https://docs.astral.sh/uv/guides/integration/jupyter/#using-jupyter-from-vscode)

## UVの利用方法

[Running scripts](https://docs.astral.sh/uv/guides/scripts/)





