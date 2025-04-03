# python-develop-template
Pythonローカル開発用テンプレート

## プロジェクトの概要

このテンプレートは、Pythonのローカル開発を始めるためのスターターキットです。
最小限の構成で、すぐに開発を始められるように設計されています。
VSCode Dev Container を利用した開発環境を構築します。
`uv` パッケージマネージャーを利用した環境構築、Jupyter Notebook の利用をサポートしています。

## セットアップ手順

1.  リポジトリをクローンします。
    ```bash
    git clone <repository_url>
    cd <repository_name>
    ```
2.  Devcontainerを起動します。


## 実行方法

`main.py` を実行するには、以下のコマンドを使用します。

```bash
uv run main.py
```

## Jupyter Notebookの利用

```sh
Create a project.
uv init project

Move into the project directory.
cd project

Add ipykernel as a dev dependency.
uv add --dev ipykernel

Open the project in VS Code.
code .
```
参考：[Using Jupyter from VS Code](https://docs.astral.sh/uv/guides/integration/jupyter/#using-jupyter-from-vscode)

## UVの利用方法

[Running scripts](https://docs.astral.sh/uv/guides/scripts/)


## ディレクトリ構造

*   `.devcontainer`: VS Code Dev Containers の設定ファイルが含まれています。この設定を使用すると、Docker コンテナ内で開発環境を構築できます。
*   `.venv`: `uv venv` で作成された仮想環境です。
*   `docker-compose.yaml`: Docker Compose を使用して、開発環境を構築するための設定ファイルです。
*   `Dockerfile`: Docker イメージを構築するための定義ファイルです。
*   `main.py`: プログラムのエントリーポイントとなるPythonスクリプトです。
*   `README.md`: プロジェクトの概要やセットアップ手順などを記述したドキュメントです。
*   `pyproject.toml`: プロジェクトのメタデータ、依存関係、ビルド設定などが記述されています。




