# bedrock-agent

Amazon Bedrock Agentのフロントエンド。

以下の記事を参考に作成しました。
https://aws.amazon.com/jp/builders-flash/202503/create-ai-advisor-with-bedrock/

## 設定

.envファイルに環境変数を設定してください。

```
AGENT_ID="dummy-agent-id"
AGENT_ALIAS_ID="dummy-alias-id"
```

## 開発環境のセットアップ（uv利用）

uv を使った仮想環境の作成・パッケージインストール手順です。

1. uv のインストール（未インストールの場合）
   ```sh
   brew install uv
   # または
   pipx install uv
   ```

2. 仮想環境の作成
   ```sh
   uv venv
   ```

3. 仮想環境の有効化
   ```sh
   source .venv/bin/activate
   ```

4. 依存パッケージのインストール
   ```sh
   uv pip install -r requirements.txt
   ```

5. アプリの実行
   ```sh
   streamlit run frontend.py
   ```

## 実行

```
pip install -r requirements.txt
streamlit run frontend.py
```

## ディレクトリ構造

```
bedrock-agent/
├── frontend.py
├── requirements.txt
└── .env
```
