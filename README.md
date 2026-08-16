# LifeLog

メモ帳・カレンダー・家計簿を1つにまとめた、ローカル完結型のWebアプリです。

**バージョン**: v1.0.0 | **最終更新**: 2026年8月16日

🔗 **公開ページ**: https://debug-mylife.github.io/lifelog/

作成: [debug-mylife](https://github.com/debug-mylife)

---

## 機能

### 📝 メモ帳
- タイトル・本文の作成、編集、削除(自動保存)
- キーワード検索
- 10色のカラーラベルで分類
- カレンダーの特定の日付とメモを紐づけ可能

### 📅 カレンダー
- 月間ページ形式の表示
- 予定の追加・編集・削除、色分け
- メモ・家計簿への相互ジャンプ機能

### 💰 家計簿
- 収入・支出の記録
- 支払い方法(現金・クレジットカード・コード決済・電子マネー・その他)を選んで記録
- 月ごとの収入・支出・収支の自動集計

### 🎨 デザインテーマ
- 2種類の見た目(ノート風/サイバー風)をワンクリックで切り替え可能

### 共通機能
- メモ・カレンダー・家計簿を個別に選んでエクスポート/インポート(JSON形式)
- スマートフォンのホーム画面に追加してアプリのように利用可能

---

## データの保存について

このアプリはサーバーを持たない、完全にローカル完結型の設計です。入力したデータはすべて、閲覧しているブラウザの中(localStorage)だけに保存されます。外部のサーバーに送信されることは一切ありません。

そのため、PCとスマートフォンなど、異なる端末・ブラウザ間でデータは自動的に同期されません。端末をまたいでデータを使いたい場合は、エクスポート/インポート機能を利用してください。

---

## 使用技術

- HTML / CSS / JavaScript(素のJavaScript、フレームワーク不使用)
- 単一のHTMLファイルで完結する構成
- フォント:- フォント: [Fraunces](https://fonts.google.com/specimen/Fraunces)、[Zen Kaku Gothic New](https://fonts.google.com/specimen/Zen+Kaku+Gothic+New)、[IBM Plex Mono](https://fonts.google.com/specimen/IBM+Plex+Mono)、[Orbitron](https://fonts.google.com/specimen/Orbitron)、[JetBrains Mono](https://fonts.google.com/specimen/JetBrains+Mono)(いずれもSIL Open Font License)

---

## 制作について

企画・設計・機能追加・不具合修正・公開まで、Claude(Anthropic社のAI)と協働しながら制作しました。コードの実装はAIの支援を受けていますが、アプリの構成・機能・デザインの方向性は自分で企画・判断しています。
