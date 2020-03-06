# cad
ピン作成時に使用する 3Dプリンタで作成する部品の cad データ
3Dプリンタの精度によって印刷できない場合 (穴があかないなど) があったため, 少しパラメータを変えた stl ファイルがたくさんあるという
git とは？というファイルの分け方をしている.

## motor_joint_for_milling

- 最新版は motor_joint_for_milling_top040mm_080slit.stl
- 現在のところ, 使用する予定のモータをネジを接合する部品
- ネジを回しながら挿入し固定する (milliing みたいに)

## photon がついてるファイル

- 梶本研の光造形 photon 用のファイル

## motor_joint_*slit.stl

- インサートナットを入れるように作成していたもの
- スリットが3Dプリンタで上手く作れなかったので無限にトライ&エラーした痕跡がある
- インサートナットはまっすぐ入れるのが難しかったのでやめた.

## motor_cover.stl

- モータを壁につけるやつ

## jikuuke.stl

- どれが最終版だかわからなくなってしまった...

## motor_and_pin_joint 

- プラスチックの底の装着する部品
- ナットを入れて, ネジで上下させるためのもの
