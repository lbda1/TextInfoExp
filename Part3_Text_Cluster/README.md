###   数据说明

data_offline文件夹包含200 economy 类，200个sports类，200个environment类，50个other类，为线下做试验的数据集，

id2class.txt为data_offline文件夹中每个文件对应的类别，以此可以比较聚类效果。

id2class_test.txt为data_test文件夹中每个文件对应的类别。

data_test 为测试的数据集，需要上交此数据集的聚类结果。

里面具体的聚类读错数据，但是里面的tfidf等方法可以使用

修改的地方
（1）data_offline 改为 data
（2）先运行get_res.py中的get_text()方法
（3）再运行TextCluster.py

