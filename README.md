## Proto Split Wireless
 
![main_01](https://github.com/user-attachments/assets/b638dd3c-190f-449e-8a14-becb146401d8)

キーボードマーケットトーキョー2026で初頒布した左右分割キーボード用基板のリポジトリです。<br>
このbranchではキーケット2026で頒布した、製造番号`10779197A_Y19_260108`についての情報を記載しています。

現在検証中のFWについては後日追記予定ですが、取り急ぎ回路図のPDFファイルを以下に格納しています。

お手元のxiaoモジュールにて検証いただける場合は、以下のPDFファイルを参考にファームウェアを構築いただければと思います。

![circuit_diagram](Docs/circiut_diagram.png)

[PDFファイル](Docs/Proto_Split_w.pdf)

## \[update 2026/04/01\]: アクリルボトムプレート用のデータを以下に格納しました。

![acrylic_bottom](https://github.com/user-attachments/assets/bf0a9402-c511-4eeb-8242-b847cc4e3178)

レーザー加工サービス等を利用する場合は、サービスの入稿条件等を確認の上、ご使用ください。

[svgファイル](Accesory/Acrylic/bottom-inkscape.svg)

## \[update 2024/04/04\]: スイッチプレート用のSTLファイルを以下に格納しました。

### known issue:
1. スペーサー取り付け用の穴を開けていますが、ボトムプレートにはスペーサー取り付け用の穴がありません。
1. bambulab A1 miniでの出力を確認していますが、一定条件下では出力時に反りが出ることを確認しています。

[STLファイル](Accesory/3DP/ploto-split_plate%20v3.stl)

## \[update 2026/04/10\]: 現在検証中のファームウェアを以下に格納しました。

[firmwareフォルダ](firmware_bin/)

### about:
- ファームウェアの構築にはzmkを使用しています。
- 現在のところPrivateリポジトリにて作業していますが、今回頒布分の基板をお持ちの方で検証をお手伝いいただける場合は、\nContributorへ追加しますので、ご連絡ください。

### known issue:
1. Central側と接続先PC間の通信ができることは確認していますが、左右間の接続が確認できていません。
1. 初回接続時はコンスタントに通信できますが、一度電源を落とし再起動した際の接続が安定していません。

