# Titanic-alive-analysis
## Keras-Titanic introduce:<br>
`下載鐵達尼號旅客資料集`<br>
`使用Pandas dataframe讀取資料並進行處理`<br>
原先資料：<br>
<img src="https://github.com/buloobuloo/Titanic-alive-analysis/blob/master/IMG/%E6%88%AA%E5%9C%96%202020-05-15%20%E4%B8%8B%E5%8D%882.13.41.png"><br>
處理後：<br>
<img src="https://github.com/buloobuloo/Titanic-alive-analysis/blob/master/IMG/%E6%88%AA%E5%9C%96%202020-05-15%20%E4%B8%8B%E5%8D%882.13.54.png"><br>
`轉換為array`<br>
`標準化`<br>
`將資料分為訓練資料與測試資料`<br>
## Keras-Titanic MLP
`Keras-Titanic introduce準備資料`<br>
`create model`<br>
`Train model`<br>
結果：<br>
<img src="https://github.com/buloobuloo/Titanic-alive-analysis/blob/master/IMG/%E6%88%AA%E5%9C%96%202020-05-15%20%E4%B8%8B%E5%8D%882.16.44.png"> <img src="https://github.com/buloobuloo/Titanic-alive-analysis/blob/master/IMG/%E6%88%AA%E5%9C%96%202020-05-15%20%E4%B8%8B%E5%8D%882.16.50.png"><br>
`評估模型準確率`<br>
0.807272732257843<br>
`加入Jack & Rose資料`<br>
<img src="https://github.com/buloobuloo/Titanic-alive-analysis/blob/master/IMG/%E6%88%AA%E5%9C%96%202020-05-15%20%E4%B8%8B%E5%8D%882.17.04.png"><br>
整理後：<br>
<img src="https://github.com/buloobuloo/Titanic-alive-analysis/blob/master/IMG/%E6%88%AA%E5%9C%96%202020-05-15%20%E4%B8%8B%E5%8D%882.17.12.png"><br>
結果：<br>
<img src="https://github.com/buloobuloo/Titanic-alive-analysis/blob/master/IMG/%E6%88%AA%E5%9C%96%202020-05-15%20%E4%B8%8B%E5%8D%882.17.22.png"><br>
`其他結果（生存率高卻沒有存活）`<br>
<img src="https://github.com/buloobuloo/Titanic-alive-analysis/blob/master/IMG/%E6%88%AA%E5%9C%96%202020-05-15%20%E4%B8%8B%E5%8D%882.17.39.png">
