# ①課題番号-プロダクト名

Career platform - event機能 -

## ②課題内容（どんな作品か）

- Career platform　個人画面を制作しました。
- キャリアに悩む方々がつながる場所や気軽に支援できる場所を作りたく、求人探しの機会に加えて、コミュニティ的な要素を追加しました。
- ログイン機能を実装していないので、アカウントIDは触れていませんが、作成したイベントの削除＆修正ができる仕様です。

## ③DEMO

https://beshift.sakura.ne.jp/kadai09/read.php

## ④作ったアプリケーション用のIDまたはPasswordがある場合

なし

## ⑤工夫した点・こだわった点

- tableを2つ仕様し、idでの紐付けを行ったこと（投稿とコメント）
- databaseのfuncs化に加えて、ヘッダーとサイドバーもincludeで利用したこと
- 課題（更新・削除・funcs化）に加えて、新しい機能追加（検索＆表示、時間経過とコメント件数カウントetc.）

## ⑥難しかった点・次回トライしたいこと(又は機能)

- ログイン機能と投稿＆IDの紐付けに次回チャレンジ！

## ⑦質問・疑問・感想、シェアしたいこと等なんでも

- [質問]
  【削除済みidへのデータ登録について】
  一度データを削除したidに改めて登録データを振ることはできるのでしょうか。

  【絵文字利用について】
  utf8mb4_unicode_cで作成しましたが、絵文字を入力するとエラーになりました。
  絵文字を含むテキスト入力をOKにしたい場合、	utf8mb4_unicode_c設定以外にも対応することはあるのでしょうか。
  
- [感想]
  PHPにも慣れてきて、さくらサーバーも今回はスムーズに出来ました。
  前回のものを流用するのではなく改めて1から作成したので、理解を深めることが出来ました。
  PHPはエラーがシンプルにわかりやすい。
