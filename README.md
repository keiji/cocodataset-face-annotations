# COCO Dataset Face Annotations

## Description
[技術書典5](https://techbookfest.org/circle/47000001)で頒布した技術同人誌「Liteな期待が重すぎる」で利用している顔データセットのアノテーションファイルです。

 * [Liteな期待が重すぎる！](https://keiji.booth.pm/items/1043447) - BOOTH

[COCO Dataset](http://cocodataset.org)が配布している画像の顔領域にアノテーションをつけたものです。

このリポジトリにあるのはアノテーションだけです。
画像は含んでいないので、別途[COCO Dataset](http://cocodataset.org)からダウンロードしてください。

アノテーションは、Googleが公開している[ML Kit](https://firebase.google.com/products/ml-kit/)のFace Detection APIを使って作成し、
いくつかのデータについてはマニュアルで調整しています。

JSONデータは[Region Cropper 2.0](https://github.com/keiji/region_cropper)の形式です。

## ラベル
 0. Face
 1. left_eye
 2. right_eye
 3. left_cheek
 4. right_cheek
 5. nose_base
 6. left_mouth
 7. right_mouth
 8. bottom_mouth
 
