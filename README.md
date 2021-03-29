# Flowers-Recognition
## 今回のやったこと
様々なモデルを学習し、Light-gbmでアンサンブル  
アンサンブルで効果が出やすいように、できるだけ多様なモデルを使用  
early stoppingを使用し、epoch数などハイパーパラメータの調整になるべく時間がかからないように  
その他、スケジューラー等は前回コンペを参考にいくつか試してみた

### 学習させてみたモデル
* Vision Transformer (resnetのハイブリッド版も使用)
* SE-ResNeXt
* SK-ResNeXt
* Efficientnet_b2~b4
* Inception_Resnet_v2

### 最終提出のアンサンブルに使用したモデル
* Vision Transformer (vit_base_patch16_224)  
* SE-ResNeXt (seresnext50_32x4d)
* Efficientnet_b2 (tf_efficientnet_b2)

#### 謝辞
今回は,前回のgalaコンペの村上さんと田中さんのコードにかなり助けて頂きました。ありがとうございます！