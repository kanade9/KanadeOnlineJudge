# KanadeOnlineJudge
KanadeOnlineJudge(KOJ)とは、自分が[Sharif Judge](https://github.com/mjnaderi/Sharif-Judge)というOSSを用いて構築したfull-feedback方式のプログラミング問題を提供するサイトです。 
ここではその使い方について解説してゆきます。アクセスは[こちら](http://koj.eastus.cloudapp.azure.com/)からどうぞ。 

### 作成した理由
最近競技プログラミングが流行しています。楽しい上にプログラミングも上達するとても素晴らしいものだと自分は考えています。自分の周りの身近な知人や友人に実際に触れてもらいたいと思い、手軽にチャレンジできる環境を作りたい！と思い構築しました。さらには自分のインプットした事をアウトプットする手段として、周りに伝えること。問題を作り解法を説明するということがこれにあたり、この動作を自分は楽しく行えると考えたのも理由の一つです。ですので基本的には知人とワイワイやるためのものであって、たくさんのユーザーに取り組んでもらうためのプラットフォームではありません。

### 登録について。
登録には招待コード、メールアドレス、パスワードが必要です。  
メールアドレスが間違っているとパスワードの再設定ができませんので注意してください。  
招待コードはこのページの一番下に記載しています。

### 使用方法
ログイン後、左のメニューからAssignmentsを選択すると現在公開されている問題に挑戦することができます。挑戦したいコンテストを選んでチェックバーにチェックを入れた後、メニュー欄からProblemsを選択すると問題が出てきます。尚、複数の問題が1つのコンテストに設定されている場合、右上から変更することができます。  
問題を解く際はローカル環境でファイルを作成し、完成したら右側のSubmitから言語と作成したファイルを選んで提出してください。  
提出後は自動的に判定画面に移動します。ここで数秒程度時間が経ったらリロードしてください。あなたのコードがジャッジされ、点数が表れたら終了です。

### 環境について
対応している言語はC,C++,Java,Python2,Python3です。ただしデバッグはPython3のみで行なっているため、他の言語ではエラーが発生する場合があります。もしエラーを見つけた場合はissue欄で報告をお願いします。
基本的にメモリは50000kBまで,実行時間はC/C++が500ms,Pythonは1500ms,Javaは2000msまでとしています。ファイルサイズは50kBまでです。  
安全のため提出されたプログラムはsandbox上で実行していますが、一部のライブラリ等の使用を制限していますのでご了承ください。
### 困ったときは？
### 今後の予定
- https対応
- 問題作成用READMEを作る

招待コード 10327
