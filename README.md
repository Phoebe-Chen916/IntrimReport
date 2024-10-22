# Pytorch入門--詳解Mnist手寫字識別
南華大學跨領域-人工智慧期中報告 11225019黃泊諍 11225027陳姵均 
<br/>
內容參考學習出處：        
原文链接：https://blog.csdn.net/weixin_44888196/article/details/125947800
# 什麼是Mnist?
MNIST 是計算機視覺領域中最為基礎的一個數據集。  
MNIST 數據集（Mixed National Institute of Standards and Technology database）是由美國國家標準與技術研究院收集整理的大型手寫數字數據集，包含了 60,000 個樣本的訓練集以及 10,000 個樣本的測試集。MNIST 中所有樣本都會將原本 28*28 的灰度圖轉換為長度為 784 的一維向量作為輸入，其中每個元素分別對應了灰度圖中的灰度值。MNIST 使用一個長度為 10 的向量作為該樣本所對應的標籤，其中向量索引值對應了該樣本以該索引為結果的預測概率。
# 代碼實現
<h4>導入Python庫<h4/>
![image]
