[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/Kazuhito00/albumentations-examples/master?filepath=albumentations-examples.ipynb)

# albumentations-examples
albumentations-examplesは画像データ拡張ライブラリAlbumentationsのJupyter上での実行例です。

# Requirement
 
* OpenCV 3.4.2(or later)
* Albumentations 0.4.5

# Usage
Jupyter上でalbumentations-examples.ipynbを開いて実行してください。

実行例を見るだけであれば、Github上でalbumentations-examples.ipynbを開くと以下のように見ることが出来ます。

また、README上部のBinderバッジからBinderでの実施も可能です（ただし一部うまく動作しないセルがあるため、原因確認中）

![2020-03-15 (1)](https://user-images.githubusercontent.com/37477845/76687013-7b05e200-6663-11ea-8e7e-f053b0dfbb5a.png)

# Examples
以下の実行例を実装しています。

* ぼかし(Blur)

* 垂直反転(VerticalFlip)

* 水平反転(HorizontalFlip)

* 水平垂直反転(Flip)

* ノーマライズ(Normalize)

* 行列転置(Transpose)

* ランダムクロップ(RandomCrop)

* ランダムガンマ補正(RandomGamma)

* ランダム90度回転(RandomRotate90) ※N回90度回転

* ランダム回転(Rotate)

* ランダムアフィン変換(ShiftScaleRotate) ※ランダムスケール、ランダム回転

* センタークロップ(CenterCrop)

* 光学ひずみ(OpticalDistortion)

* グリッドひずみ(GridDistortion)

* 弾性変形(ElasticTransform)

* ランダムグリッドシャッフル(RandomGridShuffle)

* HSV変換(HueSaturationValue)

* パッド付与(PadIfNeeded)

* RGBランダムシフト(RGBShift)

* 輝度ランダム変更(RandomBrightness)

* コントラストランダム変更(RandomContrast)

* モーションブラー付与(MotionBlur)

* メディアンブラー付与(MedianBlur)

* ガウシアンブラー付与(GaussianBlur)

* ガウスノイズ付与(GaussNoise)

* ガラスブラー付与(GlassBlur)

* コントラスト制限付き適応ヒストグラム均等化(CLAHE)

* RGBチャンネルランダムシャッフル(ChannelShuffle)

* ピクセル値反転(InvertImg)

* グレースケール化(ToGray)

* セピア化(ToSepia)

* JPEG圧縮劣化(JpegCompression)

* WebP圧縮劣化(ImageCompression)

* ランダムカットアウト(Cutout) ※正方形領域

* ランダムカットアウト(CoarseDropout) ※矩形領域

* float化(ToFloat) ※0.0～1.0

* 整数化(FromFloat)

* 切り抜き(Crop)

* マスクを使用した切り抜き(CropNonEmptyMaskIfExists)

* ランダムスケール(RandomScale)

* マックススケーリング(LongestMaxSize)

* ミニマムスケーリング(SmallestMaxSize)

* リサイズ(Resize)

* ランダムクロップ後、一定のサイズに再スケーリング(RandomSizedCrop)

* ランダムクロップ後、一定のサイズに再スケーリング(RandomResizedCrop)

* 輝度およびコントラストのランダム変更(RandomSizedBBoxSafeCrop)

* bboxを維持したランダムクロップ(RandomSizedBBoxSafeCrop)

* ランダム雪シミュレート(RandomSnow)

* ランダム雨シミュレート(RandomRain)

* ランダム霧シミュレート(RandomFog)

* ランダム太陽シミュレート(RandomSunFlare)

* ランダム影シミュレート(RandomShadow)

* ランダムチャンネルドロップ(ChannelDropout)

* ISOノイズ(ISONoise)

* ソラリゼーション(Solarize) ※閾値を超えるピクセル値を反転

* ヒストグラム平均化(Equalize)

* ポスタリゼーション(Posterize) ※各カラーチャネルのビット数を減らす

* ダウンスケール/アップスケールバックによる画質低下(Downscale)

* ノイズ乗算(MultiplicativeNoise)

* Fancy PCA

* マスクドロップアウト(MaskDropout)

* グリッドドロップアウト(GridDropout)

* imgaugヘルパー：DualIAATransform

* imgaugヘルパー：ImageOnlyIAATransform

* imgaugヘルパー：エンボス(IAAEmboss)

* imgaugヘルパー：スーパーピクセル(IAASuperpixels)

* imgaugヘルパー：先鋭化(IAASharpen)

* imgaugヘルパー：ガウスノイズ(IAAAdditiveGaussianNoise)

* imgaugヘルパー：クロッピング＆パディング(IAACropAndPad)

* imgaugヘルパー：左右反転(IAAFliplr)

* imgaugヘルパー：上下反転(IAAFlipud)

* imgaugヘルパー：アフィン変換(IAAAffine)

* imgaugヘルパー：区分線形アフィン変換(IAAPiecewiseAffine)

* imgaugヘルパー：ランダム4点透視変換(IAAPerspective)


# ToDo
以下の実行例は未実装です。

* RandomCropNearBBox
　→cropping_bboxの指定方法が良く分からなかったため確認中。
* Lambda
　→自由度が高いため例を検討中。

# Author
高橋かずひと(https://twitter.com/KzhtTkhs)

# License

albumentations-examples is under [MIT license](LICENSE.md).

# Albumentations License

The original part of Albumentations is distributed under the MIT license.

I pay tribute to his wonderful work.

Copyright (c) 2017 Buslaev Alexander、Alexander Parinov、Vladimir Iglovikov. Licensed under the [MIT license](LICENSE.md).

# Reference
https://github.com/albumentations-team/albumentations
