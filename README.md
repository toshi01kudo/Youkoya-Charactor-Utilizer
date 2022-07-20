# Charasheet-Utilizer

キャラクター保管所 (https://charasheet.vampire-blood.net/) にてご利用いただける非公式な便利ツールです。使っていただけるとありがたいです。

## 機能一覧
### ココフォリア駒出力（ゆうやけこやけのみ）
キャラクターデータをココフォリア (https://ccfolia.com) へ直接貼り付ける機能です。

キャラクター情報を登録後、「ココフォリア駒出力」ボタンを押下すると、クリップボードへコピーされ、
ココフォリアの画面にて、「貼り付け」を行えば、ココフォリアにてキャラクター作成完了です。

### ゆうやけこやけの追加サプリメント「よいやみこみち」の追加種族を選択可能
「ゆうやけこやけ」のサプリメント「[よいやみこみち](http://incoglab.com/yoiyami-sell/)」掲載の追加種族をプルダウンから選択可能になります。(ただし、正体情報はエラー保存されません。)\
基本特技も自動追加されます。
![](yoiyami_shuzoku.png)

## 前提条件
* ブラウザのアドオンにて動作します。
  * Firefoxなら [Grease Monkey](https://addons.mozilla.org/ja/firefox/addon/greasemonkey/)
  * Chrome or Vivaldiなら [Tampermonkey](https://chrome.google.com/webstore/detail/tampermonkey/dhdgffkkebhmkfjojejmpbldmpobfkfo?hl=ja)
  * ※他のブラウザでの動作検証はしていません。

## 導入方法
1. ブラウザのアドオンをインストールしてください。
  * Firefoxなら [Grease Monkey](https://addons.mozilla.org/ja/firefox/addon/greasemonkey/)
  * Chrome or Vivaldiなら [Tampermonkey](https://chrome.google.com/webstore/detail/tampermonkey/dhdgffkkebhmkfjojejmpbldmpobfkfo?hl=ja)
  * ※他のブラウザでの動作検証はしていません。
2. Github 上ののプログラムファイルページ [Youkoya-Charactor-Utilizer.user.js](Youkoya-Charactor-Utilizer.user.js) にて、上段右の 「Raw」と書かれたボタンを押下。\
![ClickRawButton](../../../KindleUnlimitedSearcher/blob/main/ClickRaw.png)
3. アドオンのページで「インストール」をクリックすることで導入完了。

## 制約事項
* ゆうやけこやけの追加種族を選択した場合、保存時に「種族が設定されていません」とエラーとなり、「正体」の保存ができません（そのほかのデータは保存できます）。種族名は「パーソナルデータ」内の「種族」に記載してご対応ください。

## 免責事項
* 本ツールの導入は必ず自己責任でお願いします。当方は本ツールにて生じた損害の責任を一切負いません。

## Links
* キャラクター保管所: https://charasheet.vampire-blood.net/
* ココフォリア: https://ccfolia.com
