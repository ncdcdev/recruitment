# NCDCのエンジニア採用に応募しませんか

NCDCでは年間を通してエンジニアチームの採用情報を行っています。

1. [NCDCの紹介](#ncdcの紹介)
2. [NCDCのエンジニアチームの特徴](#ncdcのエンジニアチームの特徴)
   - [自由な技術選択](#自分たちで開発プロセス使う技術を選択する)
   - [生産性向上ツール](#生産性や品質を上げるためのツールの導入)
   - [企画段階からの参画](#サービスの企画段階から参画できる)
   - [働きやすい制度](#リモートワークなどエンジニアが働きやすい制度)
   - [技術交流](#活発な技術交流とナレッジ共有)
3. [開発実績](#どんなことをやっているか)
4. [募集中の職種](./jobs.md)
5. [採用プロセス](#採用プロセス)
6. [応募方法](#応募方法)

## NCDCの紹介

[NCDC](https://ncdc.co.jp/) は、「デザインとテクノロジーの力でビジネスを成功に導く」をキーワードにクライアントの新規サービスの企画からデザイン、システム開発までを一元的に行う、日本発のデジタルイノベーションファームです。

![NCDCロゴ](./images/ncdc-logo.png)

デザインシンキングやUXデザイン、アジャイル開発などプロセスや方法論を活用してクライアントのデジタルビジネス推進を支援します。

## NCDCのエンジニアチームの特徴

NCDCにはコンサル、デザイナー、セールス＆マーケなどのチームがありますが、会社全体の約半分のメンバーがエンジニアチームにいます。
チームの垣根は低く、プロジェクトやプロダクトのチームにはいろいろなプロフェショナルが一体となって進めています。また、複数のチームに所属している人もいます。

### 自分たちで開発プロセス、使う技術を選択する

開発プロセスや、技術に対して自分たちの裁量が大きいです。

理由は私たちのお客様は事業部門の方が多く、使う技術についてはNCDCに任せていただけることが多いからではないかなと思います。もちろん選択の自由とセットで責任もついて来ますので、なんとなく流行っているからでは選択できませんし、選んだからにはきちんとユーザーが使えるものにする（もしくは、他の技術に変える判断をする）必要はあります。

プロジェクトごとに技術的な振り返りを確実に実施し、得られた知見を次のプロジェクトに活かす文化が根付いています。この継続的な改善のサイクルにより、より良い技術選定や開発プロセスの最適化を実現しています。

これに関連する話なので併せて紹介しますが、NCDCの強みの一つは、モダンな開発プロセスや、技術を使ってサービスを実現することだと思っています。そのため、新しい技術を積極的に採用している方だと思います。

NCDCで採用している技術スタックはフロントエンド、バックエンドともTypeScriptを採用しており、インフラはAWSをほとんどのケースで採用しています。

![NCDCの技術スタックマップ](./images/tech-map.drawio.png)

その他、モバイルアプリやCI/CDなどについてもまとめた記事がありますので、気になる方は読んでみてください。
[NCDCの技術スタック](https://ncdc.co.jp/columns/7187/)

### 生産性や品質を上げるためのツールの導入

エンジニアの生産性を高めるためにGitHub Copilotや、[GitHub Copilot Chat](https://github.blog/jp/2023-07-24-github-copilot-chat-beta-now-available-for-every-organization/)などの新しいツールも積極的に導入しています。

また、テストのカバレッジを見える化するために[Codecov](https://about.codecov.io/)を導入しています。
新規プロジェクトではテストカバレッジの導入率100%を達成しており、チーム全体でテストを書く文化が定着しています。

![Codecovのスクリーンショット](./images/codecov-image.png)

エンジニアチームでは開発の生産性と品質を高めるため、以下のような取り組みを行っています：

- プルリクエストのリードタイム可視化ツールの開発と運用
- 各チーム（フロントエンド、バックエンド、インフラ）でのテンプレートやガイドラインの整備
- 新規プロジェクトへのテストカバレッジ計測の100%導入と定期的な振り返り

プルリクエストのリードタイム可視化ツールは、AWSのLambdaとGoogleのLookerを使って比較的短期間で開発しました。このツールを使って各プロジェクトで開発の振り返りを行い、日々の生産性の向上につなげています。

![振り返りツールのスクリーンショット](./images/metrics-image.png)

### サービスの企画段階から参画できる

コードを書く時に、「この技術を使ったらもっとこんな機能を提供できるのに」とか「なんのためにこの機能があるのかわからない」と感じたことはないでしょうか。

NCDCの強みは、サービスの企画、デザイン、ソフトウェア開発を全部自社でできることです。そのため、エンジニアもサービスの企画段階から入って、技術的な側面からビジネス側の人たちと一緒にサービスを作り上げていきます。

### リモートワークなどエンジニアが働きやすい制度

NCDCは創業以来リモートワークを採用しています。そのため、自社のオフィスに出勤するという考え方はありません。

一方、お客様先に行ってワークショップを実施したり、スプリントミーティングをやったりというのは積極的に行っていますので、週に１、２回はミーティングに出かけることがあります。（現在は新型コロナの影響でお客様とのミーティングもほぼリモートになっています）

10年以上リモートワークを採用していることもあり、リモートでも良いアウトプットが出せる仕組みや、コミュニケーションのとり方は工夫しています。

また、時間の使い方の裁量は大きいと思いますし、社内の事務作業などは極力軽量化されています。
お客様と話している時間より社内のマネージャーの承認を取る方に時間がかかる、というような時間のストレスはまずありません。

### 活発な技術交流とナレッジ共有

チーム全体で技術力向上とナレッジ共有に力を入れています：

- **社内勉強会**: 年間40回以上開催。取り組みの詳細は[振り返りで続ける勉強会](https://speakerdeck.com/rsogo/retrospective-driven-study-workshop-ncdc)にまとめています。
- **社外勉強会**: AWS、ReactのLT会をほぼ毎月開催。主に[connpass](https://ncdc-dev.connpass.com/)にて一般公開しています。
  - 2024年度は、1年間で8回開催しました。
- **技術記事**: ZennやQiitaで年間130件以上の記事を公開。[NCDCのZenn記事一覧](https://zenn.dev/p/ncdc)
- **コードレビュー文化**: PRレビューやペアプログラミングを通じて、より良いコードと設計を追求します。

また、エンジニアメンバーは外部の勉強会への参加も積極的で、最新技術のキャッチアップや外部コミュニティとの交流を大切にしています。

## どんなことをやっているか

開発しているソフトウェアは次のようなものです。

### Webサービス、モバイルアプリ開発

- コンシューマ向け、企業向けを問わずWebサービスや、アプリの企画から開発

新規のサービスが多いのが大きな特徴で、反対に、ゲームの開発や企業の基幹システムの開発はあまりやっていません。

### 生成AIソリューション

- 生成AIを活用したアプリケーション開発
- Chat-GPTやClaude等を用いたビジネスソリューションの設計・実装
- 生成AIを活用したRAGや業務効率化ツールの開発

エンジニアチームが主導で、展示会向けの生成AIを活用したチャットボットのデモを開発もしました。このデモは企業の製品情報や技術資料を学習し、展示会参加者からの質問に適切に回答できる対話型システムです。

![生成AIデモのスクリーンショット](./images/genai-demo.png)

### IoT、M2M

- 製造や建設の現場で各種センサーデータとクラウドで連携するIoTのサービス
- 楽器とBluetoothで連携して新しいユーザー体験を提供するモバイルアプリ
- リモートのカメラの映像をクラウドで処理して、物体検出や画像解析を行うシステム

クラウドを活用したIoTの事例として、Webカメラからの情報をリアルタイムでクラウドに送信し、画像処理や分析を行うシステムを開発しました。

![IoTデモのスクリーンショット](./images/iot-demo.png)

### アーキテクチャ系

- 大規模なWebサービスのサーバレスでの構築
- 大規模なIoTのシステムでメッセージング層、アプリケーション層などのアーキテクチャの設計
- マイクロサービスアーキテクチャの設計と実装

### AI/ML、データ分析

- 生成AIとコンピュータビジョンを組み合わせたハイブリッドソリューションの開発
- 動画からの物体検出モデルの開発
- IoTで各種センサーから収集したデータを元に、ある数値に相関関係のあるデータを分析する
- 機械学習モデルの実運用とMLOpsの実践

### NCDCがやっていることまとめ

実際に市場に出るプロダクトももちろん開発しますし、新規性の高いものはPoCとしてプロトタイプの開発なども行っています。
NCDCの強みは、サービスの企画フェーズでお客様やデザイナーと一緒になってサービスを考えるところから、ソフトウェアを開発してプロダクトやサービスという実際に価値を生むところまでトータルで提供できるところです。

NCDCの業務内容の特徴として、エンドユーザーとの直接契約がほとんどで、お客様のオフィスに常駐する仕事はほぼありません。

## 採用プロセス

基本的には以下のようなプロセスで進みます。決まったプロセスとは別に、例えば、同い年くらいの同じ職種の人と話してみたいなどご希望があれば柔軟に対応しています。

1. 面談
せっかく転職されるので、ご自分のやりたいことや考え方と転職先がマッチしているのかが重要だと思います。面談では主にNCDCのことを知っていただくのを目的としていますので、遠慮なくいろいろ聞いてください。

2. 技術課題、エンジニア面接
技術課題はフロントエンド、バックエンド、インフラなど得意な領域で受けていただくことが可能です。コードが書けるだけではなく、設計の考え方があるのか、使っているフレームワークの思想にあった書き方をしているのか、変更しやすい作りになっているのかなどの観点で確認させていただきます。面接の際に、どうしてこの設計にしたのかなどをお聞きするので、補足してもらえたらありがたいです。またGithubなどで公開されている方はそちらで代替できる可能性がありますので、その旨お伝えください。

3. 最終面接

採用プロセスについては、下記の記事も参考になると思うので、ご覧ください。
[現役採用担当者が明かすエンジニア採用試験突破マニュアル](https://ncdc.co.jp/columns/6955/)

## 応募方法

下記のメールアドレス、またはお問い合わせフォームでご連絡ください。
CTOが直接確認して、ご連絡致します。

- [NCDC企業Webサイト](https://ncdc.co.jp/)
- [NCDC採用サイト](https://ncdc.recruit-site.biz/)
- [採用担当へメール](mailto:hr@ncdc.co.jp)
