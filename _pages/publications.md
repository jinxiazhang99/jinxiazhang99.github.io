出发点Process reward is not only a learning objective but also an online control signal for multimodal state evolution.

标题要不要改成：Visual State Refinement
----------
Industrial anomaly QA需要：

不是识别，而是：

evidence inspection。

第二段

现有MLLM问题：

visual representation frozen after encoding。

第三段

现有解决：

RL
PRM
visual refinement

但三者割裂。

第四段

提出：

RILO：

reward → visual state evolution

这样逻辑更强。
-------------
如果补强“为什么过程奖励能够指导视觉重新观察”，这篇论文的定位可以从：

工业异常QA增强方法

提升到：

MLLM过程反馈驱动多模态状态演化方法
--------------
为什么 reward score 可以代表视觉证据缺失？
reward来自：
answer correctness
lexical evidence compatibility
cross-field consistency
这些更多评价：

“语言输出是否合理”

而不是：

“视觉token哪里需要增强”。

Reviewer 可能攻击：

You assume linguistic reward can identify visual deficiency. Why?

----------
不要过度强调：

adaptive visual reasoning

建议强调：

trajectory-conditioned visual representation refinement

或者：

reward-guided visual evidence refinement

更准确。
------------------
缺少：

token-level evidence analysis

建议增加：

例如：

modulation weight vs defect region overlap

---------------
你的创新来自：

PRM
visual refinement

应该增加：

视觉推理类：

iterative visual reasoning
latent visual token methods