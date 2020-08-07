#readme.md
# Stock Client View ver.0.08.2
※このコードを利用するためにはpythonが必要です。(3.8.0を使用)

これはエクセルと連携して利用することで、在庫の管理と貸出先への貸し出し数が簡単かつ素早く確認できるコードです

## ニューリリース
- 0.07.0
    - pyファイルからの実行
- 0.08.1
    - 軽微なバグの修正
- 0.08.2
    - GUIへの対応
- 0.08.3
    - 使い方pdfを追加

## 注意事項
- 試用評価(β)版
- このコードはあくまで現在利用しているエクセルの補助的な利用を想定
- ここで利用したものは外部には取り出せないと思うこと(技術的には可能)
- 在庫は完全な機械による処理を想定しており、スキャナーなど個体識別番号を素早く入力できること
- 入力ミスがあるとエラーが起きるので、手打ちで番号等をうたないこと
- システム上、棒とネットだけの対応
- 同時に一つの画面のみ利用し、他の画面は開かないこと（データが破損する恐れあり）


- プログラムコードは著作物

- 製作者の許可なく複製・改ざん・頒布・リバースエンジニアリングを禁止されています




## 今後の予定
### アップデートで実装予定なこと
- ID＆Passによる利用者情報の保存
- その日の出庫状況や稼働状況をリアルタイムにみえる
- 演算処理の変更による、より速い処理
- 一つ一つ実行させないシステムの統合
### どうなるかわからないこと
- エクセルデータとの自動連携
- このシステムだけで出荷数が出荷しながら確認できる
- 出庫の際につける紙の印刷




## 【必須】python のインストール
1. https://www.python.org/ftp/python/3.8.5/python-3.8.5.exe     をダウンロード
2. DLしたファイルを実行し"install now"など、特に変更することなく進行させる
3. 完了画面が出たら成功

- もし分からなければサイト等を参考にする　https://techacademy.jp/magazine/15571#sec2

## Stock Client View の導入方法
1. DLする(https://github.com/HIKARI39/SCV/archive/master.zip)+SLDBConnectorのDL（検索）
2. ファイルを解凍し、任意の場所に保存する
3. exeファイルを実行する
4. 名前とパスの欄に適当な文字を入れてログインする
5. 説明はまだ作れてないので、適当に触ってみる。

※サンプルとして１１個の在庫が登録されています。



- 新規

新規在庫を登録できます

-  出庫

取引先へ出庫するとき

- 入庫

取引先から帰ってきたとき

- 廃棄

戻ってきている在庫を廃棄します

- 出庫先一覧（いまいち）

取引先とその取引先への出庫状況が一覧で表示されます
※工事番号は少しみにくい

- 出庫先検索

指定の工事番号への出庫状況を確認できます

- 在庫

出入庫の数が確認できます

## エラーや困った場合
件名「Stock Client Viewについて」と記し、メール（h_kudo39★s.okayama-u.ac.jp）に連絡して下さい。
