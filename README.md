# My_Malleable_VIs
Malleable VI

自分用にある程度汎用性のあるMalleable VI(順応性VI)をライブラリにしました。

- Array Nearest Index：配列から入力値に最も近い要素を取得します。配列の次元は何でもいいはず。配列の型はDoubleを想定。
- Boolean to 0-1：ブールを0,1に変換します。変換する型を指定できるようにしています。
- Close Front Panel：パネルを閉じます。開いていないVIのパネルを閉じようとするとエラーが発生しますが、このVIではすべてのエラーを無視します。エラーが入力されていてもパネルを閉じようとします。
- Get Current Timestamp：配線が全て入力されたときのタイムスタンプを取得します。
- Get Tail of 1D Array：1次元配列から後ろn個だけを出力します。
- Random Number：乱数を発生させます。アルゴリズムは既存のPolymorphic VIのコピーペーストです。
- Set Named Number Default if Invalid：Named Number(列挙体やテキストリング)制御器の現在値が無効の値なら入力したデフォルト値に変更します。デフォルト値の無効確認は行いません。
