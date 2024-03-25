## 概要

windows上の壁紙機能に不満があり作成。

exe化し過去に配布していた。

## 動作

今回はexeファイルを置いていても意味がないためpyファイルを置いている。

但しファイルパスなどはすべてexeが特定の場所に存在する前提で記述されているため動作しないと考えられる。

また、そのため使用する画像はアップロードしていない。

以下に動作時の画像を添付する。参照から画像を設定し、時刻を設定。その後保存することで特定のタイミングで背景画像を切り替えられる。

![スクリーンショット (2674)](https://github.com/f-atsuhiro/background_changer/assets/163499167/ac8fb29e-c9b3-4d55-a54f-a4fb77e67b6a)

## オリジナルとの相違点

現在main_.pyが設置されているが本来このファイルはmain.exeとして./assets/main_pg/に存在し、setup時にlocalappdataにコピーされるはずである。

