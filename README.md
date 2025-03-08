# know_how_camp

■サービス概要
法人の既存ノウハウ（*）を掲載し、個人がそれらのノウハウを閲覧&活用できるサービス。
*対外向けに公開しているウェビナーや記事（例：基幹システムをどう導入したか、等）

■ このサービスへの思い・作りたい理由
(以下、共に起業を考えている友人の体験)
現職はコンサルタントであり、とある課題に対し他社がどのような対応を取っているか、ノウハウを問われることが多々ある。
コンサルタントに頼らずとも、ユーザー自らノウハウの獲得&課題解決できるようなプラットフォームを構築していきたい。

■ ユーザー層について
掲載側：既存のノウハウをオウンドメディアや他サービスに掲載している法人
理由：既にノウハウを形にして発信しており、自社の宣伝や広告等に興味がある&本サービスへノウハウを掲載してくれる可能性を見込めるため。

閲覧側：企業の管理者層または担当者層の個人
理由：自社の現場レベルの課題解決を担う層であり、上記の体験にてノウハウを聞いてくる人たちのため。

■サービスの利用イメージ
掲載側：
　利用イメージ：月額課金により運営側がアカウント登録後、既存のノウハウを自由に本サービスへ掲載
　得られる価値：ノウハウを閲覧したユーザーの情報を獲得し、アプローチ可能

閲覧側：
　利用イメージ：基本無料で自らアカウント登録後、自由にノウハウを閲覧し、月額課金すれば掲載側や他閲覧者へ連絡可能
　得られる価値：ノウハウの調査から活用の相談まで本サービス内で完結させることが可能

■ ユーザーの獲得について
掲載側：ノウハウをネット上に掲載している企業をリストアップし、電話もしくは訪問営業
閲覧側：現職のお客様や友人への告知

■ サービスの差別化ポイント・推しポイント
他サービス：
　①
　　カテゴリ等のキーワード検索では多数のノウハウがヒットし、上位に表示されないノウハウが閲覧されない。
　　（=ユーザーにとって最適なノウハウか判別されることなく、上位表示されるノウハウだけが閲覧される）
　②
　　掲載側→閲覧側への一方通行のコミュニケーションとなっており、その連絡手段もメールや電話等ハードルが高い。

本サービス：
　①
　　ユーザーには困りごとを可能な限り詳細にテキスト入力してもらい、最適なノウハウを上位表示させる。
　　上記のために、運営側では各ノウハウの説明欄を均質化し、AIの連携させることも必要と考えている。
　②
　　本サービス内のチャット機能で、掲載側⇔閲覧側の気軽な連絡およびノウハウの活用相談が可能。

■ 機能候補
MVPリリース時：
　ログイン機能、ノウハウの投稿・検索・閲覧・削除・コメント・ブックマーク機能、チャット機能、類似ノウハウのレコメンド機能
本リリース時：
　AIとの連携によるノウハウ提案機能

■ 機能の実装方針予定
動画の加工：Cloudinary
チャット機能：ActionCable
レコメンド機能：Amazon Personalize

■画面遷移図 & 画面イメージ
https://www.figma.com/board/TcIhRD7YabasR52gCAKNpa/%E7%94%BB%E9%9D%A2%E9%81%B7%E7%A7%BB%E5%9B%B3?node-id=0-1&t=xsNCVXh6CLfKtp9B-1