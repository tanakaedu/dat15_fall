# dat15_fall
2015年度秋学期の関連情報。

- [2年生](https://github.com/tanakaedu/dat15_fall#2年生後期)
- [1年生](https://github.com/tanakaedu/dat15_fall#1年生後期-6回目以降)


## リンク集
- [CCNA/CCNP、LPIC、オラクルマスター、ITパスポート、 ITILファンデーション試験の合格を目指す人を応援する学習サイト](http://ping-t.com/)
- [国立情報学研究所 GRACEセンター/先端ICTセンター 長久勝 GameJamCanvas](http://www.slideshare.net/mnagaku/gamejamcanvs?ref=http://www.igda.jp/?p=2507)
  - 短時間で成果を出すイベントで失敗を減らすための情報共有手段などについてのスライド
- [Unity作品をGitHub Pagesで公開する](http://am1tanaka.hatenablog.com/entry/2015/11/27/115926)
- [code.org マインクラフトやアナと雪の女王をモチーフに、ブラウザ上でプログラミングを学習できる](https://code.org/)
- [JSFIDDLE ブラウザ上でJavaScriptを書いて実行できる](https://jsfiddle.net/)
  - [Kachibito.net 紹介記事](http://kachibito.net/web-service/how-to-join-jsfiddle.html)
- [jsdo.it 同じく、ブラウザ上でJavaScriptを書いて実行できる](http://jsdo.it/)
  - [Gihyo jsdo.itを使ったフロントエンド開発](http://gihyo.jp/design/serial/01/jsdoit/0001?page=1)
- [Google TensorFlow](http://tensorflow.org/)
  - Googleがオープンソースで公開した機械学習システム
  - データの流れを表す図(Data Flow Graph)を使って、計算方法を組み立てられる
  - ある入力を、データフローグラフに従って評価
  - 評価した結果が目的の値(小さい値とか、大きい値とか)になるように、計算式内のパラメータを調整する
  - 上記を繰り返すことで、入力に対して、良さそうな結果を出力する
  - 機械学習の例
    - [TensorFlow公式 初心者のためのMNISTの学習](http://tensorflow.org/tutorials/mnist/beginners/index.md)
    - [t-hiroyoshi Caffeで手書き数字(MNIST)の認識学習をする](http://qiita.com/t-hiroyoshi/items/2bf473fd06c352d97579)
- [ぴよぴよ・py 強くなるためのプログラミング-様々なプログラミングコンテストとそのはじめ方-](http://cocodrips.hateblo.jp/entry/2015/10/11/114212)
- [クックパッド開発者ブログ 総合職で入社した新卒がクックパッドでエンジニアになるまで](http://techlife.cookpad.com/entry/2015/10/30/125405?utm_content=buffere7557&utm_medium=social&utm_source=twitter.com&utm_campaign=buffer)
- [Unity公式Blog ENGINE ROOM GAMESとPLAYSTATION開発の明るい未来](http://blogs.unity3d.com/jp/2015/11/11/a-bright-future-for-playstation-deployment-with-engine-room-games/)
- [katsew ブラウザゲーム開発で使えそうなゲームエンジンまとめ](http://qiita.com/katsew/items/bdd3be42e43e7d63d160)
- [Unity県人会議イベント一覧](https://kenjin.unity3d.jp/events)


----


## 2015/10/30
- [Unity公式サイトニュース 就活生・若手開発者向け開発コンテスト 『ゲームクリエイター就職大作戦2015』 プレゼン発表会結果発表](http://japan.unity3d.com/blog/press/20151014)
- [Unity県人会議 バンダイナムコ　カタログIPオープン化プロジェクトGameJam](https://kenjin.unity3d.jp/events/show/274)

## 2015/10/23
- [2015/10/23 ニュース](https://github.com/tanakaedu/dat15_fall/wiki/2015-10-23%E3%83%8B%E3%83%A5%E3%83%BC%E3%82%B9)


# 2年生後期
## 6回目以降
- 就活の追い込み
  - 作品をGitHub Pagesにアップロードする
  - 名刺の作成(QRコード)
  - [Paiza新卒](http://paiza.jp/student)に登録して、コードの練習を行う
    - https://paiza.jp/lp/student
  - 勉強会への積極的な参加
- HTML
- CSS
- Bootstrap
- 数学
- Unity UNET関連
    - [ひよこのたまご 【Unity9】UNETでマルチプレイヤーなオンラインゲーム開発【UNET1】](http://hiyotama.hatenablog.com/entry/2015/07/06/153000)
    - [凹みTips Unity 5.1 から導入された新しいネットワーク機能の UNET について詳しく調べてみた](http://tips.hecomi.com/entry/2015/08/14/220030)
- Unity UNET のLAN内サーバーへの自動接続
  - http://am1tanaka.hatenablog.com/entry/2015/10/09/005346

# 1年生後期 6回目以降
- Unity公式のYoutube https://www.youtube.com/user/Unity3D
- Unityの様々なチュートリアル https://www.youtube.com/channel/UCq9_1E5HE4c_xmhzD3r7VMw/videos
- UnityのSpaceShooterを改良する
  - [x] 隊列が崩れるバグの修正
  - [x] 修正をmasterにマージ(教員が行う手順を確認)
  - [x] 自機を狙う
    - [x] ベクトル：向きを決める 
      - [x] 敵を自機の方向に向かせる
    - [x] 三角関数：角度を決める
    - [x] 多方向弾
    - [x] 時間差撃ち
  - [x] 定角速度ホーミング
  - [x] 慣性ホーミング
  - 各自、自分のアカウントにForkして、自由に改造する。就職活動に利用することを前提とするので、ライセンス表記には気を付ける
- 毎日の最後に作業をPushする
- Code.org
- クラス
- GitHubでの作業
- UNet
- 数学

## 講義資料
- [spaceshooter開発用リポジトリ](https://github.com/dat15-spaceshooter/spaceshooter)
- 10回目
  - C#でクラス設計
    - キャラクターの保持
    - ポリモーフィズムによるif文の削除
  - [ひよこのたまご チュートリアル一覧](http://hiyotama.hatenablog.com/entry/tutorials)

----

- 9回目資料
  - [9回目 慣性ホーミング](https://github.com/dat15-spaceshooter/spaceshooter/blob/master/Docs/spaceshooter-shotplayer5.pptx?raw=true)
- 8回目：自機を狙う(4)定角速度ホーミング
  - [8回目資料](https://github.com/dat15-spaceshooter/spaceshooter/blob/master/Docs/spaceshooter-shotplayer4.pptx)
- 7回目：自機を狙う(3)
  - 三角関数を使う
  - 資料は[こちら](https://github.com/dat15-spaceshooter/spaceshooter/blob/master/Docs/spaceshooter-shotplayer3.pptx)
  - [ytanaka1211ブランチ](https://github.com/dat15-spaceshooter/spaceshooter/tree/ytanaka1211)に成果物
- 6回目：自機を狙う(2)
  - ベクトルその２
    - 敵にプレイヤーの方向を向かせる
  - 資料は[こちら](https://github.com/dat15-spaceshooter/spaceshooter/blob/master/Docs/spaceshooter-shotplayer2.pptx)
  - [ytanaka1204ブランチ](https://github.com/dat15-spaceshooter/spaceshooter/tree/ytanaka-1204)に成果物
- 5回目：自機を狙う
  - ベクトル：向きを決める 
    - 直接自機を狙う
  - 隊列を出現させる(隊列が崩れて出現。原因究明は次回)
  - ytanaka1127に成果物
- 4回目：GitとGitHubについて / SpaceShooter作業
  - [インストール手順](http://am1tanaka.hatenablog.com/entry/2015/11/06/130120)
    - [GitHub Desktop](https://desktop.github.com/)
    - [WinMerge](http://www.geocities.co.jp/SiliconValley-SanJose/8165/winmerge.html)
  - [サルでも分かるGit入門](http://www.backlog.jp/git-guide/intro/intro1_1.html)
  - 最新版のmasterを自分のプロジェクトに結合
    - プロジェクトをコミットしてプッシュ
    - 資料に従って結合する
- 3回目：SpaceShooterのチーム開発(2)
  - [手順](https://github.com/tanakaedu/dat15_fall/wiki/1%E5%B9%B404%E5%9B%9E%E7%9B%AE)
- 2回目：SpaceShooterのチーム開発
  - [手順](https://github.com/tanakaedu/dat15_fall/wiki/1%E5%B9%B403%E5%9B%9E%E7%9B%AE)
- 1回目:Space Shooterを完成させる
  - [ゲーム終了とゲームの構築](https://github.com/tanakaedu/SpaceShooterTutorial/wiki/%E6%89%8B%E9%A0%863_2:%E7%B5%82%E4%BA%86%E3%81%A8%E3%82%B2%E3%83%BC%E3%83%A0%E3%81%AE%E6%A7%8B%E7%AF%89)
  - [敵、更なる障害物、背景のスクロールなど](http://unity3d.com/jp/learn/tutorials/modules/intermediate/live-training-archive/extending-space-shooter?playlist=17147)

# リンク
- 新卒向けのITエンジニア就活用サービス paiza新卒
    - http://paiza.jp/student
- PHP学習環境 paiza learning
  - https://paiza.jp/learning
- 学生向け　プログラミングコンテスト CODE RUNNER 2015  
    - https://coderunner.jp/trial.html
- [とほほのBootstrap入門](http://www.tohoho-web.com/ex/bootstrap.html)
- [ソラリス IoT向けデバイス向けSIM](https://soracom.jp/)
- [カタログIPオープン化プロジェクト](http://open.channel.or.jp/)

