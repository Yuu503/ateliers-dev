# ateliers-dev - repository information

このリポジトリは、Docusaurus を使って生成する静的サイトのソースコードと記事を保管しています。旧サイトの公開・自動デプロイは終了しました。

現在の公式サイトは [https://ateliers.dev/](https://ateliers.dev/) です。サイトのソースコードと公開運用は [Ateliers-Dev/ateliers-website](https://github.com/Ateliers-Dev/ateliers-website) で管理しています。このリポジトリの記事やソースは、アーカイブとして保持しています。

## ライセンス

このプロジェクトは [MIT ライセンス](LICENSE) です。  
詳細については、[LICENSE](LICENSE) ファイルをご確認ください。  
  
(This project is licensed under the terms of the [MIT License](LICENSE). See the [LICENSE](LICENSE) file for details. )

## Docusaurus について

Docusaurus は、React と Markdown を使って静的サイトを生成するためのツールです。  
オープンソースで Facebook によって開発されています。

公式サイトは、以下のリンクからアクセスできます。  
[Docusaurus](https://docusaurus.io/)

素晴らしいツールを提供してくれた Facebook に感謝します。

## 開発と動作確認の環境

*<2024/04/23 時点>*  
以下の環境にて、開発と動作確認を行っています。

OS: Windows 11 Pro  
IDE: VS Code  

Node.js: v20.7.0
Docusaurus のバージョンは 3.9.2 です（2025/11/22 時点で最新）。

### 2025/11/22 Docusaurus 最新化作業

- Docusaurus v3.3.2 → v3.9.2 へアップデート
- 公式推奨に従い、設定ファイルの非推奨項目（onBrokenMarkdownLinks）を修正
- ブログ著者情報を authors.yml 参照形式に統一
- 全ブログ記事に <!--truncate--> マーカーを追加
- HTTP技術記事のアンカーリンク修正
- ビルド・動作確認済み

> 注意: 今後 Docusaurus v4 へのアップグレード時は breaking change にご注意ください。

## ブランチについて

このリポジトリでは、以下のブランチを使用しています。

* `master` ブランチ:  
旧サイトのソースコードと記事を保管しています。現在の公式サイトを公開するブランチではありません。
* `feature` ブランチ:  
開発用のブランチです。プラグイン追加や機能修正など、大幅な変更を行う場合は、このブランチで作業してから `master` ブランチにマージします。
* `gh-pages` ブランチ:  
旧サイトの最後の公開ファイルを保管しています。現在は `master` ブランチの更新による自動デプロイを停止しています。

## 貢献について

このプロジェクトにフィードバックや提案がある場合は、GitHubのIssueを通じてお知らせください。  
貢献が予想される場合は、`CONTRIBUTING.md` を追加し、具体的な貢献方法について詳細を記述します。

## 技術的な問題や質問について

このプロジェクトに関する質問やフィードバック、提案があれば、GitHubのIssueを通じてお知らせください。
