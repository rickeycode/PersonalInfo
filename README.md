# 職務経歴書
## 基本情報
|key|value|
|---|-----|
|Name|田中 佑 (Yu Tanaka)|
|Blog|[RC-Code](https://rc-code.info/)|
|Twitter|[@rc_code](https://twitter.com/rc_code)|
|Qiita|[@rc_code](https://qiita.com/rc_code)|

## スキル

### 言語
- HTML5
- CSS
- SCSS
- JavaScript
- Swift
- ActionScript

#### 業務経験なし
- Kotlin
- Less

### 編集
- Design (Illustrator, Sketch, Figma)
- Animation (Adobe Animate, Lottie)

#### 業務経験なし
- Video (Adobe Premiere Pro)
- Sound (Logic Pro)

### フレームワーク
- Node.js
- Angular.js

### ライブラリ (OSS)
多数利用していますが、特筆すべきものを列挙。
- j-Query
- RxSwift
- realm
- TwitterKit
- FacebockSDK
- SwiftLint
- Alamofire
- GPUImage
- SDWebImage
- Quick
- Nimble

### CI
- jenkins
- TravisCI
- Bitrise

### ツール
- GoogleAnalytics
- Fabric
- fastlane
- Firebase
- Docbase
- esa
- Slack
- Skype


## アピールポイント
- アニメーション作成経験があるので、インタラクティブなコンポーネント作成が得意
- 単純なアニメーション・UIではなくUXを考慮した成果物を作成できる
- デザインシステムの改善経験があり、保守性・効率性を踏まえた開発フローが考えられる
- メジャーなデザインパターンを把握しており、適切なアーキテクチャでプログラミングできる
- 小規模の立ち上げプロジェクトを経験したので、立案からリリースまで一貫して作業できる
- 大規模開発を経験しているので、ユーザへの影響の勘所を理解している

## やったことはないが興味があるもの
- Android開発を趣味程度でしか開発できていないので、業務経験をしてみたい
- IoTの分野でインターフェースの知識を活かしてみたい
- 大人・子供に限らず教育の分野でプログラミング知識・ユーザインサイトの知識などを活かしたい

## 職務経歴
### 2019/3-  : 株式会社サイバーエージェント - アメーバブログiOSチーム
　iOSエンジニアとして所属し、主に新規開発を中心に従事。
  開発言語： Swift, Ruby (fastlaneで使用)
  開発ツール： Bitrise, Fabric, Firebase, GoogleAnalytics, Sketch, Figma

#### アプリ全体の刷新プロジェクト
  デザインスプリントからリリースまで一貫して担当。
  デザインスプリントの期間はメイン画面（フィード型リスト画面）のモックを製作し、フィードバックを早急に反映するPDCAを回した。
  実装期間には「お気に入り」「レコメンド」「履歴」のリストをユーザの状態によってロジックを変えて表示するという、複雑な画面を担当した。
  また刷新を期に、チームを跨いでドキュメント環境・デザインシステムの改善なども同時に進めた。
  アーキテクチャにはMVVMを採用し、RxSwiftでの開発を行った。

#### フォローしたブログの未読数表示機能
お気に入りに登録しているブログに関してチェックしたか否かのデータをAPIから取得し、未読数を表示する機能を開発。
アプリ起動中、該当するブログを閲覧した際にデータ更新やUI更新を行ったり、お気に入りから除外されたブログを省くなどというケースを踏まえ、データ保持＆更新の設計＆実装を行った。
また、未読のブログをレコメンドするモジュールのデザインや挙動に言及し、工数内で実現可能なパターンを提案し、実装した。

#### ブログのジャンル毎タブ表示・タブ編集機能
  ユーザの興味をカテゴライズする大規模機能（興味のあるカテゴリをタブ表示する機能）の開発を行い、設計・実装を行った。
  ジャンルにフューチャーしたブログを配信するAPIを繋げ、各ジャンルのブログをまとめたリストをタブ毎に表示する機能を実装した。
  興味のあるジャンルをタブに追加する機能、タブの並び替え及び削除機能も合わせて実装し、APIのレスポンス内容の精査から実装まで一貫して担当した。
  アーキテクチャは簡易的なファクトリパターンを採用した。


#### 各種広告の導入
  広告事業部との連携をとり、インバナーサーベイ型広告やアーティクル型広告のUI設計から実装まで担当。
  その他、カスタマーサービスからの調査・修正依頼対応、カバレッジの向上、行動ログの設計・導入も経験した。

### 2017/5-  : 株式会社サイバーエージェント - 株式会社アメステージ出向
　iOSチームのリーダーとして所属し、動画配信アプリの新規開発を行った。
　アプリの新規開発以外にも、アニメーションコンポーネントの非同期取得機構、動画のプレイタイムと同期したイベント発火機能の設計、アニメーションの作成等も担当した。
  開発言語： Swift, Ruby (fastlaneで使用), Node.js (アニメーション書き出しツールの作成)
  開発ツール： Bitrise, Fabric, Firebase, GoogleAnalytics, Sketch, Figma

#### アプリ仕様の策定
  - アプリの動画配信方法・再生方法の策定
  - チャットワークのシステム策定
  - 動画と同期したイベント発火方法の策定
  - アニメーションコンポーネントの非同期追加方法の策定
  - 課金システムの策定

#### 機能検証
  - 不安定ネットワーク上での配信・受信検証 (wowzaサーバとのコネクション確立を検証)
  - 動画配信時の各種イベント同期検証 (hlsのメタデータ領域とwebSocketの活用によるプレイタイム同期イベントの実現可能性を検証)
  - 非同期アニメーションコンポーネントの取得・保持検証 (配信に必須なアニメーション画像とタイムラインjsonを保持しているかチェックし、再生前にローカル保持する機構の検証)
  - 課金システム検証 (Apple側とのトランザクションと未完了トランザクションのローカル保持検証）

#### アプリ実装
  - ログイン機構の実装 (PaaS)
  - 課金システムの実装 (未完了トランザクション処理含む)
  - 配信画面実装（カメラ起動・動画アップロード・フィルタ適用・イベント発火機能&画面）
  - 視聴画面実装（hls受け取り&Player起動・webSocketつなぎ込み&チャット表示・イベント受信&発火・アニメーションコンポーネント再生）

#### その他
  - アニメーションのデザイン・作成（png書き出しとタイムラインjson書き出し）
  - Node.js によるアニメーションコンポーネントの管理ツール作成
  - 申請周り業務
  - GoogleAnalyticsの管理設定
  - TravisCIの管理設定

### 2016/9-  : 株式会社サイバーエージェント - 株式会社アメーバスタジオ出向
  

### 2013/5-  : 株式会社サイバーエージェント - アメーバピグスマホチーム

### 2011/5-  : 株式会社プーペガール

### 2008/4-  : 株式会社STC
　Webアプリケーションエンジニア（サーバーサイドエンジニア）として、インフラ設計からリリース、障害対応まで一通りの役職を経験しました。開発言語はPHP (Laravel、Zend)とScala (Play、akka-http)です。開発環境としてはGitLab、Jenkins、Vagrant、Oracle DB、MySQL、Groonga、Cassandraを利用してきました。クラウドサービスは特に利用せず、オンプレミス環境でサービスを運用していました。  

##### 担当業務
- インフラ設計
- サービスアーキテクチャ検討
- 新サービス検討
- 技術選定
- 要件定義・基本設計・詳細設計
- 実装・テスト・リリース・障害対応
- 開発環境改善（共通仮想環境構築、Jenkins化）
- API設計・開発
##### 業務外
　社外向けイベントの支援をしたり、デザイン思考のワークショップにメンターとして参加したり、業務外プロジェクトとしてMashup Awardsの法人部門にリーダー兼プレゼンター兼開発担当者として参加したりしました。Mashup Awardsでは最優秀賞を獲得しました。
### 2012/4 - 2016/2: 株式会社日立製作所
　設計開発、ブリッジSE、システムエンジニアとしてソフトウェアやサービスの開発に従事しました。在籍期間中、精神疾患のため計9ヶ月休職しました。
#### オンプレミス環境向け統合管理ソフトウェアの設計開発 (2012/8 - 2014/2)
　設計開発者として、ユースケース検討から実装、障害対応まで一通りの役職を経験しました。開発言語はJava (Java EEベースの独自フレームワーク）とFlex、Action Script3です。開発環境としてはSubversion、Jenkins、VMware、HiRDBを利用してきました。また、海外向けの製品だったため、ドキュメントは日本語ですが、表示仕様などは日本語と英語の両方を作成していました。  
　私は、統合管理ソフトウェアの中でもファイルサーバーやオブジェクトストレージの管理機能について主に担当していたため、Javaの実装能力だけでなくファイルサーバー、ブロックストレージ、オブジェクトストレージそれぞれのハードウェア仕様も考えながら実装する必要があったためハードウェアの知識も身につけました。
##### 担当業務
- ユースケース検討・ユースケース定義
- 要件定義
- 基本設計・詳細設計
- フロントエンドの開発
- ビジネスロジックの開発
- データベース設計
- 実装・テスト・障害対応
- 開発環境改善（共通仮想環境構築・Jenkins化）
#### オンプレミス環境向け統合管理ソフトウェアのブリッジSE (2014/5 - 2015/11)
　インドへのオフショア開発を対応するブリッジSEとして、ユースケース検討からオフショア先への実装依頼、開発、実装内容の確認・テストまで行っていました。開発言語はJava（Java EEベースの独自フレームワーク）とFlex、Action Script3です。開発環境としてはSubversion、Jenkins、VMware、HiRDBを利用してきました。オフショア先へ実装を依頼するため、ドキュメントはすべて英語で作成していました。また、オフショア先のメンバーと毎朝デイリーミーティングを英語で行っていたため、英語での業務推進には抵抗がありません。
##### 業務内容
- ユースケース検討・定義
- フロントエンド・ビジネスロジックの仕様決め
- オフショア先への実装依頼
- 実装内容のテスト
- 開発（日本側での調整が必要なものやツールなど）
#### 金融系基幹システム開発 (2015/12 - 2016/2)
　システムエンジニアとして、ネット銀行の基幹システムを開発していました。主に海外送金の機能や、デビットカード機能付きカードの実装を行いました。
##### 業務内容
- 基本設計・詳細設計
- データベース設計
- 実装
- テスト・リリース
#### 業務外
教育の一環で営業、工場勤務、経済、人間中心設計、コンピュータ工学などを学びました。

## 直近の企画・運営歴

## 登壇歴
|Date|Event|Slide|
|----|-----|-----|
|2017/04/22|Women Techmakers Tokyo 2017|[stretch opportunities](https://speakerdeck.com/okoysm/stretch-opportunities-number-wtm17)|
|2017/03/31|DENSO様向けデザイン思考プレゼン|資料非公開|
|2017/02/24|雑兵MeetUp ＃9|[転職したら転職しやすくなった](https://speakerdeck.com/okoysm/zhuan-zhi-sitarazhuan-zhi-siyasukunatuta-number-zohyomeetup)|
|2017/02/11|東京工業大学『エンジニアリング・デザインプロジェクトB+C 』発表会|資料非公開|
|2017/02/04|ゆるふわScalaコップ本読書会 第1章|[師匠（SENSEI）を見つけよう](https://speakerdeck.com/okoysm/shi-jiang-sensei-wojian-tukeyou)|
|2017/01/20|InnoCAFE#26 新年の抱負LT大会|[集中 #innocafe](https://speakerdeck.com/okoysm/ji-zhong-number-innocafe)|
|2016/12/17|FESTA2016 by MashupAwards (for Pro部門 決勝戦)|[全社員早押上司争奪戦](https://speakerdeck.com/okoysm/quan-she-yuan-zao-ya-shang-si-zheng-duo-zhan-number-ma-2016-number-forprojue-sheng-zhan)|
|2016/11/09|東京高専卒業生が後輩に送る楽しい授業 先輩の人生に学び、今日からできることを見つけよう|[講義資料](https://drive.google.com/file/d/0ByawtewcHSh9b1JzaDRibHU5RXM/view)|
|2016/10/09|DevFest Tokyo 2016|[女性エンジニアコミュニティの力](https://speakerdeck.com/okoysm/nu-xing-enziniakomiyuniteifalseli-number-devfest16)|
|2016/09/14|PayPal Tech Meetup #3|[お土産選びを助ける"PayPay"](https://speakerdeck.com/okoysm/otu-chan-xuan-biwozhu-kerupaypay)|
|2016/07/19|IoT縛りの勉強会! IoTLT vol.17 @ ヤフー|[屋内GPSツールを作っていたと思ったら、いつのまにかノールック出勤ツールができてた](https://speakerdeck.com/okoysm/wu-nei-gpsturuwozuo-tuteita-tosi-tutara-itufalsemanika-falserutukuchu-qin-turugadekiteta-number-iotlt)|
|2016/07/08|女子エンジニアLT夏祭り2016|[松村家を支える技術](http://qiita.com/okoysm/private/4d3820c1c3086c84aa04)|
|2016/06/17|Laravel勉強会 InnoCAFE#21|[Laravel歴=PHP歴な私がLαravelを布教した話](https://speakerdeck.com/okoysm/laravelli-equals-phpli-nasi-ga-laravelbu-jiao-sitahua-number-innocafe)|
|2016/05/21|JJUG CCC 2016 Spring|[もう知らないとは言わせない！Play Frameworkはじめの一歩](https://speakerdeck.com/okoysm/mouzhi-ranaitohayan-wasenai-play-frameworkhazimefalse-bu-number-jjug-ccc-number-ccc-m62)|
|2016/05/20|dots.女子部 - オールジャンル女子エンジニア集合！tips共有会vol. 2　〜私、この技術に恋してます♡〜|[Scala女子はカッコイイ](https://speakerdeck.com/okoysm/scalanu-zi-hakatukoii-number-dotsgirls)|
|2016/03/24|dots.女子部勉強会 vol.7 わたし、一生エンジニア宣言！～ 女性エンジニアとして長く働く秘訣 ～|(パネラーのため特になし)|
|2016/02/12|登壇者女子限定 Milkcocoa Girls ! Milkcocoa Meetup vol 6|[人見知りでもイベントを楽しめる!!〜リアルとネットをつなぐ〜](http://www.slideshare.net/syokookochi/ss-58187886)|
|2016/02/05|CROSS 2016|[We Are Geek Women Japan](https://docs.google.com/presentation/d/1g2dUqvcVo-VfV1yNHz1nmFvxtaaCMbo7qnvBkagSq54/edit#slide=id.p)|
|2016/01/21|第1回 ゆるゆる高専エンジニアLT大会 at FULLER|[女性エンジニアコミュニティの作り方](http://www.slideshare.net/syokookochi/fullerlt)|
|2015/12/21|dots.女子部 - オールジャンル女子エンジニア集合！tips共有会！！|[1日を36時間にするたったひとつの方法](http://www.slideshare.net/syokookochi/136-56467862)|
|2015/12/20|高専カンファレンス100 in 東京|[社会に出る前に知っておきたかったnのこと](http://www.slideshare.net/syokookochi/n-56467901)|
|2015/11/28|JJUG CCC 2015 Fall|(飛び込みLTのため特になし)|
|2015/10/31|「ECMAScript6勉強会」HappyHalloween JS 祭！！|[JSつまみぐい](http://www.slideshare.net/syokookochi/js-54599906)|
|2015/01/16|Tech Women - New Year's Party|[エンプラYOUは何してる？〜B2Cビジネスを支えるITインフラ〜](http://www.slideshare.net/syokookochi/you-43850960)|

## 受賞歴
- Mashup Awards 2016 For Pro 最優秀賞
- PayPal Tech Meetup #3 金賞
- IoTLT vol.17 がじぇるね賞
