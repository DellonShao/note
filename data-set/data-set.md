# 数据中心开源数据集及相关论文整理
近些年，随着云计算的快速兴起，各大公司都纷纷建立自己的数据中心，微软在数据中心方面的投入超过了 150 亿，阿里巴巴仅在张北的数据中心就投入了 180 亿。在数据中心的高额投入下，机器的资源使用效率却面临了很大的问题。以 Google 的数据中心为例，其生产环境下机器的平均 CPU 利用率只有 20%，Amazon 的 AWS EC2 平均 CPU 利用率只有 7%~17%。

为了更好的解决数据中心所面临的挑战，各大公司纷纷开始公开自己集群的数据集，希望通过数据集的方式，让研究者更好的了解在大规模的场景下所遇到的问题。
## Google
- [https://github.com/google/cluster-data](https://github.com/google/cluster-data)
- 公开时间：2011年
- 数据集时间跨度：30天
## Microsoft Azure
- [https://github.com/Azure/AzurePublicDataset](https://github.com/Azure/AzurePublicDataset)
- 公开时间：2017年
- 数据集时间跨度：30天
## Alibaba Co-located cluster
- [https://github.com/alibaba/clusterdata](https://github.com/alibaba/clusterdata)
- 公开时间：2017年（1000+台机器，24小时数据）、2018年（4000+台机器，9天的数据）
- 均为阿里内部私有云集群的数据
## Two sigma、LANL Mustang、LANL OpenTrinity
- [https://www.pdl.cmu.edu/ATLAS/](https://www.pdl.cmu.edu/ATLAS/)
- 数据集时间跨度：9个月、5年、3个月
# 数据分析相关论文
## Google
- Heterogeneity and Dynamicity of Clouds at Scale: Google Trace Analysis（SoCC 2012）
## Microsoft
- Resource Central: Understanding and Predicting Workloads for Improved Resource Management in Large Cloud Platforms（SOSP 2017）
## Alibaba
- Who Limits the Resource Efficiency of My Datacenter: An Analysis of Alibaba Datacenter Traces（IWQoS 2019
- The Elasticity and Plasticity in Semi-Containerized Co-locating Cloud Workload: a View from Alibaba Trace（SoCC 2018）
- Characterizing Co-located Datacenter Workloads: An Alibaba Case Study（APsys 2018）
- Imbalance in the Cloud: an Analysis on Alibaba Cluster Trace（BIGDATA 2017）
## Two sigma
- On the diversity of cluster workloads and its impact on research results（ATC 2018）
