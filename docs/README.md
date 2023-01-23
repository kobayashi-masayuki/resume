# 職務経歴書

## 基本情報

| key      | value                                       |
| -------- | ------------------------------------------- |
| 氏名     | 小林　正幸（Kobayashi Masayuki）            |
| 生年月日 | 1992/8/3                                    |
| 居住地   | 東京都                                      |
| 最終学歴 | 大阪大学 大学院ビジネスエンジニアリング専攻 |

---

## 各種アカウント

<p>
<a href="https：//github.com/kobayashi-masayuki" target="_blank"><img alt="Github" src="https：//img.shields.io/badge/kawamataryo-%2312100E.svg?&style=flat-square&logo=Github&logoColor=white" /></a>
<a href="https：//qiita.com/kobayashi-masayuki" target="_blank"><img alt="Medium" src="https：//img.shields.io/badge/ryo2132-55C500.svg?&style=flat-square&logo=qiita&logoColor=white" /></a>
</p>

---

## 保有スキル、経験

- 3 年以上の Web API などのバックエンド開発経験
- MySQL/PostgreSQL/DyanmoDB などのデータベース経験
- pytest、unittest 等のテストフレームワーク経験
- スケーラビリティを考慮したアプリケーションの設計経験、負荷対策を行った経験
- Web アプリケーション開発経験（バックエンド、フロントエンド）
- アプリケーションの国際化対応経験（i18n）
- 要件定義、基本設計、アーキテクチャ設計、API 設計、データベーススキーマ設計、アルゴリズム設計
- 細部まで考慮した設計及び実装能力
- プロジェクト計画策定と実施、変更管理などのプロジェクトマネジメント能力
- 運用開始後の運用管理及びメンテナンスと障害対応
- クラウドサービス（AWS/GCP/）を利用したサービス運用/開発経験とセキュリティ知識
- 仕様書、設計書等の技術ドキュメントの記述
- IoT、組み込みシステム開発・設計とデバイス選定経験
- 勉強会、社内学習のコミュニティ形成

---

## 技術スタック

### 言語

<p>
  <img alt="Python" src="https：//img.shields.io/badge/-Python-3776AB?style=flat-square&logo=Python&logoColor=white" />
  <img alt="JavaScript" src="https：//img.shields.io/badge/-JavaScript-F7DF1E?style=flat-square&logo=JavaScript&logoColor=white" />
  <img alt="C++" src="https：//img.shields.io/badge/-C++-00599C?style=flat-square&logo=C%2B%2B&logoColor=white" />
  <img alt="Java" src="https：//img.shields.io/badge/-Java-007396?style=flat-square&logo=Java&logoColor=white" />
  <img alt="Ruby" src="https：//img.shields.io/badge/-Ruby-CC342D?style=flat-square&logo=Ruby&logoColor=white" />
  <img alt="PHP" src="https：//img.shields.io/badge/-PHP-777BB4?style=flat-square&logo=PHP&logoColor=white" />
</p>

### フレームワーク・その他

<p>
  <img alt="Flask" src="https：//img.shields.io/badge/-Flask-000000?style=flat-square&logo=Flask&logoColor=white" />
  <img alt="FastAPI" src="https：//img.shields.io/badge/-FastAPI-009688?style=flat-square&logo=FastAPI&logoColor=white" />
  <img alt="Node.js" src="https：//img.shields.io/badge/-Node.js-339933?style=flat-square&logo=Node.js&logoColor=white" />
  <img alt="Docker" src="https：//img.shields.io/badge/-Docker-46a2f1?style=flat-square&logo=docker&logoColor=white" />
  <img alt="Vue" src="https：//img.shields.io/badge/-Vue.js-4FC08D?style=flat-square&logo=Vue.js&logoColor=white" />
  <img alt="Laravel" src="https：//img.shields.io/badge/-Laravel-FF2D20?style=flat-square&logo=Laravel&logoColor=white" />  
  <img alt="Ruby-on-Rails" src="https：//img.shields.io/badge/-Rails-CC0000?style=flat-square&logo=Ruby-on-Rails&logoColor=white" />

## 職務経歴詳細

### エネルギーベンチャー起業（2022/05〜現在）

- EV 充電インフラシステム開発に従事。システムは、仕様調査からインフラを含めた技術選定、実装、運用まで携わり、リリースに貢献した
- また、組み込みの充電制御システム開発に参画し、企画、プロトタイプの回路の部品選定からコード実装まで行った
- 顧客の課題分析や技術的な解決策の提示、PoC、継続的な技術学習、社内エンジニアの教育、ビジネスサイドとエンジニアサイドの橋渡し、ハードウェアエンジニアとソフトウェアエンジニアの橋渡しなどを行い、本プロジェクトにおける IoT ソフトウェア開発のリーダーを担当している

- **プロジェクト規模：**
  - 平均 2〜4 人チームでのアジャイル開発
- **プロジェクト概要：**
  - プロトコル仕様に準拠したクラウドベースの IoT システム開発
  - アーキテクチャ設計、開発、テスト、運用
  - 新規機能開発やサービス改善のためのデバイスの選定から実装
  - 制御デバイスのファームウェア開発・OTA
- **技術スキル**
  - 言語： Python v3.9、Arduino（C/C++）
    - OCPP ライブラリに合わせて Python 言語を選択した
  - フレークワーク： FastAPI v0.78（充電器の管理システム）、Flask v2.2（デバイス内部の管理画面）
    - API 機能だけが必要な充電器の管理システムには、高速で高い拡張性を持つ FastAPI を採用した
    - デバイス内部の管理画面には、軽量な Flask を採用した
  - Web サーバ： nginx v1.2
  - Python Packages： pytest v7.1、ocpp v0.15（OCPP 1.6)、uvicorn v0.17, sqlalchecmy v1.4、websockets v10
    - 限られた開発期間の中でリリースまでこぎつけるため、更新頻度が高い Python の OCPP ライブラリを使用し、使用する充電器の対応バージョンに合わせて OCPP 1.6 に準拠したプロトコルを実装した
  - データベース： PostgreSQL v13
  - CI/CD： GitHub Actions
  - ハードウェア： Raspberry Pi 2W、ESP32 DEVKIT V1、環境センサー、電力計、ブレーカー、リレー
    - 入手性やコスト、スペックを考慮し、IoT デバイスを選択した
    - Raspberry Pi 2W の確保のため、正規代理店の調査および交渉を行った
  - 無線通信： LTE、Wi-Fi、RFID
  - バグ監視： Bugsnag（Slack 連携）
  - ソース管理： GitHub
  - インフラ： AWS（ECS on Fargate、RDS、Route53、CloudWatch）、SORACOM（IoT SIM）
    - 管理しなければいけない項目が少なく管理が楽な Fargate を採用した
    - SIM には通信から分析、可視化、その他多くの課題を解決できる IoT プラットフォームの SORACOM を採用した
  - コミュニケーションツール： Slack、Zoom、Google Meet
  - タスク管理： Asana
  - その他： Docker v20、docker-compose v2.13、 Wireshark（パケット解析）
- ## **ソフトスキル**
  - 課題や調査報告の際、第 3 者が一目で状況を把握できるように構成を考えて丁寧な資料作成を心がけ、課題と解決策を提案するようにしている
  - IoT の知識を深めるために、IoT の書籍や記事を参考にしたり、勉強会に参加して、IoT の知識アップデートを行っている
  - トラブルシューティングの際、概略だけでも第一報は迅速に報告して、どの程度の影響かを把握、緊急性を判断するようにしている
  - チームメンバーのスキルややりたいことと、会社として取り組むべき課題をマッチングさせるようにして、チームメンバーのスキルアップを図っている
  - 同じチーム以外の投稿も見るようにして、自分の知見や解決策が役に立つと思えば、積極的に発言している
  - 自分の通常業務の範囲を超えて働かないといけない場合でも、助けを必要とする人に手を差し伸べることができる
  - 問題が発生した際は、リードエンジニアや事業責任者に報告、打ち合わせを設定することで、問題の解決を促すようにしている
- **役割：**
  - 開発リード（課題の発見・整理・技術選定・実装）
  - プロジェクト管理（タスクの分割、優先順位の設定、進捗管理）
  - 改善提案（開発、運用プロセスの改善）
  - エンジニア採用（採用広報、選考活動）
- **その他**
  - 自分が考えたものが形になる、企画から実装までを経験できることが好き
  - EV 業界や充電器に興味や知見を持っていて、プロジェクトに参加したいと思った
  - プロジェクトが開始してから幾度となく仕様変更があったが、対応するために担当者のアサインやタスクの優先順位を調整するなど、プロジェクトの進捗管理を行った
  - アーキテクチャの設計や機能のロジックを考えることが好き
