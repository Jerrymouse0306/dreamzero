# README_self
## debug记录

## 学习笔记
### 整体框架
1. /docs中包含三个文本，有些readme里面没写的内容可以去那里查找使用方式。

    1.1 docs/DATASET_TO_GEAR_AND_TRAIN.md中记录了如何用新的训练集训练dreamzero

    1.2 docs/DROID_CONVERSION.md 是一个专门说明 DROID 数据集转换流程的文档。

    1.3 docs/WAN22_BACKBONE.md 是一个专门说明 WAN2.1 视频扩散模型骨干网络的文档。

2. /eval_utils这是用来评估和测试的脚本

    2.1 policy_server.py 托管策略服务

    2.2 policy_client.py 提供客户端接口

    2.3 run_sim_eval.py 实现具体的模拟评估逻辑

    这个文件夹里的代码是DreamZero 采用基于 WebSocket 的分布式客户端-服务器架构，用于支持大规模模型的实时推理服务。该架构实现了高效的观察-动作通信、分布式计算协调和多客户端会话管理。

3. groot是模型的核心代码

4. scripts是常用的脚本，例如训练之类的在这里找。

### /groot文件夹

### /scripts文件夹


