# Linear-Regression-Using-Gradient-Descent

## 概要
勾配降下法と確率的勾配降下法を用いてパラメーターを推定し線形回帰モデルを作成する。


## 作業手順
- ダミーデータの作成
  - 簡易的なダミーデータを作成するため、xを標準正規分布、yをy=5.0*x+10+ノイズ（ノイズも標準正規分布から得られる乱数）として作成
  - 最終的に推定されるパラメーターの検算をできるようにしておく
  
- 残差の二乗和を算出する関数を作成
  - 任意の傾き（alpha）と切片（beta）が入力値

- 目的関数をalphaとbetaに関して偏微分して得られる勾配の関数を作成
  - 任意の傾き（alpha）と切片（beta）が入力値

- 目的関数が最小になるようなalphaとbeta、更新過程での残差の二乗和を出力する関数を作成
  - alphaとbetaの初期値、学習率、エポック数が入力値

- 上記で算出されたalphaとbetaを用いて線形回帰モデルをプロット
