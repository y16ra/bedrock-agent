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
