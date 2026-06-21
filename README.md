# ett-oil-temperature-forecast
ETTデータセット（ETTh1）を用いて、変圧器のオイル温度（OT）の1時間先予測を行うPoC。線形回帰・SimpleLSTM（1層LSTM）・UNetResidualLSTMBlock（U-Net構造+残差接続）の3手法を比較検証。結果として、直前値（OT_lag1）を用いたシンプルな線形回帰が最も高精度（テストRMSE 0.65℃）となり、複雑な深層学習モデルが常に優位とは限らないことを示した。
