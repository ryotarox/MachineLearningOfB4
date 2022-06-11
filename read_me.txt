〇hakohige.py 
　直近24時間分のlag変数を加えたRandomForest、RandomForest、直近24時間分のlag変数を加えたXGboost、XGBoost、直近24時間分のlag変数を加えたLightGBM、LightGBM、LSTM、SARIMAXで予測をおこなった結果と実際の答えとの間の相対値を集計して箱ひげ図にして一覧表示するプログラム。



〇発表スライドのためのグラフ.py
　直近24時間分のlag変数を加えたRandomForest、RandomForest、直近24時間分のlag変数を加えたXGboost、XGBoost、直近24時間分のlag変数を加えたLightGBM、LightGBM、LSTM、SARIMAXで予測をおこなった結果と実際の答えとの間の相対値を集計して箱ひげ図にして一覧表示するプログラム。
　表を用いて、最も良い値から三番目までの手法をそれぞれ表記するプログラム。
 
 
 
〇SARIMAX_24_predict
SARIMAXによる予測結果を地点別にbiasとbarでcsvファイルにそれぞれ保存されている。



〇LSTM_24_predict
LSTMによる予測結果を地点別にbiasとbarでcsvファイルにそれぞれ保存されている。



〇lgb_24_predict
LightGBMによる予測結果を地点別にbiasとbarでcsvファイルにそれぞれ保存されている。



〇xgb_24_predict
XGBoostによる予測結果を地点別にbiasとbarでcsvファイルにそれぞれ保存されている。



〇Landom_24_predict
RandomForestによる予測結果を地点別にbiasとbarでcsvファイルにそれぞれ保存されている。



〇rmse_var_total.py
それぞれの予測結果をrmseとvarで別に合計して表記しているプログラム。
HeatMapも表示するプログラム。



〇station_plot.py
ステーションごとに頻度プロットヒストグラムを表示するプログラム。



〇論文整形用.py
論文にのせた、直近24時間分のlag変数を加えたRandomForest、RandomForest、直近24時間分のlag変数を加えたXGboost、XGBoost、直近24時間分のlag変数を加えたLightGBM、LightGBM、LSTM、SARIMAX、の予測プログラムをまとめている。一部なので実行はできない。



〇研究セミナー_1028.py
直近24時間分のlag変数を加えたRandomForest、RandomForest、直近24時間分のlag変数を加えたXGboost、XGBoost、直近24時間分のlag変数を加えたLightGBM、LightGBM、LSTM、SARIMAX、の折れ線グラフを表記している。rmseそのままと絶対値を取ったものを載せているプログラム。



〇研究セミナー_0204.py
直近24時間分のlag変数を加えたRandomForest、RandomForest、直近24時間分のlag変数を加えたXGboost、XGBoost、直近24時間分のlag変数を加えたLightGBM、LightGBM、LSTM、SARIMAX、の予測結果を折れ線グラフでプロットするプログラム。月と地点ごとにグラフを作成している。



〇XGBoost_24_30data.py
XGBoostによる予測の実行プログラム。ここでXGBoostを動かしてる。



〇RandomForest_24_30data.py
RandomForestによる予測の実行プログラム。ここでRandomForestを動かしてる。



〇LightGBM_24_30data.py
LightGBMによる予測の実行プログラム。ここでLightGBMを動かしてる。



〇研究セミナー_1021.py
LandomForestによる試験的な実行プログラム。



〇研究セミナー_1014.py
いくつかの予測モデルによる結果の折れ線グラフ。
ヒストグラム。
当時の実験段階。



〇SARIMAX_24_30data.py
SARIMAXによる予測の実行プログラム。ここでSARIMAXを動かしてる。



〇LSTM_24_30data.py
LSTMによる予測の実行プログラム。ここでLSTMを動かしてる。



〇table_folder 
実験に使用した10ステーションの平均と分散の表がcsvで入っている。



〇LSTM_test_1217-コピー.py
LSTMを適用する最初の試験プログラム。試しにやってみたもの。



〇LSTM_test_1217.py
LSTM_test_1217-コピー.pyとほぼ同じ。



〇lightGBM_1224_コピー.py
lightGBMとRandomForestでの試験的なプログラムの適用。



〇status_test_0107.py
シミュレーション実験に使用したstatusファイルの欠損値確認のプログラム。
status.csvの形式の確認もしている。



〇test_3.2.1_kalman_filter.py
kalman_filterの適用を試みたプログラム。
試みただけ。



〇状態空間モデル_初回実装.py
状態空間モデルを初めて適用しようと試みたプログラム。
試みただけ。



〇lightGBM_1224.py
lightGBM_1224_コピー.pyとほぼ同じ。



〇SARIMAX_1224.py
SARIMAXの適用を試みているプログラム。
SARIMAX内の数値の調整なども行っていた。
statusデータに関して、トレンド、季節変動、その他に分けるプログラムもある。



〇XGBoost初回実装.py 
XGBoostの適用を初めて試みたプログラム。



〇SARIMAX_1217.py
SARIMAXの数値変更による違いを比較しているプログラム。



〇sarima_light_random_lstm_1210.py
AR、MA、SARIMA、lightgbm、RandomForestを初めて比較しているプログラム。
この時のlithtgbm、RandomForestは学習回数の関係で、過適合気味である。



〇LSTM1209.py
LSTMの構造やプログラムを動きを確かめながらの初回実装。



〇ARIMApredict.py
ARIMA、LSTMのお試し実装プログラム。



〇machine_learning.py
機械学習のための前処理をいろいろ試している。
lightGBMに適用してみたりもしている。



〇ar_apply.py
ARの試験適用をしているプログラム。
数値の調整による結果を可視化して確認している。



〇ar_apply_new.py
ar_apply.pyのつづき。


〇AR_test.py
このフォルダで初めて作成したファイル。
ARとMAの初回適用をおこなっている。




