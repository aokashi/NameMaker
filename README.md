世界観の地名作成のために作成、加工したJavascriptの名前生成プログラムです。

# 処理について
1. csvファイルの内容を取得して、1行毎に分けます
2. 分けた1行分をそれぞれ,で分けます
3. 1行の一番最初にある数字を元に、付けるかどうかの判定をします
4. 付ける場合は、1行の2番目の数字から3番目の数字の範囲で、持っていく文字列の回数を決めます
5. ,で分けた文字列を決めた回数分、ランダムで選定します
6. 1行毎に選定した文字列をくっつけます

# csvデータのフォーマット
1行を読み込む際、以下のフォーマットで処理していきます

- 1番目は、入れる確率を設定します(0～100の確率で決めます)
- 2番目は、最小出力回数を設定します
- 3番目は、最大出力回数を設定します

最小出力回数が最大出力回数を上回るとエラーが発生します。

# 添付しているcsvデータについて
- 日本地名：日本にありそうな地名を生成します
- 海外地名：[ヒラリラーの名前生成機](http://hirarira.net/namemaker)に近い生成パターンで生成します

# Thanks
- ヒラリラー(http://hirarira.net) - 名前生成プログラムのベースの提供
