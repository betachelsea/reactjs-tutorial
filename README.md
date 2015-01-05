# reactjs-tutorial
ここのチュートリアルをざっくり終わらせたやつ
http://facebook.github.io/react/docs/tutorial.html

+αでブラウザ上への反映(更新)の動きだけ確認したかったので、POST周りの処理はコメントアウトした。

# メモ
ローカルサーバも立ち上げずtemplate.htmlを開くことでとりあえず確認したい場合はFirefox推奨。
Chromeだとcomments.jsonを読み込むところでエラー扱いにされてしまう（XMLHttpRequest cannot load file:///...）
- 参考：[林檎はいかが - Chromeではローカル内でJSONファイルが読み込めない ](http://www.studiom-web.net/wp/blog/2013/07/07/chrome%E3%81%A7%E3%81%AF%E3%83%AD%E3%83%BC%E3%82%AB%E3%83%AB%E5%86%85%E3%81%A7json%E3%83%95%E3%82%A1%E3%82%A4%E3%83%AB%E3%81%8C%E8%AA%AD%E3%81%BF%E8%BE%BC%E3%82%81%E3%81%AA%E3%81%84/)

たぶんローカルサーバを立ててそこで動かせば解決する。
