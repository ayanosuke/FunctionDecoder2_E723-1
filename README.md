# Arduino_SmileFunctionDecoder2 for Effect Function<br>
SmileFunctionDecoder2 (AYA002-2)用のエフェクトファンクッションデコーダスケッチです。<br>
多種点灯パターンを用意しました。<br>
<br>
デフォルトのアドレス3<br>
O1:F1 でON/OFF<br>
O2:F2 でON/OFF<br>
O3:F3 でON/OFF<br>
O4:ヘッドライト F0でON/OFF F4でFX 効果切り替え<br>
<br>
LightMes()関数搭載(^^;<br>
ATtiny85デコーダはシリアルピンが無いため、Atiny85 PB0(5pin):O1を使って、<br>
変数の値を光で確認できます。<br>
※出力ポートはO1,O2,O3,O4のいづれかに変更できます。<br>
※アドレス書きかえ時に影響あるところに入れるとアドレス変更に失敗します。<br>
※CV49の書き換えでFX効果を切り替えたいのですが、なぜかうまく動かない。<br>