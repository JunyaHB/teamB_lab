# README

fujikawa0724での改変
* 上のバーを書き換えた。
* contact, aboutusのページを作った。
* helpページは消した。
* testを少し書き換えて通るようにした。
* 設問が6問になった。
* 結果がerbで出るようにした。
* questions1ファイルを追加
* 結果をスコアにして合計した値を表示、値により寸評を表示

今後の予定
* トップページから診断ページの遷移をすり合わせる。TakeshiHoraのプルリクエスト#8でいいと思う。
* 未回答の質問があるときにエラーを出す
* トップページからはhidden属性のinputで値を渡す
トップページにメールアドレスを入力→次のページのhiddenに入れる→DBに入れる
トップページにメールアドレスを入力しない→次のページのhiddenにから文字列を入れる→DBに入れる
* 結果をDBに入れる
* メールを送信する
* 問題数を増やす
