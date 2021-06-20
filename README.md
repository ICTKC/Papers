#### 双过程计算要解决的问题

* 1. System1基本可以认为是预训练+特定的网络结构
* 2. System2是形式，是符号，嵌入表示，还是一个图？
*     - （2.1）规则从哪儿来？
*         - RNNLogic: Learning logic rules for reasoning on kg 
*     - （2.2）基于逻辑的简单编码：逻辑符号用soft logic编码
*         - 
*     - （2.3）基于实例的网络：用逻辑符号进行数据增强，利用增强后的数据训练一个网络，例如异或操作。可能一个规则可能就是一个网络
*     - （2.4）基于形式结构的网络：逻辑符号用图网络表示，例如自动数学证明
*     - （2.5）符号表示，逻辑运算推理机操作
*         - 
* 3. System2如何和System1结合？
*     - （3.1）编码后嵌入编码或解码阶段
*     - （3.2）多网络形成复杂模型结构
*         - 将System2逐步扩展成网络，但基于已知可能的逻辑链知道推理链的构造
*     - （3.3）teacher-student框架
*         - 
*     - （3.4）诱因学习框架
* 4. 什么时候唤起System2？
*     - （5.1）门控机制
*     - （5.2）参考[Dual-process theories - a metacognitive perspective.pdf]
* 5. System1和system2在具体不同任务中的形式？
*     - （6.1）检索：
*     - 问题 - 多跳阅读理解属于什么问题？？检索？
*     

#### 1. 双过程计算基础理论介绍
* 双过程理论综述[https://www.sciencedirect.com/topics/psychology/dual-process-theory](https://www.sciencedirect.com/topics/psychology/dual-process-theory)
* [Dual-process theories- a metacognitive perspective.pdf](https://github.com/ICTKC/MustReadPapers_DPC/files/6682304/Dual-process.theories-.a.metacognitive.perspective.pdf)



#### 2. 神经符号计算
* [Neural-Symbolic Computing- An Effective Methodology for Principled Integration of Machine Learning and Reasoning.pdf](https://github.com/ICTKC/MustReadPapers_DPC/files/6682298/Neural-Symbolic.Computing-.An.Effective.Methodology.for.Principled.Integration.of.Machine.Learning.and.Reasoning.pdf)


#### 谓词逻辑+神经网络
* [Harnessing Deep Neural Networks with Logic Rules.pdf](https://github.com/ICTKC/MustReadPapers_DPC/files/6682300/Harnessing.Deep.Neural.Networks.with.Logic.Rules.pdf)
* [[aaai 2019] DeepLogic - Towards End-to-End Differentiable Logical Reasoning.pdf](https://github.com/ICTKC/MustReadPapers_DPC/files/6682314/aaai.2019.DeepLogic.-.Towards.End-to-End.Differentiable.Logical.Reasoning.pdf) 
* [[icml 2019] SATNet- Bridging deep learning and logical reasoning using a differentiable satisfiability solver .pdf](https://github.com/ICTKC/MustReadPapers_DPC/files/6682316/icml.2019.SATNet-.Bridging.deep.learning.and.logical.reasoning.using.a.differentiable.satisfiability.solver.pdf)
* [[jair 2020] Ontology Reasoning with Deep Neural Networks.pdf](https://github.com/ICTKC/MustReadPapers_DPC/files/6682317/jair.2020.Ontology.Reasoning.with.Deep.Neural.Networks.pdf)
* [[nips 2017] Differentiable Learning of Logical Rules for Knowledge Base Reasoning.pdf](https://github.com/ICTKC/MustReadPapers_DPC/files/6682318/nips.2017.Differentiable.Learning.of.Logical.Rules.for.Knowledge.Base.Reasoning.pdf)
* [[nips 2019] Bridging Machine Learning and Logical Reasoning by Abductive Learning.pdf](https://github.com/ICTKC/MustReadPapers_DPC/files/6682319/nips.2019.Bridging.Machine.Learning.and.Logical.Reasoning.by.Abductive.Learning.pdf)
* [How to represent part-whole hierarchies in a neural network.pdf](https://github.com/ICTKC/MustReadPapers_DPC/files/6682320/How.to.represent.part-whole.hierarchies.in.a.neural.network.pdf)
[TensorLog  A Probabilistic Database Implemented Using Deep-Learning Infrastructure.pdf](https://github.com/ICTKC/MustReadPapers_DPC/files/6682321/TensorLog.A.Probabilistic.Database.Implemented.Using.Deep-Learning.Infrastructure.pdf)



#### 图神经网络
* [[ijcai20] Graph Neural Networks Meet Neural-Symbolic Computing- A Survey and Perspective.pdf](https://github.com/ICTKC/MustReadPapers_DPC/files/6682301/ijcai20.Graph.Neural.Networks.Meet.Neural-Symbolic.Computing-.A.Survey.and.Perspective.pdf)
