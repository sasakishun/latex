# latexで打消し線を使う方法
- ```https://did2memo.net/2016/04/24/easy-latex-install-windows-10-2016-04/``` を参考に処理を進める
- latexの最新版は```https://www.ms.u-tokyo.ac.jp/~abenori/soft/abtexinst.html```
から取得

\usepackage{color}    
\usepackage{jumoline} 
\usepackage{proofread}

# .styファイルの追加方法
- ```http://www.kagami.org/diary/2005-01-30-1.html```を参考に処理を進める
- 必要なスタイルファイルは2つ**jumoline.sty**と**sa**
-   http://sils.shoin.ac.jp/~gunji/CR/Kyozai/misc/jumoline/jumoline.sty
-   http://www.kagami.org/diary/data/proofread/proofread.sty
- スタイルファイル(.sty)を```C:\w32tex\share\texmf-dist\tex\platex\base```に移動
- powershellを起動し```$mktexlsr```を入力
