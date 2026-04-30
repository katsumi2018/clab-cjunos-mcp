## 概要

containerlab 上に cJunosEvolved と各種コンポーネントを構築し、  
Junos MCP サーバを使ってネットワーク機器の状態を  
自然言語で確認するサンプルです。

詳細は以下の記事を参照してください。  
https://qiita.com/k-maki/items/b183efb4596594d680c1

OSPFのネイバー状態を自然言語で聞いたときの例
<img width="660" height="211" alt="image" src="https://github.com/user-attachments/assets/6eceea1c-78e2-49fe-9e49-266c84f88010" />


---

## 内容

- containerlab で検証環境を構築
- Junos MCP Server をデプロイ
- Open WebUI + LLM（Gemini）と連携
- 自然言語で Juniper ルータの状態を取得（IF / OSPF など）

---

## 構成
<img width="1149" height="437" alt="image" src="https://github.com/user-attachments/assets/ce488892-9f56-402c-b11d-e1263db990ae" />


---

## ポイント

- showコマンド不要で状態確認が可能
- MCP経由でルータから情報取得
- LLMが自然言語をクエリに変換して実行
