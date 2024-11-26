github action 上で eslint を実施するデモ

## 想定プロジェクト

- サブディレクトリに frontend,など存在するモノレポ構成(backend も存在する想定だが、デモのため省略)

## デモの流れ

- front ディレクトリの変更を伴う PR に対して lint チェックを実施
- PR に対してコメントで lint エラーを通知する
