# 職務経歴書

## 基本情報

|key|value|
|---|-----|
|名前|原山 拓也|
|Github|[harayama-developmer](https://github.com/harayama-developmer)|
|個人ブログ|[toaru-kaihatsu.com](https://toaru-kaihatsu.com/)|
|Qiita|[@harayama2](https://qiita.com/harayama2)|
|Twitter|[@harayama22](https://twitter.com/harayama22)|

## プロフィール概要
- Ruby on Railsを使ったWebアプリケーション開発、運用が現在の専門です。
- 小規模〜中規模サービスの新規開発フェーズにおいてバリューを発揮できるタイプです。設計段階からサービスの全体像を把握して、類似サービスの調査、ワイヤーフレームの作成なども可能です。
- 主に担当する領域はバックエンドですが、デザインやフロントエンドに関しても常に改善点を見つけるようにしており、必要なら自分で手を動かすこともあります。
- 少数チームのマネジメント経験もあり、アジャイルの導入、ベロシティの管理、スクラムイベントの運用、大きなユーザーストーリーの分割、などの運用経験もあります。

## スキル

使用経験のあるものを記載しています。

### 言語
- Ruby
- PHP
- JavaScript

### フレームワーク等
- Ruby on Rails
- Vue.js
- Nuxt.js

### RDB/NoSQL
- MySQL
- PostgreSQL
- Redis

### クラウド

#### AWS
VPC | S3 | CloudFront | Amplify | ALB | EC2 | ECS | Fargate | ACM | Route53 | IAM | RDS | ElastiCache | CloudWatch | AWS Organizations

#### GCP
GCS | Cloud Functions | GAE | BigQuery | Firebase

### SaaS/PaaS
Github | Github Actions | CircleCI | Sentry | NewRelic | Twilio | Imgix | Sendgrid | Heroku | Cloudflare

### ツール系/その他
Terraform | Docker | nginx | Capistrano | GoogleMap | Geocoding | Slack | Microsoft Teams | JIRA | Confluence | Backlog | Trello | Clickup

## 強み
- 1人〜少数での開発
- 基盤コード開発、テンプレート開発
- Github ActionsなどのCI導入
- デプロイの自動化
- 類似サービス調査や機能の提案
- 開発フローの提案、構築

## 職務経歴

### 法人向け求人管理サービスの開発(2021年 - 現在)
#### 使用技術: Rails/Nuxt.js/Fargate/Amplify/Terraform/AWS
#### ポジション: 開発リーダー
#### プロジェクト概要
開発リーダーとして新規求人管理サービスの開発、外部ベンダー作成のアプリケーションとのAPI連携の設計・実装などを担当。

- バックエンドを中心にRailsでOpenAPI(Swagger)によるAPIを開発。フロントエンドの開発用にMockが動作するようdocker-composeの導入を担当。
- Fargateおよび周辺技術の調査。また、AWS CodePipelineを用いた自動デプロイの調査を実施。マネジメントコンソールでの設定。
- Github ActionsによるCI/CDパイプラインの構築。開発関係者向けにtblsを使ったDB定義書を自動作成する仕組みも構築。
- ECS Execを使ったコンテナログインによる運用。
- 外部アプリケーションとのデータ同期の仕組みの実装。
- Twilio Conversation APIを使ったリアルタイムメッセージ機能の実装。
- AWS IAMのスイッチロールを用いて、dev/stg/prdなど複数環境の切り替えの仕組みを構築。
- 2~4名程度のチームにおいて、スクラムマスター的なことも担当。

### 採用サイト作成SaaSサービスの開発(2019年 - 2020年)
#### 使用技術: Rails/Vue.js/Nuxt.js/Heroku/GAE/GCP
#### ポジション: 開発エンジニア
#### プロジェクト概要
自社サービスとして採用サイト作成サービスの開発を担当。

- バックエンドを中心にRailsでAPIの開発、Webpackerに使ってRailsアプリケーション内にVue.jsの導入、Heroku周りを担当。
- Github ActionsによるCI/CDパイプラインの構築。
- ステークホルダーと直接コミュニケーションをとりながら、要件定義を実施。様々な機能を実装。
- 請求書払いができる決済APIを使用。決済APIの定期決済の仕様がサービス要件と合わなかったため、独自のフローを実装。

上記以外にも、コワーキング向け会員管理システムの構築、不動産向けCMSの構築などの小〜中規模の開発経験があります。

### その他の業務

#### メンター業務

- プログラミングスクールのメンター業務を担当。
- Rails、AWSを中心に受講生の学習支援を実施。
- 答えをすぐ教えるのではなく、答えに辿り着けるような着眼点や調べ方、問題解決能力を教えるよう意識して対応。
