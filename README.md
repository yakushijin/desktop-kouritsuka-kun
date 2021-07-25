# デスクトップ効率化君

`ベータ版`

## 概要

- ubuntu 向け作業効率化ソフト

## 機能

- クリップボードの履歴管理
- ショートカットリンク管理
- 定型文管理

## インストール方法

1. インストーラ作成

   ```sh
   git clone https://github.com/yakushijin/desktop-kouritsuka-kun.git && cd desktop-kouritsuka-kun
   npm install && npm run build
   npm run linux
   ls dist
   ```

1. dist ディレクトリ配下に作成された deb ファイルを開きインストール

1. タスクトレイにアプリのアイコンが表示される

## 使い方

※現時点ではショートカットキーは固定

| ショートカットキー | 実行アクション               |
| ------------------ | ---------------------------- |
| Ctrl + Alt + Z     | クリップボード履歴表示       |
| Ctrl + Alt + X     | ショートカットリンク管理表示 |
| Ctrl + Alt + C     | 定型文管理表示               |
