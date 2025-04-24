---
marp: true
theme: custom-theme
paginate: true
---

# Marp を始めよう

発表者：あなたの名前

---

## Marp とは？

Marp（Markdown プレゼンテーションエコシステム）は、Markdown を使用して美しいスライドデッキを作成できます。

- Markdown でスライドを作成
- PDF、PPTX、HTML にエクスポート
- テーマとディレクティブでカスタマイズ

---

## 基本的な書式

標準的な Markdown 構文をすべて使用できます：

- **太字テキスト** と *斜体テキスト*
- リスト（順序付きと順序なし）
- [リンク](https://marp.app/)
- `コードスニペット`

```javascript
// シンタックスハイライト付きのコードブロック
function hello() {
  console.log("こんにちは、Marp！");
}
```

---

## 画像

![width:500px](https://marp.app/assets/marp.svg)

`width:500px` のようなディレクティブで画像サイズを制御できます

---

## 背景

<!-- _backgroundColor: #123456 -->
<!-- _color: white -->

ディレクティブを使用してカスタム背景色とテキスト色を設定できます。

---

<!-- _backgroundImage: url('https://source.unsplash.com/random/1280x720/?nature') -->
<!-- _color: white -->

# 背景画像

背景として画像も使用できます！

---

## カラム

<div class="columns">
<div>

### 左カラム

- 項目 1
- 項目 2
- 項目 3

</div>
<div>

### 右カラム

1. 最初のポイント
2. 2番目のポイント
3. 3番目のポイント

</div>
</div>

<style>
.columns {
  display: grid;
  grid-template-columns: repeat(2, minmax(0, 1fr));
  gap: 1rem;
}
</style>

---

# ありがとうございました！

Marp で独自のプレゼンテーションを作成しましょう！
