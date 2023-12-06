# RubberSheet Floating-Finger 

## 概要
第24回計測自動制御学会システムインテグレーション部門講演会(SI2023)において発表．<br>
発表タイトル：**柔軟膜を用いたオープンソースなフローティングフィンガー機構**

<!-- ![Overview](/images/SI2023_fig_overview.png) -->
<img width="50%" src="/images/SI2023_fig_overview.png">

## パーツ
- ipt：inventor向けCADデータ (.ipt, .iam)
- step：STEPファイル (.stp)
- 組み立て後のデータ：RSFF_assembly_1_v3_clearance

### 近接覚センサ：TK-01
製品URL：https://www.thinker-robotics.co.jp/

### センサカバー
該当CADファイル：RSFF_cover_1_v3_clearance\
作成方法：研究室では以下の2種類の3Dプリンターで作成．いずれの場合でも運用可能であることを確認．
  1. **光造形式3Dプリンター (AGILISTA-3200)**
     - モデル材：AR-M2
     - サポート材：AR-S1
  1. **FDM式3Dプリンター (Zortrax M200 Plus)**
     - フィラメント：Z-ULTRAT (ABS系樹脂)
<img width="20%" src="\images\RSFF_sensor_cover.png">
\

### Floating-Fingerの基部
該当CADファイル：RSFF_cover_2_v2_clearance\
作成方法：センサカバーと同じ
<img width="20%" src="\images\RSFF_base.png">
\

### 柔軟膜
該当CADファイル：RubberSheet_1
材料：市販の飴ゴムシート　[購入先リンク](https://www.monotaro.com/g/01013365/?t.q=%E9%A3%B4%E3%82%B4%E3%83%A0%E3%82%B7%E3%83%BC%E3%83%88)\
作成方法：RubberSheet_1を3Dプリンターで印刷したパーツをもとに切り取る
<img width="20%" src="\images\RSFF_rubber_sheet.png">
\

### 爪
該当CADファイル：RSFF_tip_metal_1\
素材：アルミニウム\
作成方法：meviyを利用し外注　[meviyリンク](https://meviy.misumi-ec.com/ja-jp/)
<img width="20%" src="\images\RSFF_tip.png">
\

### 爪と柔軟膜の接続部分
該当CADファイル：RSFF_tip_mount_1\
作成方法：センサカバーと同じ
<img width="20%" src="\images\RSFF_tipmount.png">
\

### 反射板
該当CADファイル：RSFF_reflector_v2\
作成方法：センサカバーと同じ
<img width="20%" src="\images\RSFF_reflector.png">
\

### COBOTTAの手先との接続部分
該当CADファイル：RSFF_mount_1_clearance, RSFF_mount_1_clearance_MIR1\
作成方法：センサカバーと同じ
<img width="20%" src="\images\RSFF_mount.png">
\

## 道具
- ハサミ
- ボルト(M2×10)
- ナット(M2)
- 瞬間接着剤

## 組み立て手順

<!-- ![組み立て](/images/SI2023_fig_CAD_2.png) -->
<img width="50%" src="/images/SI2023_fig_CAD_2.png">



## 備考
- センサカバーにはセンサ基板に対して約0.2mmのクリアランスを設けている．
- 本研究は株式会社Thinkerとの共同研究の一環として実施された．

