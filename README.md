
使用 RNN、LSTM、DENSE、MLP、Conv1D + LSTM 等模型預測時間序列資料
![image](https://github.com/user-attachments/assets/2a7c95f1-9184-4852-9e87-ce2758adf1a9)

![image](https://github.com/user-attachments/assets/70087d53-3ad8-4be2-9969-fffd6d55c34e)

| Model           | MAE      | MSE        | RMSE     | MAPE    | MASE    | R²      |
|---------------|---------|-----------|---------|--------|--------|--------|
| Simple RNN    | 2.7882  | 90.9026   | 9.5343  | 2.9118 | 1.1644 | 0.9316 |
| LSTM          | 2.9804  | 86.9124   | 9.3227  | 3.0218 | 1.2447 | 0.9346 |
| Dense         | 3.6241  | 91.3322   | 9.5568  | 3.7174 | 1.5135 | 0.9313 |
| MLP           | 3.9830  | 88.0190   | 9.3818  | 3.9724 | 1.6634 | 0.9338 |
| Conv1D + LSTM | 10.4526 | 270.3742  | 16.4431 | 9.4594 | 4.3652 | 0.7966 |
