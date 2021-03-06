# 柔軟デュアルマニピュレータの省エネルギー振動制御に関わる研究

旭川高専専攻科2年次に実施した研究です．

## 1. 研究背景
　振動制御問題は柔軟宇宙構造物や軽量ロボットなど，航空宇宙とロボット工学の分野で広く研究されている課題である．振動は機械製品の信頼性，品質，精度，寿命などを損なうばかりか，安全性，居住性，人体に与える振動障害や騒音公害等，様々な問題を引き起こす．特に，産業用ロボットは，工場のオートメーション化に伴い単純な繰り返し作業や精密さを要求される作業等を人に成り代わり行う労働力として普及している．したがって，ロボットマニピュレータ高速化ならびに高精度化には振動制御技術は必須である．さらには，近年のCO2削減の観点からロボットマニピュレータのさらなる省エネルギー化は国内外から望まれている研究課題である．

## 2. 研究目的
　本研究では，1つのモータハブに2つの固有振動数が異なる柔軟リンクが搭載されたシステムの省エネルギーフィードフォワード制御に関する研究を試みる．具体的には，この柔軟デュアルマニピュレータの Point-to-Potin 制御問題を扱い，位置決め後の２つのリンクの振動を同時に抑制させ，かつ，駆動エネルギーを最小化する関節角の軌道生成法を提案する．そして，数値シミュレーションから提案手法の有効性を検証する．1つの回転関節の運動から，固有振動数の異なる2つのリンクの振動を低消費エネルギーで抑制させることが本研究の特徴である.

## 3. 手法・手段
　まず，理論解析から制御対象である柔軟デュアルマニピュレータの運動方程式を導出する．次に，モデル実験装置を製作し，パラメータ同定実験を実施し，運動方程式のパラメータを正確に求める．フィードフォワード制御として，Point-to-Point作業を想定した初期位置から目的位置までの旋回軌道を定義し，位置決め後の残留振動を抑制させかつ省エネルギー駆動が両立される最適軌道の生成を試みる．ここで，旋回軌道をサイクロイド関数とガウス関数の結合により表現する．このとき，軌道はガウス関数内のパラメータに依存するので，粒子群最適化を適用して残留振動と省エネルギー化が両立されるようにパラメータをチューニングする．この粒子群最適化に基づくアルゴリズムから省エネルギーフィードフォワード制御がシミュレーションで表現できる．最後にモデル実験を実施し，シミュレーション結果との比較検討の過程から，提案手法の有効性及び実現性を検証する．

## 4. シミュレーションデータ・実験データ
[URL](https://drive.google.com/drive/folders/1CsvhLRqF2h3PsAYAG1A36q-I_iOkLmCv?usp=sharing)