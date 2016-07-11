# Kumamoto-shi
下载2016年4月16日熊本地震的数据，因为是uncorrected数据，
所以需要用matlab来process
程序的使用流程如下：
boreholedata   % 调用readborehole程序读入加速度数据
ampra          % 计算地表和钻孔底部幅值谱的比值
