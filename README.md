# albumentations-examples
albumentations-examplesは画像拡張ライブラリAlbumentationsのJupyter上での実行例集です。

# Requirement
 
* OpenCV 3.4.2(or later)
* Albumentations 0.4.5

# Usage

ぼかし(Blur)
垂直反転(VerticalFlip)
水平反転(HorizontalFlip)
水平垂直反転(Flip)
ノーマライズ(Normalize)
行列転置(Transpose)
ランダムクロップ(RandomCrop)
ランダムガンマ補正(RandomGamma)
ランダム90度回転(RandomRotate90) ※N回90度回転
ランダム回転(Rotate)
ランダムアフィン変換(ShiftScaleRotate) ※ランダムスケール、ランダム回転
センタークロップ(CenterCrop)
光学ひずみ(OpticalDistortion)
グリッドひずみ(GridDistortion)
弾性変形(ElasticTransform)
ランダムグリッドシャッフル(RandomGridShuffle)
HSV変換(HueSaturationValue)
パッド付与(PadIfNeeded)
RGBランダムシフト(RGBShift)
輝度ランダム変更(RandomBrightness)
コントラストランダム変更(RandomContrast)
モーションブラー付与(MotionBlur)
メディアンブラー付与(MedianBlur)
ガウシアンブラー付与(GaussianBlur)
ガウスノイズ付与(GaussNoise)
ガラスブラー付与(GlassBlur)
コントラスト制限付き適応ヒストグラム均等化(CLAHE)
RGBチャンネルランダムシャッフル(ChannelShuffle)
ピクセル値反転(InvertImg)
グレースケール化(ToGray)
セピア化(ToSepia)
JPEG圧縮劣化(JpegCompression)
WebP圧縮劣化(ImageCompression)
ランダムカットアウト(Cutout) ※正方形領域
ランダムカットアウト(CoarseDropout) ※矩形領域
float化(ToFloat) ※0.0～1.0
整数化(FromFloat)
切り抜き(Crop)
マスクを使用した切り抜き(CropNonEmptyMaskIfExists)
ランダムスケール(RandomScale)
マックススケーリング(LongestMaxSize)
ミニマムスケーリング(SmallestMaxSize)
リサイズ(Resize)
ランダムクロップ後、一定のサイズに再スケーリング(RandomSizedCrop)
ランダムクロップ後、一定のサイズに再スケーリング(RandomResizedCrop)
輝度およびコントラストのランダム変更(RandomSizedBBoxSafeCrop)
bboxを維持したランダムクロップ(RandomSizedBBoxSafeCrop)
ランダム雪シミュレート(RandomSnow)
．ランダム雨シミュレート(RandomRain) ※rain_type：None
ランダム霧シミュレート(RandomFog)
ランダム太陽シミュレート(RandomSunFlare)
ランダム影シミュレート(RandomShadow)
ランダムチャンネルドロップ(ChannelDropout)
ISOノイズ(ISONoise)
ソラリゼーション(Solarize) ※閾値を超えるピクセル値を反転
ヒストグラム平均化(Equalize)
ポスタリゼーション(Posterize) ※各カラーチャネルのビット数を減らす
ダウンスケール/アップスケールバックによる画質低下(Downscale)
ノイズ乗算(MultiplicativeNoise)
Fancy PCA
マスクドロップアウト(MaskDropout)
グリッドドロップアウト(GridDropout)

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
