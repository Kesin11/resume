# 職務経歴書

## 基本情報

|key|value|
|---|---|
|氏名|加瀬健太（Kenta Kase）|
|生年月日|1989/06/01|
|居住地|東京|
|Twitter|[@Kesin11](https://twitter.com/Kesin11)|
|Zenn|[@Kesin11](https://twitter.com/Kesin11)|
|Qiita|[@Kesin11](https://twitter.com/Kesin11)|
|個人ブログ|[kesin.hatenablog.com](https://kesin.hatenablog.com/)|
|SpeakerDeck|[Kesin11](https://speakerdeck.com/Kesin11)|

---

## 保有スキル
- バックエンド、フロントエンドを問わずCI/CDやビルドパイプラインの整備
- CIOps、GitOps等を活用したソフトウェア開発の自動化・省力化
- 自動テストの設計、構築
- 大規模なリポジトリにおける効率的なGit運用
- GCPを活用した開発

---

## 技術スタック
- CircleCI, Github Actions, Bitrise, Jenkins, Cloud Build
- GCP（特にGCE、GCS、GKE、BigQuery、DataPortal）
- Git
- Terraform
- Ansible
- Docker、k8s
- Android、iOSビルド（特にiOSの証明書周り）
- TypeScript
- Ruby

---

## 職務経歴
### 株式会社ディー・エヌ・エー

#### 社内向けCI/CD基盤の運用（2021/04 - 現在）
CIのSaaSであるCircleCIのエンタープライズ向けであるCircleCI Serverの構築・運用メンバーとして参加。社内のエンジニアが利用しやすいCI/CD環境を提供している。

- 役割
  - 社内向けCI/CD基盤サポートチームのメンバー（メンバー2名）
- 担当業務
  - AWS上に構築されるCircleCI Serverの運用
  - Terraformを利用したEC2やEKSなどのインフラ構築
  - TypeScriptによるオートスケーリングやユーザー管理などの各種運用スクリプトを作成
  - CircleCIの効率的な利用方法の社内サポート、ドキュメント作成

#### 大規模なモバイルゲーム開発におけるCI/CD基盤の設計・開発（2019/04 - 現在）
Unityを使用したモバイルゲーム開発におけるCI/CDの基盤となるJenkinsクラスタをクラウド上に構築。大規模開発でありながら安定したビルド環境を実現し、また2021年のコロナ禍やオフィス移転に際してもクラウドの利点を生かして業務への影響を最小限に留めた。

- 役割
  - CI/CDチームのリーダー（メンバー3-4名）
- 担当業務
  - ゲーム開発チームと共同でモバイルゲーム開発用のJenkinsクラスタ設計・構築・運用
  - Terraformを利用したGCP上のインフラ構築
  - Ansibleを利用したJenkins、ビルドマシン（Linux, macOS）のプロビジョニング
  - Unityゲームのビルドパイプラインの構築
  - 大規模リポジトリにおけるGit, Git LFSの効率的な使い方の調査・啓蒙活動
- 対外活動
  - [モバイルゲーム開発におけるJenkinsクラウド時代のJenkins構築と管理テクニック　CEDEC2020](https://speakerdeck.com/dena_tech/mohairukemukai-fa-niokerujenkinskurautoshi-dai-falsejenkinsgou-zhu-toguan-li-tekunituku)
  - [大きなGitリポジトリをクローンするときの工夫を図解します](https://swet.dena.com/entry/2021/07/12/120000)（同チームメンバーによる記事。自身はレビューを担当）

#### QAチーム業務支援のツール調査・システム開発（2017/10 - 2019/03）
ゲーム開発の傍らでテストやJenkinsによる自動化に興味を持っていたためSWET(Software Engineer in Test）グループに社内異動。

SeleniumやAppiumといったWeb/モバイルのE2Eテスト技術の調査、QAチーム用のバグチケット分析基盤の構築、ストア提出後のアプリがリジェクトされる可能性を機械的に検出するツールを開発。

- 役割
  - QAサポートチームのリーダー(メンバー3名）
- 担当業務
  - QA現場へのヒアリングと内製ツールの仕様策定
  - ストア提出後のiOS/Androidアプリがリジェクトされる可能性を機械的に検出するツールをRubyで開発
  - QAチーム用のバグチケット分析基盤をBigQueryとDataPortalで構築
  - iOS/AndroidのE2Eテスト基盤となるデバイスファームサービスの調査
- 対外活動
  - [ゼロ円から始めるクラウドの実機を使った自動テスト（iOS）](https://swet.dena.com/entry/2018/12/02/000000)
  - [iOSアプリのリジェクトリスクを早期に発見するための取り組み iOSDC Japan 2019](https://speakerdeck.com/kesin11/iosapurifalseriziekutorisukuwozao-qi-nifa-jian-surutamefalsequ-rizu-mi)

#### ブラウザソーシャルゲーム開発（2014/08 - 2017/09）
ブラウザのソーシャルゲームタイトルのエンジニアとして、毎月のイベントや季節のキャンペーン施策、新規ゲームモードの開発。プログラミングだけではなく、プランナーと共にゲームの仕様決めやパラメータ設計、KPI分析、ゲーム画面の設計なども経験。

- 役割
  - サーバーサイドエンジニア
- 担当業務
  - Perlによるゲームサーバー、バッチ処理実装
  - 大規模ユーザーを抱えるMySQLのテーブル、インデックス設計
  - Jenkins運用

## 業務外活動
### OSS・個人開発
|Repo|Stars|Forks|
|----|----|-----|
|[CIAnalyzer](https://github.com/Kesin11/CIAnalyzer)|![GitHub Repo stars](https://img.shields.io/github/stars/Kesin11/CIAnalyzer?style=social)|![GitHub forks](https://img.shields.io/github/forks/Kesin11/CIAnalyzer?style=social)|
|[danger-textlint](https://github.com/Kesin11/danger-textlint)|![GitHub Repo stars](https://img.shields.io/github/stars/Kesin11/danger-textlint?style=social)|![GitHub forks](https://img.shields.io/github/forks/Kesin11/danger-textlint?style=social)|
|[ts-junit2json](https://github.com/Kesin11/ts-junit2json)|![GitHub Repo stars](https://img.shields.io/github/stars/Kesin11/ts-junit2json?style=social)|![GitHub forks](https://img.shields.io/github/forks/Kesin11/ts-junit2json?style=social)|
|[Firestore-simple(Archived)](https://github.com/Kesin11/Firestore-simple)|![GitHub Repo stars](https://img.shields.io/github/stars/Kesin11/Firestore-simple?style=social)|![GitHub forks](https://img.shields.io/github/forks/Kesin11/Firestore-simple?style=social)|

### 技術記事
- [GitHub Actionsの手動実行パラメータのUI改善について速報で解説する](https://zenn.dev/kesin11/articles/13ca0f40e1eaa0)
- [CI/CDのデータを収集するCIAnalyzerの紹介](https://zenn.dev/kesin11/articles/cf08579949b8b0)
- [Bazelの解説（TS, Dockerイメージ、リモートキャッシュ）](https://zenn.dev/kesin11/books/c86010deb5b8008f394f)
- [v7をリリースしたので改めてfirestore-simpleを紹介します](https://kesin.hatenablog.com/entry/2020/04/27/150000)
- [Firebase Emulator Suiteをフル活用してTDDで開発しよう](https://qiita.com/Kesin11/items/43bbc06524aa31c1fd2c)

### 勉強会登壇
- [CI/CDのボトルネックを把握できていますか？BigQueryでビルド情報ダッシュボードを構築した話 CI/CD Conference 2021](https://speakerdeck.com/kesin11/cdfalsebotorunetukuwoba-wo-dekiteimasuka-bigquerydebirudoqing-bao-datusiyubodowogou-zhu-sitahua)
- [TypeScriptから使いやすいFirestore-simpleを紹介します(2020年版) Firebase Realtime Meetup](https://speakerdeck.com/kesin11/typescriptkarashi-iyasuifirestore-simplewoshao-jie-simasu-2020nian-ban)
- [GitHub Actionsが他のCIサービスと比較してできることできないこと GitHub Actions Meetup Tokyo β](https://speakerdeck.com/kesin11/github-actionsgata-falsecisabisutobi-jiao-sitedekirukotodekinaikoto)
