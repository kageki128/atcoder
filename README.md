# AtCoder by Rust

## 環境

- Rust toolchain
- cargo-compete
- online-judge-tools
- pipx

## 手順

例: `abc421` を始める場合

1. コンテスト用フォルダを作成して移動
    - `cargo compete new abc421 --open`
    - `cd abc421`
2. コードを書く
3. サンプルテストを実行
    - `cargo compete test`
4. 提出
    - `cargo compete submit`

## 主なコマンド

- コンテスト作成: `cargo compete new abc421 --open`
- 問題ページを開く: `cargo compete open`
- サンプルテスト実行: `cargo compete test`
- テストケース再取得: `cargo compete retrieve testcases`
- 提出: `cargo compete submit`
- AtCoder にログイン: `cargo compete login atcoder`