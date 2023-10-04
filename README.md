[![Deploy](https://github.com/Scout-Association-of-Japan/DX-promotion-guidelines/actions/workflows/deploy.yml/badge.svg)](https://github.com/Scout-Association-of-Japan/DX-promotion-guidelines/actions/workflows/deploy.yml)

ボーイスカウト日本連盟が提供するデジタルツール配布プログラムのドキュメントサイト「[デジタルツール利用ガイド](https://scout-association-of-japan.github.io/DX-promotion-guidelines/)」のリポジトリです。

## 貢献の仕方
Issuesにあるタスクや発見した不具合等の修正にご協力ください。  
詳しくは[貢献の仕方](./.github/CONTRIBUTING.md)をご覧ください。

## 環境構築とローカル実行
### 0.前提要求
- Python3系
- Pip

### 1.プロジェクトのクローン
本プロジェクトのリポジトリをローカルにクローンします。

### 2.依存関係のインストール
プロジェクトルートで以下のコマンドを実行します。
```
pip install -r requirements.txt
```

### 3.デバッグ&ビルド
デバッグ（ホットリロード対応）
```
mkdocs serve
```
ビルド
```
mkdocs build
```


## 貢献者一覧
[貢献者一覧](./CONTRIBUTORS.md)をご覧ください。