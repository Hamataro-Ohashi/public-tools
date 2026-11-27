# public-tools

業務の効率化に使う、汎用の小さなツールをまとめたリポジトリです。
ツールごとにディレクトリを分けて格納しています。

---

## ツール一覧

| ツール | 概要 | ドキュメント |
|--------|------|--------------|
| [multi-url-opener](./multi-url-opener/) | 複数のURLや検索語を、新しいタブでまとめて開きます | [README](./multi-url-opener/README.md) |
| [multi_zip_downloader](./multi_zip_downloader/) | 複数のURLのファイルを、タブを開かずに順番にダウンロードします。Web配布ファイルのダウンロード確認テストに使えます | [README](./multi_zip_downloader/README.md) |

---

## ディレクトリ構成

```
public-tools/
├── README.md                          本書
├── multi-url-opener/
│   ├── README.md                      複数タブ開くツールの説明
│   └── multi-url-opener.html          複数タブ開くツール本体
└── multi_zip_downloader/
    ├── README.md                      複数ZIPダウンロードツールの説明
    └── multi-zip-downloader.html      複数ZIPダウンロードツール本体
```

---

## 使い方

動作環境、事前準備、使い方、注意事項は、ツールごとに違います。
使う前に、各ディレクトリの **README.md** を確認してください。

---

## 共通の注意事項

- 入力したURLやデータは、ツールの外部（各Webサーバや検索エンジンなど）に送られる場合があります。機密情報の扱いに注意してください
