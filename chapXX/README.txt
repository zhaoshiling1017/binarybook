
このフォルダには
書籍では触れていないプログラムを置いています。

書籍を読んだあと
さらに詳しい情報を知りたい方は参考にしてください。


■dumpXX

Windows環境にてプロセスをダンプするサンプルプログラムです。
以下のページで簡単な解説をしています。

プロセスダンプするプログラムを作成してみよう！
http://07c00.hatenablog.com/entry/2013/09/07/015519


■asmdisas

80x86 32-bit Disassembler and Assembler
http://www.ollydbg.de/srcdescr.htm

上記サイトで公開されているアセンブラ、逆アセンブラを
Visual C++ 2010 Express版でビルドできるようにしたものです。

アセンブラ命令とマシン語で相互変換したい。
http://07c00.hatenablog.com/entry/2013/09/24/021307


■ShellcodersChallenge

セキュリティコンテスト SECCON2013 において
使用された問題のソースコード一式です。
Ubuntu12.04/x86 + Apache2 にて動作確認しています。

SECCON2013については http://2013.seccon.jp/ をご参照ください。
使用されたのは SECCON関西（大阪）大会 であり、
http://2013.seccon.jp/blog/2013/12/seccon-2016.html
こちらのページに詳細が載っています。

技術的には「ブラウザ上からx86命令を実行できる環境を作ってみる」を
コンセプトに作ってみたものになります。

以下が動作を解説したスライドです（サンドボックス方式）。
http://www.slideshare.net/KenjiAiko/on-web-30208130

このままだと脆弱性があるプログラムとなっていますので
あくまで自身のみがアクセスできる環境でお試しください。
