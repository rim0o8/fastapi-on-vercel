# FastAPI on Vercel

このプロジェクトは、VercelでFastAPIアプリケーションをデプロイする方法を示しています。

[English](README.md) | 日本語

## 特徴

- FastAPIフレームワークを使用した高速なAPIの構築
- Vercelでの簡単なデプロイ
- 自動的なOpenAPI（Swagger）ドキュメントの生成

## 前提条件

- Python 3.9以上
- Vercelアカウント
- Vercel CLI（ローカルテスト用）

## セットアップ方法

1. リポジトリをクローンする

    ```bash
    git clone https://github.com/yourusername/fastapi-on-vercel.git
    cd fastapi-on-vercel
    ```

## Vercelへのデプロイ

1. Vercel CLIをインストールする（オプション）

    ```bash
    npm i -g vercel
    ```

2. Vercelにデプロイする

    Vercel CLIを使用する場合:
    ```bash
    vercel login
    vercel
    ```

    GitHubリポジトリと連携する場合:
    1. GitHubにリポジトリをプッシュ
    2. Vercelダッシュボードでリポジトリをインポート
    3. デプロイ設定を確認して「Deploy」をクリック

## ファイル構成

- **app.py**: FastAPIアプリケーションのエントリーポイント
- **requirements.txt**: プロジェクトの依存関係（fastapi, uvicorn）
- **vercel.json**: Vercelの設定ファイル（ビルド設定とルート設定）
- **.vercelignore**: デプロイから除外するファイル

## 参考資料

- [FastAPI公式ドキュメント](https://fastapi.tiangolo.com/)
- [Vercelのプロジェクト設定](https://vercel.com/docs/project-configuration)
- [VercelのPythonランタイム](https://vercel.com/docs/functions/serverless-functions/runtimes/python) 