# AnalogWatch_forMSX0
MSX0用アナログ風時計プログラム

疑似輝度コントロールのため、ロータリポテンショメータをPORT Bに接続する必要があります。

同梱のWB1.SC5は、盤面とフォントが含まれています。
オリジナル盤面とフォントを作られる際には、
盤面は(44,0)-(255,212)のエリア、
数字は０の(2,0)-(15,14)から縦に10文字、
曜日は日曜の(0,150)-(43,158)から7つ分 
で配置されています。

また、べーしっ君を利用しています。
画面タッチで盤面を複数切り替えられるようにしたかったんですが、BLOADが使えないので、断念しました。。。

プログラムの終了は、スペースキーを押してください。

--2023/11/30 追記--  
少し改良して、75行目のデバイスパスを空文字列にするかコメントアウトすると、輝度調整が無効になり、常に表示できるようにしました。
