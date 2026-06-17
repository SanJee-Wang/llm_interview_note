# 02.大语言模型架构

### 2.0 Agent 开发必备 LLM 基础

[00.AI Agent 开发所需 LLM 基础](</02.大语言模型架构/00.AI Agent开发所需LLM基础/00.AI Agent开发所需LLM基础.md> "00.AI Agent 开发所需 LLM 基础")

本节是 AI Agent 开发的主线入口，重点关注：

```text
LLM 的本质：基于上下文预测 token
Token、上下文窗口、成本和延迟
Temperature、top-p、top-k 对输出稳定性的影响
Embedding 在 RAG、搜索、聚类、推荐、分类中的作用
幻觉来源和工程缓解方式
```

如果目标是 AI Agent 应用开发，建议先按下面的主线顺序阅读。BERT、MoE、模型源码细节可以作为深入参考，不作为第一学习主线。

### 2.1 AI Agent 开发主线

[01.LLM Tokenization：从文本到 token id](</02.大语言模型架构/01.LLM Tokenization/01.LLM Tokenization.md> "01.LLM Tokenization")

[02.Token、上下文窗口、成本和延迟](/02.大语言模型架构/02.Token及模型参数/02.Token及模型参数.md "02.Token及模型参数")

[03.解码策略：Top-k、Top-p、Temperature](/02.大语言模型架构/03.解码策略-Top-k-Top-p-Temperature/03.解码策略-Top-k-Top-p-Temperature.md "03.解码策略")

[04.Attention：token 之间如何互相参考](/02.大语言模型架构/04.Attention/04.Attention.md "04.Attention")

[05.Transformer 架构细节](/02.大语言模型架构/05.Transformer架构细节/05.Transformer架构细节.md "05.Transformer架构细节")

### 2.2 Transformer 深入参考

[2.layer\_normalization](/02.大语言模型架构/2.layer_normalization/2.layer_normalization.md "2.layer_normalization")

[3.位置编码](/02.大语言模型架构/3.位置编码/3.位置编码.md "3.位置编码")

[6.激活函数](/02.大语言模型架构/6.激活函数/6.激活函数.md "6.激活函数")

### 2.3 注意力深入参考

[MHA\_MQA\_GQA](/02.大语言模型架构/MHA_MQA_GQA/MHA_MQA_GQA.md "MHA_MQA_GQA")

### 2.4 BERT

[bert细节](/02.大语言模型架构/bert细节/bert细节.md "bert细节")

[bert变种](/02.大语言模型架构/bert变种/bert变种.md "bert变种")

### 2.5 常见大模型

[llama系列模型](/02.大语言模型架构/llama系列模型/llama系列模型.md "llama系列模型")

[chatglm系列模型](/02.大语言模型架构/chatglm系列模型/chatglm系列模型.md "chatglm系列模型")

[llama 2代码详解](</02.大语言模型架构/llama 2代码详解/llama 2代码详解.md> "llama 2代码详解")

[llama 3](</02.大语言模型架构/llama 3/llama 3.md> "llama 3")

### 2.6 MoE

[1.MoE论文](/02.大语言模型架构/1.MoE论文/1.MoE论文.md "1.MoE论文")

[2.MoE经典论文简牍](/02.大语言模型架构/2.MoE经典论文简牍/2.MoE经典论文简牍.md "2.MoE经典论文简牍")

[3.LLM MoE ：Switch Transformers](</02.大语言模型架构/3.LLM MoE ：Switch Transformers/3.LLM MoE ：Switch Transformers.md> "3.LLM MoE ：Switch Transformers")
