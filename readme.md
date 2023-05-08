# プロダクトのタイトル

簡易ブログアプリ

## プロダクトの紹介

- 写真と簡単なコメントを自由に投稿できます。

- 投稿された内容は一覧で確認できます。

- ログイン機能や投稿一覧へのコメント機能は今後実装したいです。（ログイン機能が特に現時点では私にとって難しかった；；）

## 工夫した点，こだわった点

- テキストエリアで入力した改行の情報をアウトプットする際にも反映したこと。

- 写真と投稿内容がセットで表示されるようにしたこと。

- 見やすいデザインにした。

- 投稿した内容をアウトプットへ自動で反映するのには画像を含めた関係でラグがあったため、リロードボタンを用意し強制的に投稿内容を反映させて確認できるようにした。

- アウトプットされた投稿一覧をホバーしたら少し大きく表示されるようにし、写真が小さくなってしまう問題への対処にした。

- スマホでも見れるようにした。

## 苦戦した点，共有したいハマりポイントなど

- firebase のデータベースにアップロードするときに一緒に画像のみストレージへアップロードさせるところが難しかった。

- アップロードした後、画像をダウンロードして表示する url の取得方法に迷走した。

- 画像が表示されたと思ったら複製されて表示され、何故表示できたかを理解していないままどこかを直せば完成と思ってコードを修正したら表示が消えてしまい振り出しに戻ってしまった。

- 関数のスコープの概念を見落とすことが多かったので反省。

- エラー文が大量に出た時に 1 つずつ対応していたら、ループしたので俯瞰して見る必要があったと感じた。
