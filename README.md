# rust-learning
Rustの学習記録と小さな作品集。学んだこと・実装の工夫・実行方法をまとめる用。

## 開発環境

- Windows / WSL 2 / Ubuntu
- Visual Studio Code
- Rust / Cargo

## 学習内容

### 01. Hello World

CargoでRustプロジェクトを作成し、ビルドと実行を確認しました。

#### 実行方法

リポジトリのルートから、次を実行します。

```bash
cd hello_rust
cargo run
```

#### 実行結果

```text
Hello, world!
```

#### 学んだこと

- `cargo new` でプロジェクトを作成する
- `src/main.rs` にプログラムを書く
- `cargo run` でビルドと実行を行う
- `println!` で文字を表示する

