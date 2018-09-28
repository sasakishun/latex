# latexで打消し線を使う方法
- 下記のスタイルファイルをインストールした後,.texファイルにこれらの記述を追加すればOK

\usepackage{color}    

\usepackage{jumoline} 

\usepackage{proofread}

# .styファイルの追加方法
- http://www.kagami.org/diary/2005-01-30-1.html を参考に処理を進める
- 必要なスタイルファイルは2つ**jumoline.sty**と**proofread.sty**
-   http://sils.shoin.ac.jp/~gunji/CR/Kyozai/misc/jumoline/jumoline.sty
-   http://www.kagami.org/diary/data/proofread/proofread.sty
- スタイルファイル(.sty)を```C:\w32tex\share\texmf-dist\tex\platex\base```に移動
- powershellを起動し```$mktexlsr```を入力

# latexを使う方法（WindowsでTexWorksを使う場合）
- https://did2memo.net/2016/04/24/easy-latex-install-windows-10-2016-04/ を参考に処理を進める
- latexの最新版はhttps://www.ms.u-tokyo.ac.jp/~abenori/soft/abtexinst.html
から取得

# TexWorksでpbibtex(日本語bibtexの読み込みに必要)の使い方
- https://qiita.com/takahiro_itazuri/items/d34a66cf6c69032a4f26 を参考に
