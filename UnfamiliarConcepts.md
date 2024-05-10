# 理解していない、納得していない事一覧
###### 解決済みは[こちら](https://github.com/suzukidog/TIL/blob/main/UnderstoodConcepts.md)
<br>
<br>


- **static**
<br>staticってなんだよ！
<br>claudeに説明してもらっても全くわからないよ！
***


- **phpmyadminでエラー#1044**
<br>`#1044 - ユーザー 'sail'@'%' によるデータベース 'hogehoge' へのアクセスは拒否されました。`
<br>これについて調べた結果、.enbのDB_USERNAMEをsailからrootに変えると全ての権限が得られるらしい。
<br>しかしrootに変えるもエラーは出たまま。しかも保存と再起動をしているはずなのだがエラーメッセージにはsailの文字…。
<br>俺はrootだ！！
***

- **難しすぎて理解できないpart1**
<ul>
  
```
if (auth()->attempt(["username" => $incomingFields["loginusername"], "password" => $incomingFields["loginpassword"]])) {
    $request->session()->regenerate();
    return "Congrats!";
} else {
    return "Sorry...";
}
```

なんだよこれ、if文に詰め込みすぎだろ。意味わからん
<br>ログインするときにusernameとpasswordが合っていればCongratsもしくはSorryを返すよ。
<br>っていうコードなんだと思うけど、詰め込みすぎてよくわからなくなってる。
</ul>





<!-- 今の所ナイヨ！ -->
<!--
- **タイトル**
説明
<br>説明
-->
