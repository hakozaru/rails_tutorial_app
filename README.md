# Ruby on Rails チュートリアルを追うレポジトリ
- あまりに基礎がなさすぎるので、隙間時間でRailsの基礎を自分に叩き込むために作成したレポジトリです。
- ただし、優先順位はSilver取得まではSilver。
- 可能であればアウトプットもしたいところ。（Gistか？）

# 心得
- わからないところは徹底して潰す。
 - チュートリアルでRspecは使われてないから、また別に勉強が必要。
- わかるところも飛ばさずに確実に読む。
 - しかし1日でも早く貢献するために素早く進めて少しでも業務に活かす。
- 嫁の機嫌は損ねないこと！（大切）
 - 嫁が出かける日などを有効に使う。
 - たまに甘いものを買ってきてごまかす。

### メモ
- 第1章
 - 特に不明な点はなし。
 - 全部ローカルでやるので、デプロイは全部すっ飛ばした。

- 第2章
 - チュートリアルでは新しくプロジェクト作成しているが、1章のをそのまま使った。
 - データベースのマイグレーションについてまだ理解が足りない（6章で解説）。
 - 2.3.3のRailsコンソール操作内容は自分もやってみるとある程度イメージできる。
   - でもまだ完璧なイメージは持てていない感じ。
   - 関連付けは11, 12章でさらに解説。
 - 演習のFILL_INに指定するシンボル名は db/schema.rb から:nameと:emailとわかる。

- 第3章
 - ここも新規でプロジェクトを作成せずに、今までのをそのまま使いまわした。
 - Railsのリカバリ機能も後々覚えておいたほうが良さそう。(今は飛ばす)
 - RESTアーキテクチャについて調べる。
 - この章ではコントローラのテストについて書かれている。
   - モデルについてのテストは6章〜
   - 統合テストについては7章〜
 - 「テンプレート」 = 「View」のこと
 - どうでもよくないけど、「git config --global user.name」と「git config --global user.email」が正しく設定されてなかったから、アカウント不明の謎な人がコミットし続けていた。

- 第4章
 - かなり多くのRubyに関する要素が出てくるので、何回も読み直して働きや役割等を叩き込む。
   - 普通にSilverの勉強にもなりそう。
 - 返値がtrueまたはfalseとなるようなメソッド名は?で終わる名前がつけられる。
 - 最後(4.4.5)の"example_user.rb"を使ったコードの検証は今後も勉強で使えそうだから覚えておく。
 - 「“deified”」という単語は回文である。

- 第5章
 - ページのレイアウトを作成している。
   - Bootstrapの導入
   - パーシャルで切り出し
 - [Asset Pipeline](http://railsguides.jp/asset_pipeline.html)の3つの主要機能についての説明。
   - アセットディレクトリ...静的ファイルを置く
   - マニフェストファイル...Railsに指示する
   - プリプロセッサエンジン...foobar.html.erb(右から順番にerb -> htmlと実行される。)
 - Sass(強化版CSS)について。
   - ネスト
   - 変数
 - Routesについて。
   - 名前つきルートの定義
   - routesは超絶重要だから、真っ先に書かれていることを理解できた方がRailsのスタートとしては良さそう。
   - 実際ここでの話はもっと早く知りたかったZE☆
 - テスト
   - featureテストっぽい。 なんでこんなに種類があるのか・・・

# その他いろいろ
1. [素晴らしいチュートリアルを用意してくださった方々に感謝。](http://railstutorial.jp/)
1. [マークダウンの書き方すぐに忘れる。](http://www.markdown.jp/syntax/)
