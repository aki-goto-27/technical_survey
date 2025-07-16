# 🧠 Transformerに関する技術調査資料

※ChatGPTにまとめさせたReadMeです．

本リポジトリでは、自然言語処理の分野で広く使われている **Transformer** モデルの技術調査・スライド資料（PDF）を掲載しています。  
学習・推論時の動作、Attentionの数式、処理の流れなどを**視覚的かつ初学者向け**に整理しています。

---

## 📌 背景

本資料は、以下を目的として作成したものです：

- Transformerの**数式的な動作理解**
- 自然言語処理モデル（特に翻訳系）における**処理構造の視覚化**
- 従来のRNN/seq2seqとの違いを明確にする
- Self-Attention / Cross-Attention / Multi-Head Attentionなどの**具体的な動作理解**
- 研究やプロジェクトのための**基礎知識の整理**

---

## 📄 スライド内容の構成

1. 従来手法（RNN / seq2seq）の課題
2. Attentionの数理的仕組み
3. Transformerの構造（エンコーダ・デコーダ）
4. Tokenization / Embedding / Positional Encoding
5. Self-Attention・Multi-Head Attention の計算フロー
6. 推論時・学習時の動作
7. 応用事例（GPT, BERT, ViT, DALL·Eなど）

---

## 📎 資料

- `Transforumer.pdf`  
  → Transformerの構造と動作について、図・数式・処理フローを交えて解説したスライド資料です。

---

## 🔍 想定読者

- Transformerの構造を改めて整理したい方
- 自然言語処理を研究・実装し始めた方
- Transformerの中間処理を数式ベースで理解したい方
