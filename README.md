# CopyNum

何のプログラムなのかよくわからない名前ですね．  
  
指定したディレクトリから任意個のファイルをランダムに選び，別に指定したディレクトリへコピーします．  
  
  
使い道：主に膨大な画像ファイルからWindowsの壁紙スライドショーで使うものを選び出すのに使っています．
複数のパソコンを使用するときは，Ｄｒｏｐｂｏｘなどのクラウドサービスを使うことで，一つのパソコンにだけ膨大な画像ファイルを入れておけばよくなります．
各パソコン上にクラウドサービスのディレクトリをつくり，そこに画像ファイルをコピー，壁紙スライドショーの参照先にします．  
  
  
使い方：コマンドラインからの実行は、exeファイル名と、4つのコマンドライン引数を入力します．
引数は，参照ディレクトリ・コピー先ディレクトリ・ファイルの開始番号・ファイルの数を順に入力してください．
ファイルの開始番号・ファイルの数の入力が無い場合，0から連番に20個のファイルをコピーします．  
  
一定時間ごとに自動で使用するには，タスクスケジューラに登録するのがいいと思います．   
タスクスケジューラの使い方は以下のサイト様が参考になります。  
http://www.atmarkit.co.jp/ait/articles/1007/30/news111.html  
http://www.atmarkit.co.jp/ait/articles/1307/08/news101.html
