# 🚀 llm-infer-framework-learn

本工程用于记录LLM（大语言模型）推理框架的学习与实践过程，包含从底层原理到工程实现的全链路探索。


## 📚 学习路径

### 基础理论篇
- **推理框架使用**  
  [vllm](https://github.com/vllm-project/vllm)、[TensorRT-LLM](https://github.com/NVIDIA/TensorRT-LLM)
- **推理核心原理**  
  模型压缩、量化技术、K/V缓存机制、PagedAttention 等关键概念解析

## 🛠️ 代码仓库结构
```
llm-infer-framework-learn/
├── llm-infer-framework/    # 推理框架学习
├──── vllm
├──── TensorRT-LLM
```


## 🔍 学习资源索引
- **论文精读**  
  [LLaMA Efficient Inference](https://arxiv.org/abs/2307/09288)、[AWQ: Activation-aware Weight Quantization](https://arxiv.org/abs/2306.00978) 等核心文献解析
- **工具链学习**  
  PyTorch C++ Extension、CUDA Programming Guide、TVM/TensorRT使用指南
- **开源项目参考**  
  llama.cpp、vllm、text-generation-webui 源码解读笔记


## 📝 进度记录
- [ ] 完成vllm安装
- [ ] 使用vllm运行一个example


欢迎关注本仓库，一起探索LLM推理框架的技术细节与优化技巧！如有疑问或建议，欢迎提Issue交流~