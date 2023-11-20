# RubberSheet Floating-Finger 

## 概要
第24回計測自動制御学会システムインテグレーション部門講演会(SI2023)において発表．<br>
発表タイトル：**柔軟膜を用いたオープンソースなフローティングフィンガー機構**

<!-- ![Overview](/images/SI2023_fig_overview.png) -->
<img width="50%" src="/images/SI2023_fig_overview.png">

## パーツ

### 近接覚センサ：TK-01
製品URL：https://www.thinker-robotics.co.jp/

### センサカバー
該当CADファイル：\
作成方法：研究室では以下の2種類の3Dプリンターで作成．いずれの場合でも運用可能であることを確認．
  1. **光造形プリンター (AGILISTA-3200)**
     - モデル材：AR-M2
     - サポート材：AR-S1
  1. **FDM式3Dプリンター (Zortrax M200 Plus)**
     - フィラメント：Z-URTLAT (ABS系樹脂)

### Floating-Fingerの基部
該当CADファイル：\
作成方法：センサカバーと同じ

### 柔軟膜
該当CADファイル：\
材料：市販の飴ゴムシート　[購入先リンク](https://www.monotaro.com/g/01013365/?t.q=%E9%A3%B4%E3%82%B4%E3%83%A0%E3%82%B7%E3%83%BC%E3%83%88)\
作成方法：（CADファイル）を3Dプリンターで印刷したパーツをもとに切り取る

### 爪
該当CADファイル：\
素材：アルミニウム\
作成方法：meviyを利用し外注 [meviyリンク](https://meviy.misumi-ec.com/ja-jp/)

### 爪と柔軟膜の接続部分
該当CADファイル：\
作成方法：センサカバーと同じ

### 反射板
該当CADファイル：\
作成方法：センサカバーと同じ

### COBOTTAの手先との接続部分
該当CADファイル：\
作成方法：センサカバーと同じ

## 道具
- ハサミ
- ボルト(M2×10)
- ナット(M2)
- 瞬間接着剤(アロンアルファを使用)

## 組み立て手順

<!-- ![組み立て](/images/SI2023_fig_CAD_2.png) -->
<img width="50%" src="/images/SI2023_fig_CAD_2.png">



## 備考
- センサカバーにはセンサ基板に対して約0.2mmのクリアランスを設けている．
- 本研究は株式会社Thinker との共同研究の一環として実施された．

