# nazokake - なぞかけ練習プラグイン for Claude Code

なぞかけ（Japanese wordplay riddles）の練習ができる Claude Code プラグインです。

## 機能

### `/nazokake` - 練習セッション
- お題を出題し、ユーザーが「その心」を考える
- ヒントを段階的に提示
- 答え合わせと練習記録の自動保存
- なぞかけの作り方も教えてくれる

### `/nazokake-add` - コレクション追加
- ネットからうまいなぞかけを検索・収集
- テーマを指定して絞り込み可能

## インストール

Claude Code で以下のコマンドを実行してください。

```
/plugin marketplace add bsj-t-akamatsu/nazokake-plugin
/plugin install nazokake
```

## なぞかけとは？

「AとかけてBととく。その心は？」の形式で、AとBに共通する言葉（同音異義語）を見つける日本語の言葉遊びです。

**例**: 「寿司とかけて名曲ととく。その心は、どちらもサビに涙する」
- 寿司のサビ = わさび
- 名曲のサビ = 楽曲のクライマックス部分

## ライセンス

MIT
