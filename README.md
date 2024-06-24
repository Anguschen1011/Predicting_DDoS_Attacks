#### 資訊工程學系(1121)
# 無線網路(1121_B4CS030015A)

我們使用的第一個資料集選擇了UNSW-nb15資料集作為本次實驗的基礎。該資料集來自澳洲新南威斯大學網路靶場實驗室，包含兩百五十多萬筆資料，每筆資料都有諸如編號(ID)、使用協定(proto)、使用服務(service)等總共45個特徵。  由於第一個資料集沒有DDoS的類別，加上資料集有些久遠，所以我們使用第二個資料集NF-BoT-IoT資料集，數據的特徵是從公開可用的pcap文件中提取的，並且流量被標記為它們相應的攻擊類別。 最後分別透過訓練我們所選模型(SVM, KNN, CNN, RNN)，去辨別是否有網路攻擊、Dos攻擊(使用UNSW-nb15資料集);辨別是否有網路攻擊、DDoS攻擊(使用NF-BoT-IoT資料集)。

We used the UNSW-NB15 dataset as the foundation for our first experiment. This dataset comes from the Cyber Range Lab at the University of New South Wales in Australia and contains over 2.5 million records. Each record has a total of 45 features, such as ID, protocol used (proto), service used (service), etc.Since the first dataset does not include the DDoS category and the dataset is somewhat dated, we utilized a second dataset, the NF-BoT-IoT dataset. The features of this dataset were extracted from publicly available pcap files, and the traffic was labeled according to their respective attack categories.Finally, we trained our selected models (SVM, KNN, CNN, RNN) to identify whether there are network attacks and DoS attacks using the UNSW-NB15 dataset, and to identify whether there are network attacks and DDoS attacks using the NF-BoT-IoT dataset.


