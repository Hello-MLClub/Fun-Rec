本教程主要是针对具有机器学习基础并想找推荐算法岗位的同学。教程内容由推荐系统概述、推荐算法基础、推荐系统实战和推荐系统面经四个部分组成。本教程对于入门推荐算法的同学来说，可以从推荐算法的基础到实战再到面试，形成一个闭环。每个部分的详细内容如下：

- **推荐系统概述。** 这部分内容会从推荐系统的意义及应用，到架构及相关的技术栈做一个概述性的总结，目的是为了让初学者更加了解推荐系统。
- **推荐系统算法基础。** 这部分会介绍推荐系统中对于算法工程师来说基础并且重要的相关算法，如经典的召回、排序算法。随着项目的迭代，后续还会不断的总结其他的关键算法和技术，如重排、冷启动等。
- **推荐系统实战。** 这部分内容包含推荐系统竞赛实战和新闻推荐系统的实践。其中推荐系统竞赛实战是结合阿里天池上的新闻推荐入门赛做的相关内容。新闻推荐系统实践是实现一个具有前后端交互及整个推荐链路的项目，该项目是一个新闻推荐系统的demo没有实际的商业化价值。
- **推荐系统算法面经。** 这里会将推荐算法工程师面试过程中常考的一些基础知识、热门技术等面经进行整理，方便同学在有了一定推荐算法基础之后去面试，因为对于初学者来说只有在公司实习学到的东西才是最有价值的。

为了方便学习和交流，**我们建立了学习社区（微信群+知识星球）**

分享前沿技术资讯、算法实战项目、求职内推、算法竞赛、算法面试攻略、面试经验交流(校招、社招、实习)等，与 10000+来自港大、北大、清华、中科院、CMU、腾讯、百度、微软等名校名企开发者互动交流~

![image](https://user-images.githubusercontent.com/76510785/235394137-a42c8150-cb61-4b4a-afa5-252dc9736b9b.png)

一个专注于分享大模型、算法实战、学术论文、面试攻略的公众号，免费提供技术交流群，关注公众号：机器学习社区，与我们一起成长。

![image](https://user-images.githubusercontent.com/76510785/235394150-dff32753-00b4-481a-9901-9ce8a9a7b068.png)

                                                                                                               
## 内容导航 
### 推荐系统概述
- [推荐系统的意义](docs/ch01/ch1.1.md)
- [推荐系统架构](docs/ch01/ch1.2.md)
- [推荐系统技术栈](docs/ch01/ch1.3.md)

### 推荐系统算法基础 
#### **经典召回模型**
- **基于协同过滤的召回**
  - [UserCF](docs/ch02/ch2.1/ch2.1.1/usercf.md)
  - [ItemCF](docs/ch02/ch2.1/ch2.1.1/itemcf.md)
  - [Swing](docs/ch02/ch2.1/ch2.1.1/Swing.md)
  - [矩阵分解](docs/ch02/ch2.1/ch2.1.1/mf.md)
- **基于向量的召回**
    - [FM召回](docs/ch02/ch2.1/ch2.1.2/FM.md)
    - **item2vec召回系列**
        - [word2vec原理](docs/ch02/ch2.1/ch2.1.2/word2vec.md)
        - [item2vec召回](docs/ch02/ch2.1/ch2.1.2/item2vec.md)
        - [Airbnb召回](docs/ch02/ch2.1/ch2.1.2/Airbnb.md)
    - [YoutubeDNN召回](docs/ch02/ch2.1/ch2.1.2/YoutubeDNN.md)
    - **双塔召回**
        - [经典双塔](docs/ch02/ch2.1/ch2.1.2/DSSM.md)
        - [Youtube双塔](docs/ch02/ch2.1/ch2.1.2/YoutubeTwoTower.md)
    - **图召回**
        - [EGES](docs/ch02/ch2.1/ch2.1.3/EGES.md)
        - [PinSAGE](docs/ch02/ch2.1/ch2.1.3/PinSage.md)
    - **序列召回**
        - [MIND](docs/ch02/ch2.1/ch2.1.4/MIND.md)
        - [SDM](docs/ch02/ch2.1/ch2.1.4/SDM.md)
- **树模型召回**
    - [TDM](docs/ch02/ch2.1/ch2.1.5/TDM.md)

#### **经典排序模型**
- **[GBDT+LR](docs/ch02/ch2.2/ch2.2.1.md)**
- **特征交叉**
    - [FM](docs/ch02/ch2.2/ch2.2.2/FM.md)
    - [PNN](docs/ch02/ch2.2/ch2.2.2/PNN.md)
    - [DCN](docs/ch02/ch2.2/ch2.2.2/DCN.md)
    - [AutoInt](docs/ch02/ch2.2/ch2.2.2/AutoInt.md)
    - [FiBiNET](docs/ch02/ch2.2/ch2.2.2/FiBiNet.md)
- **WideNDeep系列**
    - **[Wide&Deep](docs/ch02/ch2.2/ch2.2.3/WideNDeep.md)**
    - **改进Deep侧**
        - [NFM](docs/ch02/ch2.2/ch2.2.3/NFM.md)
        - [AFM](docs/ch02/ch2.2/ch2.2.3/AFM.md)
    - **改进Wide侧**
        - [DeepFM](docs/ch02/ch2.2/ch2.2.3/DeepFM.md)
        - [xDeepFM](docs/ch02/ch2.2/ch2.2.3/xDeepFM.md)
- **序列模型**
    - [DIN](docs/ch02/ch2.2/ch2.2.4/DIN.md)
    - [DIEN](docs/ch02/ch2.2/ch2.2.4/DIEN.md)
    - [DSIN](docs/ch02/ch2.2/ch2.2.4/DSIN.md)
- **多任务学习**
    - [多任务学习概述](docs/ch02/ch2.2/ch2.2.5/2.2.5.0.md)
    - [ESMM](docs/ch02/ch2.2/ch2.2.5/ESMM.md)
    - [MMOE](docs/ch02/ch2.2/ch2.2.5/MMOE.md)
    - [PLE](docs/ch02/ch2.2/ch2.2.5/PLE.md)

### 推荐系统实战

#### **竞赛实践(天池入门赛-新闻推荐【建议使用tf1.14】)**
- **文档**
  - [赛题理解&Baseline](docs/ch03/ch3.1/markdown/ch3.1.1.md)
  - [数据分析](docs/ch03/ch3.1/markdown/ch3.1.2.md)
  - [多路召回](docs/ch03/ch3.1/markdown/ch3.1.3.md)
  - [特征工程](docs/ch03/ch3.1/markdown/ch3.1.4.md)
  - [排序模型&模型融合](docs/ch03/ch3.1/markdown/ch3.1.5.md)

#### **新闻推荐系统实践**
- [特别说明(必看)](docs/ch03/ch3.2/3.2.md)
- **视频**
  - [新闻推荐系统流程的构建视频讲解](https://datawhale.feishu.cn/minutes/obcnzns778b725r5l535j32o)
- **文档**
  - **离线物料系统的构建**
      - [Mysql基础](docs/ch03/ch3.2/3.2.1.1.md)
      - [MongoDB基础](docs/ch03/ch3.2/3.2.1.2.md)
      - [Redis基础](docs/ch03/ch3.2/3.2.1.3.md)
      - [Scrapy基础及新闻爬取实战](docs/ch03/ch3.2/3.2.1.4.md)
      - [自动化构建用户及物料画像](docs/ch03/ch3.2/3.2.1.5.md)
  - **前后端基础及交互**
      - [前端基础及Vue实战](docs/ch03/ch3.2/3.2.2.1.md)
      - [flask简介及基础](docs/ch03/ch3.2/3.2.2.2.md)
      - [前后端交互](docs/ch03/ch3.2/3.2.2.3.md)
  - [推荐系统流程的构建](docs/ch03/ch3.2/3.2.3.md)
  - **召回**
      - [规则类召回](docs/ch03/ch3.2/3.2.4.1.md)
      - [YoutubeDNN召回](docs/ch03/ch3.2/3.2.4.2.md)
      - [DSSM召回](docs/ch03/ch3.2/3.2.4.3.md)
  - [DeepFM排序模型](docs/ch03/ch3.2/3.2.5.md)
  - [重排(打散策略)](docs/ch03/ch3.2/3.2.6.md)

### 推荐系统算法面经
  - [ML与DL基础](docs/ch04/ch4.1.md)
  - [推荐模型相关](docs/ch04/ch4.2.md)
  - [热门技术相关](docs/ch04/ch4.3.md)
  - [业务场景相关](docs/ch04/ch4.4.md)
  - [HR及其他](docs/ch04/ch4.5.md)


### 备注

[2.1 竞赛实践(天池入门赛-新闻推荐)](https://tianchi.aliyun.com/competition/entrance/531842/forum)

<div align=center>
    <img src="http://ryluo.oss-cn-chengdu.aliyuncs.com/图片image-20211213165802957.png" alt="image-20211213165802957" width="800px" />
    <img src="http://ryluo.oss-cn-chengdu.aliyuncs.com/图片image-20211213165847593.png" alt="image-20211213165847593" width="800px" />
</div>

**2.2 新闻推荐系统实践前端展示和后端逻辑(项目没有任何商用价值仅供入门者学习)**

<div align=center> 
    <img src="http://ryluo.oss-cn-chengdu.aliyuncs.com/图片image-20211205142026937.png" alt="image-20211205142026937" width="800px" />
    <img src="http://ryluo.oss-cn-chengdu.aliyuncs.com/图片Fun-Rec新闻推荐系统.png" alt="Fun-Rec新闻推荐系统" width="810px" />
</div>

