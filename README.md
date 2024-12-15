![](./assets/logo2.png)

<p align="center">全世界最好的大语言模型资源汇总 持续更新</p>

<p align="center">
<a href="https://info.flagcounter.com/U6Yn"><img src="https://s11.flagcounter.com/count2/U6Yn/bg_FFFFFF/txt_000000/border_CCCCCC/columns_2/maxflags_10/viewers_0/labels_1/pageviews_0/flags_0/percent_0/" alt="Flag Counter" border="0"></a>
</p>

<details>
<summary>查看更多信息</summary>
<p align="center">
  <a href="https://github.com/WangRongsheng/awesome-LLM-resourses"><img src=https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg ></a>
  <a href="https://github.com/WangRongsheng/awesome-LLM-resourses"><img src=https://img.shields.io/github/forks/WangRongsheng/awesome-LLM-resourses.svg?style=social ></a>
  <a href="https://github.com/WangRongsheng/awesome-LLM-resourses"><img src=https://img.shields.io/github/stars/WangRongsheng/awesome-LLM-resourses.svg?style=social ></a>
  <a href="https://github.com/WangRongsheng/awesome-LLM-resourses"><img src=https://img.shields.io/github/watchers/WangRongsheng/awesome-LLM-resourses.svg?style=social ></a>
</p>

</details>

<p align="center">
  <a href="https://www.wangrs.site/awesome-LLM-resourses/">[在线阅读]</a>
</p>

![](https://camo.githubusercontent.com/2722992d519a722218f896d5f5231d49f337aaff4514e78bd59ac935334e916a/68747470733a2f2f692e696d6775722e636f6d2f77617856496d762e706e67)

#### 目录

- [数据 Data](#数据-Data)
- [微调 Fine-Tuning](#微调-Fine-Tuning)
- [推理 Inference](#推理-Inference)
- [评估 Evaluation](#评估-Evaluation)
- [体验 Usage](#体验-Usage)
- [知识库 RAG](#知识库-RAG)
- [智能体 Agents](#智能体-Agents)
- [搜索 Search](#搜索-Search)
- [书籍 Book](#书籍-Book)
- [课程 Course](#课程-Course)
- [教程 Tutorial](#教程-Tutorial)
- [论文 Paper](#论文-Paper)
- [Tips](#tips)

![](https://camo.githubusercontent.com/2722992d519a722218f896d5f5231d49f337aaff4514e78bd59ac935334e916a/68747470733a2f2f692e696d6775722e636f6d2f77617856496d762e706e67)

## 数据 Data

> [!NOTE]
> 
> 此处命名为`数据`，但这里并没有提供具体数据集，而是提供了处理获取大规模数据的方法
>
> 我们始终None秉持授人以鱼不如授人以None渔

1. [AotoLabel](https://github.com/refuel-ai/autolabel): 使用大语言模型对文本数据集进行标记、清理和丰富。
2. [LabelLLM](https://github.com/opendatalab/LabelLLM): 开源数据标注平台。
3. [data-juicer](https://github.com/modelscope/data-juicer): 一个一站式数据处理系统，使数据更加高质量、更有营养、更易于大语言模型消化！
4. [OmniParser](https://github.com/jf-tech/omniparser): 一个原生 Golang ETL 流式解析和转换库，用于 CSV、JSON、XML、EDI、文本等。
5. [MinerU](https://github.com/opendatalab/MinerU): MinerU 是一个一站式、开源、高质量数据提取工具，支持 PDF/网页/电子书提取。
6. [PDF-Extract-Kit](https://github.com/opendatalab/PDF-Extract-Kit): 一个用于高质量 PDF 内容提取的综合工具包。
7. [Parsera](https://github.com/raznem/parsera): 用于使用大语言模型抓取网站的轻量级库。
8. [Sparrow](https://github.com/katanaml/sparrow): Sparrow 是一个创新的开源解决方案，用于从各种文档和图像中高效提取和处理数据。
9. [Docling](https://github.com/DS4SD/docling): 轻松快速地将 PDF 转换为 JSON 或 Markdown。
10. [GOT-OCR2.0](https://github.com/Ucas-HaoranWei/GOT-OCR2.0): OCR 模型。
11. [LLM Decontaminator](https://github.com/lm-sys/llm-decontaminator): 重新思考语言模型的基准和污染，使用重新表述的样本。
12. [DataTrove](https://github.com/huggingface/datatrove): DataTrove 是一个用于大规模处理、过滤和去重文本数据的库。
13. [llm-swarm](https://github.com/huggingface/llm-swarm/tree/main/examples/textbooks): 生成大型合成数据集，如 [Cosmopedia](https://huggingface.co/datasets/HuggingFaceTB/cosmopedia)。
14. [Distilabel](https://github.com/argilla-io/distilabel): Distilabel 是一个基于验证过的研究论文，为需要快速、可靠和可扩展管道的工程师提供的合成数据和 AI 反None馈框架。
15. [Common-Crawl-Pipeline-Creator](https://huggingface.co/spaces/lhoestq/Common-Crawl-Pipeline-Creator): 公共爬虫管道创建器。
16. [Tabled](https://github.com/VikParuchuri/tabled): 检测和提取表格到 Markdown 和 CSV。
17. [Zerox](https://github.com/getomni-ai/zerox): 使用 gpt-4o-mini 的零样本 PDF OCR。
18. [DocLayout-YOLO](https://github.com/opendatalab/DocLayout-YOLO): 通过多样化的合成数据和全局到局部的自适应感知提升文档布局分析。
19. [TensorZero](https://github.com/tensorzero/tensorzero): 通过经验改进大语言模型。
20. [Promptwright](https://github.com/StacklokLabs/promptwright): 使用本地大语言模型生成大型合成数据。
21. [pdf-extract-api](https://github.com/CatchTheTornado/pdf-extract-api): 使用最先进的现代 OCR 和 Ollama 支持的模型进行文档（PDF）提取和解析的 API。
22. [pdf2htmlEX](https://github.com/pdf2htmlEX/pdf2htmlEX): 将 PDF 转换为 HTML 而不丢失文本或格式。
23. [Extractous](https://github.com/yobix-ai/extractous): 快速高效的非结构化数据提取。使用 Rust 编写，支持多种语言的绑定。
24. [MegaParse](https://github.com/QuivrHQ/MegaParse): 针对 LLM 摄入优化的文件解析器，无损。

<div align="right">
    <b><a href="#目录">None↥ 返回顶部</a></b>
</div>

## 微调 Fine-Tuning

1. [LLaMA-Factory](https://github.com/hiyouga/LLaMA-Factory): 统一高效微调 100+ 大语言模型。
2. [unsloth](https://github.com/unslothai/unsloth): 2-5 倍更快，内存使用量减少 80% 的大语言模型微调。
3. [TRL](https://huggingface.co/docs/trl/index): 变换器强化学习。
4. [Firefly](https://github.com/yangjianxin1/Firefly): Firefly：大模型训练工具，支持训练数十种大模型
5. [Xtuner](https://github.com/InternLM/xtuner): 一个高效、灵活且功能齐全的大模型微调工具包。
6. [torchtune](https://github.com/pytorch/torchtune): 一个用于大语言模型微调的原生 PyTorch 库。
7. [Swift](https://github.com/modelscope/swift): 使用 PEFT 或全参数微调 200+ 大语言模型或 15+ 多模态语言模型。
8. [AutoTrain](https://huggingface.co/autotrain): 一种自动训练、评估和部署最先进机器学习模型的新方法。
9. [OpenRLHF](https://github.com/OpenLLMAI/OpenRLHF): 一个易于使用、可扩展和高性能的 RLHF 框架（支持 70B+ 全参数调优 & LoRA & Mixtral & KTO）。
10. [Ludwig](https://github.com/ludwig-ai/ludwig): 用于构建自定义大语言模型、神经网络和其他 AI 模型的低代码框架。
11. [mistral-finetune](https://github.com/mistralai/mistral-finetune): 一个轻量级代码库，使得 Mistral 的模型能够高效、性能优异地进行微调。
12. [aikit](https://github.com/sozercan/aikit): 轻松微调、构建和部署开源大语言模型！
13. [H2O-LLMStudio](https://github.com/h2oai/h2o-llmstudio): H2O LLM Studio - 一个用于微调大语言模型的框架和无代码 GUI。
14. [LitGPT](https://github.com/Lightning-AI/litgpt): 在您自己的数据上预训练、微调和部署 20+ 大语言模型。使用最先进的技术：闪存注意力、FSDP、4 位、LoRA 等。
15. [LLMBox](https://github.com/RUCAIBox/LLMBox): 实现大语言模型的综合库，包括统一的训练流程和全面的模型评估。
16. [PaddleNLP](https://github.com/PaddlePaddle/PaddleNLP): 易于使用且强大的 NLP 和大语言模型库。
17. [workbench-llamafactory](https://github.com/NVIDIA/workbench-llamafactory): 这是一个 NVIDIA AI Workbench 示例项目，演示使用 Llamafactory 进行端到端模型开发工作流程。
18. [OpenRLHF](https://github.com/OpenLLMAI/OpenRLHF): 一个易于使用、可扩展和高性能的 RLHF 框架（70B+ PPO 全参数调优 & 迭代 DPO & LoRA & Mixtral）。
19. [TinyLLaVA Factory](https://github.com/TinyLLaVA/TinyLLaVA_Factory): 小规模大型多模态模型的框架。
20. [LLM-Foundry](https://github.com/mosaicml/llm-foundry): Databricks 基础模型的 LLM 训练代码。
21. [lmms-finetune](https://github.com/zjysteven/lmms-finetune): 一个用于微调（全参数、lora）大型多模态模型的统一代码库，支持 llava-1.5、qwen-vl、llava-interleave、llava-next-video、phi3-v 等。
22. [Simplifine](https://github.com/simplifine-llm/Simplifine): Simplifine 让您使用任何 Hugging Face 数据集或模型只需一行代码即可调用 LLM 微调。
23. [Transformer Lab](https://github.com/transformerlab/transformerlab-app): 高级 LLM 工程的开源应用程序：在您自己的计算机上与大语言模型互动、训练、微调和评估。
24. [Liger-Kernel](https://github.com/linkedin/Liger-Kernel): 用于大语言模型训练的高效 Triton 内核。
25. [ChatLearn](https://github.com/alibaba/ChatLearn): 一个用于大规模对齐的灵活高效的训练框架。
26. [nanotron](https://github.com/huggingface/nanotron): 最小化的大语言模型 3D 并行训练。
27. [Proxy Tuning](https://github.com/alisawuffles/proxy-tuning): 通过代理微调语言模型。
28. [Effective LLM Alignment](https://github.com/VikhrModels/effective_llm_alignment/): 有效的大语言模型对齐工具包。
29. [Autotrain-advanced](https://github.com/huggingface/autotrain-advanced)
30. [Meta Lingua](https://github.com/facebookresearch/lingua): 一个精简、高效且易于破解的研究 LLM 的代码库。
31. [Vision-LLM Alignemnt](https://github.com/NiuTrans/Vision-LLM-Alignment): 该仓库包含用于基于视觉的大语言模型的 SFT、RLHF 和 DPO 的代码，包括 LLaVA 模型和 LLaMA-3.2-vision 模型。
32. [finetune-Qwen2-VL](https://github.com/zhangfaen/finetune-Qwen2-VL): 快速启动微调或继续预训练 Qwen2-VL 模型。

<div align="right">
    <b><a href="#目录">None↥ 返回顶部</a></b>
</div>

## 推理 Inference

1. [ollama](https://github.com/ollama/ollama): 快速启动并运行 Llama 3、Mistral、Gemma 和其他大语言模型。
2. [Open WebUI](https://github.com/open-webui/open-webui): 用户友好的大语言模型 WebUI（原 Ollama WebUI）。
3. [Text Generation WebUI](https://github.com/oobabooga/text-generation-webui): 大语言模型的 Gradio Web UI。支持 transformers、GPTQ、AWQ、EXL2、llama.cpp（GGUF）、Llama 模型。
4. [Xinference](https://github.com/xorbitsai/inference): 一个设计用于服务语言、语音识别和多模态模型的强大且多功能的库。
5. [LangChain](https://github.com/langchain-ai/langchain): 构建上下文感知的推理应用。
6. [LlamaIndex](https://github.com/run-llama/llama_index): 您的大语言模型应用的数据框架。
7. [lobe-chat](https://github.com/lobehub/lobe-chat): 一个开源的、现代设计的大语言模型/AI 聊天框架。支持多 AI 提供商、多模态（视觉/TTS）和插件系统。
8. [TensorRT-LLM](https://github.com/NVIDIA/TensorRT-LLM): TensorRT-LLM 为用户提供了一个易于使用的 Python API，用于定义大语言模型（LLM）并构建包含最先进优化技术的 TensorRT 引擎，以在 NVIDIA GPU 上高效进行推理。
9. [vllm](https://github.com/vllm-project/vllm): 一个高吞吐量且内存高效的大语言模型推理和服务引擎。
10. [LlamaChat](https://github.com/alexrozanski/LlamaChat): 在 macOS 本地应用程序中与您喜爱的大语言模型聊天。
11. [NVIDIA ChatRTX](https://www.nvidia.com/en-us/ai-on-rtx/chatrtx/): ChatRTX 是一个演示应用程序，让您可以个性化连接到您自己的内容（文档、笔记或其他数据）的 GPT 大语言模型（LLM）。
12. [LM Studio](https://lmstudio.ai/): 发现、下载并在本地运行大语言模型。
13. [chat-with-mlx](https://github.com/qnguyen3/chat-with-mlx): 使用 MLX 框架在 Apple Silicon 上与您的数据本地聊天。
14. [LLM Pricing](https://llmpricecheck.com/): 快速找到适合您预算的大语言模型（LLM）API！使用我们的免费工具立即访问顶级供应商的最新价格。
15. [Open Interpreter](https://github.com/OpenInterpreter/open-interpreter): 计算机的自然语言界面。
16. [Chat-ollama](https://github.com/sugarforever/chat-ollama): 一个基于大语言模型的开源聊天机器人。它支持广泛的语言模型和知识库管理。
17. [chat-ui](https://github.com/huggingface/chat-ui): 驱动 HuggingChat 应用程序的开源代码库。
18. [MemGPT](https://github.com/cpacker/MemGPT): 使用长期记忆和自定义工具创建 LLM 代理。
19. [koboldcpp](https://github.com/LostRuins/koboldcpp): 一个简单的单文件方式，使用 KoboldAI 的 UI 运行各种 GGML 和 GGUF 模型。
20. [LLMFarm](https://github.com/guinmoon/LLMFarm): 在 iOS 和 MacOS 上使用 GGML 库离线运行 Llama 和其他大语言模型。
21. [enchanted](https://github.com/AugustDev/enchanted): Enchanted 是一个用于使用 Ollama 与私有自托管语言模型（如 Llama2、Mistral 或 Vicuna）聊天的 iOS 和 macOS 应用程序。
22. [Flowise](https://github.com/FlowiseAI/Flowise): 拖放 UI 构建您自定义的大语言模型流程。
23. [Jan](https://github.com/janhq/jan): Jan 是一个开源的 ChatGPT 替代品，可以在您的计算机上 100% 离线运行。支持多个引擎（llama.cpp、TensorRT-LLM）。
24. [LMDeploy](https://github.com/InternLM/lmdeploy): LMDeploy 是一个用于压缩、部署和服务大语言模型的工具包。
25. [RouteLLM](https://github.com/lm-sys/RouteLLM): 一个用于服务和评估 LLM 路由器的框架 - 在不牺牲质量的同时节省 LLM 成本！
26. [MInference](https://github.com/microsoft/MInference): 关于
为了加速长上下文 LLM 的推理，通过近似和动态稀疏计算注意力，预填充时在 A100 上最多可将推理延迟降低 10 倍，同时保持准确性。
27. [Mem0](https://github.com/mem0ai/mem0): 个性化 AI 的记忆层。
28. [SGLang](https://github.com/sgl-project/sglang): SGLang 是另一个快速服务大语言模型和视觉语言模型的框架。
29. [AirLLM](https://github.com/lyogavin/airllm): AirLLM 优化推理内存使用，允许 70B 大语言模型在单个 4GB GPU 卡上无需量化、蒸None馏和修剪即可运行推理。现在您可以在 8GB vram 上运行 405B Llama3.1。
30. [LLMHub](https://github.com/jmather/llmhub): LLMHub 是一个轻量级的管理平台，旨在简化与各种语言模型（LLM）的操作和交互。
31. [YuanChat](https://github.com/IEIT-Yuan/YuanChat)
32. [LiteLLM](https://github.com/BerriAI/litellm): 使用 OpenAI 格式调用所有 LLM API [Bedrock、Huggingface、VertexAI、TogetherAI、Azure、OpenAI、Groq 等]。
33. [GuideLLM](https://github.com/neuralmagic/guidellm): GuideLLM 是一个强大的工具，用于评估和优化大语言模型（LLM）的部署。
34. [LLM-Engines](https://github.com/jdf-prog/LLM-Engines): 大语言模型（LLM）的统一推理引擎，包括开源模型（VLLM、SGLang、Together）和商业模型（OpenAI、Mistral、Claude）。
35. [OARC](https://github.com/Leoleojames1/ollama_agent_roll_cage): ollama_agent_roll_cage（OARC）是一个本地 Python 代理，将 ollama llm 与 Coqui-TTS 语音模型、Keras 分类器、Llava 视觉、Whisper 识别等融合，创建一个统一的聊天机器人代理，用于本地、自定义自动化。
36. [g1](https://github.com/bklieger-groq/g1): 使用 Groq 上的 Llama-3.1 70b 创建类似 o1 的推理链。
37. [MemoryScope](https://github.com/modelscope/MemoryScope): MemoryScope 为 LLM 聊天机器人提供强大且灵活的长期记忆能力，提供构建此类能力的框架。
38. [OpenLLM](https://github.com/bentoml/OpenLLM): 在云端以 OpenAI 兼容的 API 端点运行任何开源 LLM，如 Llama 3.1、Gemma。
39. [Infinity](https://github.com/infiniflow/infinity): 为 LLM 应用程序构建的 AI 原生数据库，提供密集嵌入、稀疏嵌入、张量和全文的超快速混合搜索。
40. [optillm](https://github.com/codelion/optillm): 一个与 OpenAI API 兼容的优化推理代理，实现了几种最先进的技术，可以提高 LLM 的准确性和性能。
41. [LLaMA Box](https://github.com/gpustack/llama-box): 基于 llama.cpp 的大语言模型推理服务器实现。
42. [ZhiLight](https://github.com/zhihu/ZhiLight): 一个高度优化的推理加速引擎，用于 Llama 及其变体。

<div align="right">
    <b><a href="#目录">None↥ 返回顶部</a></b>
</div>

## 评估 Evaluation

1. [lm-evaluation-harness](https://github.com/EleutherAI/lm-evaluation-harness): 一个用于少样本评估语言模型的框架。
2. [opencompass](https://github.com/open-compass/opencompass): OpenCompass 是一个 LLM 评估平台，支持广泛的模型（Llama3、Mistral、InternLM2、GPT-4、LLaMa2、Qwen、GLM、Claude 等）在 100+ 数据集上进行评估。
3. [llm-comparator](https://github.com/PAIR-code/llm-comparator): LLM Comparator 是一个用于并排评估和分析 LLM 响应的交互式数据可视化工具，开发中。
4. [EvalScope](https://github.com/modelscope/evalscope)
5. [Weave](https://weave-docs.wandb.ai/guides/core-types/evaluations): 一个用于跟踪和评估 LLM 应用程序的轻量级工具包。
6. [MixEval](https://github.com/Psycoy/MixEval/): 从 LLM 基准混合中衍生出众人的智慧。
7. [Evaluation guidebook](https://github.com/huggingface/evaluation-guidebook): 如果您曾想知道如何确保 LLM 在您特定的任务上表现良好，这本指南就是为您准备的！
8. [Ollama Benchmark](https://github.com/aidatatools/ollama-benchmark): 通过 Ollama（本地 LLM）进行吞吐量的 LLM 基准测试。
9. [VLMEvalKit](https://github.com/open-compass/VLMEvalKit): 大型视觉-语言模型（LVLMs）的开源评估工具包，支持 ~100 个 VLMs、40+ 基准。

`LLM API 服务平台`：
1. [Groq](https://groq.com/)
2. [None硅基流动](https://cloud.siliconflow.cn/models)
3. [火山引擎](https://www.volcengine.com/product/ark)
4. [文心千帆](https://qianfan.cloud.baidu.com/)
5. [DashScope](https://dashscope.aliyun.com/)
6. [aisuite](https://github.com/andrewyng/aisuite)

<div align="right">
    <b><a href="#目录">None↥ 返回顶部</a></b>
</div>

## 体验 Usage

1. [LMSYS Chatbot Arena: Benchmarking LLMs in the Wild](https://arena.lmsys.org/)
2. [CompassArena 司南大模型竞技场](https://modelscope.cn/studios/opencompass/CompassArena/summary)
3. [None琅None琊榜](https://langyb.com/)
4. [Huggingface Spaces](https://huggingface.co/spaces)
5. [WiseModel Spaces](https://wisemodel.cn/spaces)
6. [Poe](https://poe.com/)
7. [林哥的大模型野榜](https://lyihub.com/)
8. [OpenRouter](https://openrouter.ai/)
9. [AnyChat](https://huggingface.co/spaces/akhaliq/anychat)

<div align="right">
    <b><a href="#目录">None↥ 返回顶部</a></b>
</div>

## 知识库 RAG

1. [AnythingLLM](https://github.com/Mintplex-Labs/anything-llm): 适用于任何 LLM 的全功能 AI 应用程序，具备完整的 RAG 和 AI 智能体功能。
2. [MaxKB](https://github.com/1Panel-dev/MaxKB): 基于 LLM 大语言模型的知识库问答系统。开箱即用，支持快速嵌入到第三方业务系统。
3. [RAGFlow](https://github.com/infiniflow/ragflow): 基于深度文档理解的开源 RAG（Retrieval-Augmented Generation）引擎。
4. [Dify](https://github.com/langgenius/dify): 开源的 LLM 应用开发平台。Dify 的直观界面结合了 AI 工作流、RAG 管道、智能体功能、模型管理、可观察性功能等，让您可以从原型快速过渡到生产环境。
5. [FastGPT](https://github.com/labring/FastGPT): 基于 LLM 的知识平台，提供开箱即用的数据处理和模型调用能力，通过 Flow 可视化实现工作流编排。
6. [Langchain-Chatchat](https://github.com/chatchat-space/Langchain-Chatchat): 基于 Langchain 与 ChatGLM 等不同大语言模型的本地知识库问答。
7. [QAnything](https://github.com/netease-youdao/QAnything): 基于任何内容的问答。
8. [Quivr](https://github.com/QuivrHQ/quivr): 个人生产力助手（RAG）None⚡️None🤖 与您的文档（PDF、CSV 等）及应用程序使用 Langchain、GPT 3.5 / 4 turbo、私人、Anthropic、VertexAI、Ollama、LLMs、Groq 进行聊天，您可以与用户共享！本地和私人替代 OpenAI GPTs 和 ChatGPT，由检索增强生成驱动。
9. [RAG-GPT](https://github.com/open-kf/rag-gpt): RAG-GPT 利用 LLM 和 RAG 技术，从用户定制的知识库中学习，提供与上下文相关的答案，确保快速且准确的信息检索。
10. [Verba](https://github.com/weaviate/Verba): 由 Weaviate 驱动的检索增强生成（RAG）聊天机器人。
11. [FlashRAG](https://github.com/RUC-NLPIR/FlashRAG): 用于高效 RAG 研究的 Python 工具包。
12. [GraphRAG](https://github.com/microsoft/graphrag): 一个模块化的基于图的检索增强生成（RAG）系统。
13. [LightRAG](https://github.com/SylphAI-Inc/LightRAG): LightRAG 帮助开发者构建和优化检索器-智能体-生成器管道。
14. [GraphRAG-Ollama-UI](https://github.com/severian42/GraphRAG-Ollama-UI): 使用 Ollama 与 Gradio UI 及额外功能的 GraphRAG。
15. [nano-GraphRAG](https://github.com/gusye1234/nano-graphrag): 一个简单且易于修改的 GraphRAG 实现。
16. [RAG Techniques](https://github.com/NirDiamant/RAG_Techniques): 该存储库展示了各种高级的检索增强生成（RAG）系统技术。RAG 系统将信息检索与生成模型结合起来，提供准确且上下文丰富的响应。
17. [ragas](https://github.com/explodinggradients/ragas): 用于评估您的检索增强生成（RAG）管道的框架。
18. [kotaemon](https://github.com/Cinnamon/kotaemon): 一个开源的清洁且可定制的 RAG UI，用于与您的文档聊天。同时考虑了最终用户和开发者的需求。
19. [RAGapp](https://github.com/ragapp/ragapp): 在任何企业中使用 Agentic RAG 的最简单方法。
20. [TurboRAG](https://github.com/MooreThreads/TurboRAG): 使用预计算的 KV 缓存加速检索增强生成的分块文本。
21. [LightRAG](https://github.com/HKUDS/LightRAG): 简单且快速的检索增强生成。
22. [TEN](https://github.com/TEN-framework/ten_framework): 下一代 AI-智能体框架，世界上第一个真正的实时多模态 AI 智能体框架。
23. [AutoRAG](https://github.com/Marker-Inc-Korea/AutoRAG): 用于自动寻找最佳 RAG 管道的 RAG 自动机器学习工具。
24. [KAG](https://github.com/OpenSPG/KAG): KAG 是一个基于 OpenSPG 引擎的知识增强生成框架，用于构建知识增强的严格决策和信息检索知识服务。
25. [Fast-GraphRAG](https://github.com/circlemind-ai/fast-graphrag): 智能适应您的用例、数据和查询的 RAG。
26. [Tiny-GraphRAG](https://github.com/limafang/tiny-graphrag)
27. [DB-GPT GraphRAG](https://github.com/eosphoros-ai/DB-GPT/tree/main/dbgpt/storage/knowledge_graph): DB-GPT GraphRAG 整合了基于三元组的知识图和文档结构图，同时利用社区和文档检索机制增强 RAG 能力，实现了与微软的 GraphRAG 相当的性能，同时仅消耗 50% 的所需令牌。请参阅 DB-GPT [Graph RAG 用户手册](http://docs.dbgpt.cn/docs/cookbook/rag/graph_rag_app_develop/) 以获取详细信息。
28. [Chonkie](https://github.com/bhavnicksm/chonkie): 一个轻量级、速度极快且准备好 CHONK 您文本的无废话 RAG 分块库。
29. [RAGLite](https://github.com/superlinear-ai/raglite): RAGLite 是使用 PostgreSQL 或 SQLite 的检索增强生成（RAG）的 Python 工具包。

<div align="right">
    <b><a href="#Contents">None↥ 返回顶部</a></b>
</div>

## 智能体 Agents

1. [AutoGen](https://github.com/microsoft/autogen): AutoGen 是一个框架，通过使用多个可以相互对话以解决任务的智能体，启用 LLM 应用程序的开发。[AutoGen AIStudio](https://autogen-studio.com/)
2. [CrewAI](https://github.com/joaomdmoura/crewAI): 用于协调角色扮演、自主 AI 智能体的框架。通过促进协作智能，CrewAI 赋予智能体无缝协作的能力，处理复杂任务。
3. [Coze](https://www.coze.com/)
4. [AgentGPT](https://github.com/reworkd/AgentGPT): 在浏览器中组装、配置和部署自主 AI 智能体。
5. [XAgent](https://github.com/OpenBMB/XAgent): 用于解决复杂任务的自主 LLM 智能体。
6. [MobileAgent](https://github.com/X-PLUG/MobileAgent): 强大的移动设备操作助手家族。
7. [Lagent](https://github.com/InternLM/lagent): 用于构建基于 LLM 的智能体的轻量级框架。
8. [Qwen-Agent](https://github.com/QwenLM/Qwen-Agent): 基于 Qwen2 构建的智能体框架和应用程序，具有功能调用、代码解释器、RAG 和 Chrome 扩展功能。
9. [LinkAI](https://link-ai.tech/portal): 一站式 AI 智能体搭建平台。
10. [Baidu APPBuilder](https://appbuilder.cloud.baidu.com/)
11. [agentUniverse](https://github.com/alipay/agentUniverse): agentUniverse 是一个 LLM 多智能体框架，允许开发者轻松构建多智能体应用程序。此外，通过社区，他们可以跨不同领域交换和分享实践模式。
12. [LazyLLM](https://github.com/LazyAGI/LazyLLM): 用于低代码构建多智能体大模型应用的开发工具。
13. [AgentScope](https://github.com/modelscope/agentscope): 以更简单的方式开始构建由 LLM 驱动的多智能体应用程序。
14. [MoA](https://github.com/togethercomputer/MoA): 智能体混合（MoA）是一种新None颖的方法，利用多个 LLM 的集体优势来提升性能，实现了最先进的结果。
15. [Agently](https://github.com/Maplemx/Agently): AI 智能体应用开发框架。
16. [OmAgent](https://github.com/om-ai-lab/OmAgent): 用于解决复杂任务的多模态智能体框架。
17. [Tribe](https://github.com/StreetLamb/tribe): 无需编码的工具，可快速构建和协调多智能体团队。
18. [CAMEL](https://github.com/camel-ai/camel): 第一个 LLM 多智能体框架和致力于寻找智能体扩展规律的开源社区。
19. [PraisonAI](https://github.com/MervinPraison/PraisonAI/): PraisonAI 应用程序将 AutoGen 和 CrewAI 或类似框架结合成一个低代码解决方案，用于构建和管理多智能体 LLM 系统，专注于简洁性、定制化和高效的人机协作。
20. [IoA](https://github.com/openbmb/ioa): 一个用于协作 AI 智能体的开源框架，通过类似互联网的连接性，启用不同的分布式智能体组队并解决复杂任务。
21. [llama-agentic-system](https://github.com/meta-llama/llama-agentic-system): Llama Stack APIs 的智能体组件。
22. [Agent Zero](https://github.com/frdel/agent-zero): Agent Zero 不是预定义的智能体框架。它被设计为动态的，随着您的使用而有机增长和学习。
23. [Agents](https://github.com/aiwaves-cn/agents): 一个面向数据中心、自主演进的自主语言智能体的开源框架。
24. [AgentScope](https://github.com/modelscope/agentscope): 以更简单的方式开始构建由 LLM 驱动的多智能体应用程序。
25. [FastAgency](https://github.com/airtai/fastagency): 将多智能体工作流程快速带入生产环境的最快方式。
26. [Swarm](https://github.com/openai/swarm): 用于构建、编排和部署多智能体系统的框架。由 OpenAI 解决方案团队管理。实验性框架。
27. [Agent-S](https://github.com/simular-ai/Agent-S): 使用计算机像人类一样的开源智能体框架。
28. [PydanticAI](https://github.com/pydantic/pydantic-ai): 使用 Pydantic 和 LLMs 的智能体框架/None垫片。

<div align="right">
    <b><a href="#Contents">None↥ 返回顶部</a></b>
</div>

## 搜索 Search

1. [OpenSearch GPT](https://github.com/supermemoryai/opensearch-ai): SearchGPT / Perplexity 克隆，但为您个人化。
2. [MindSearch](https://github.com/InternLM/MindSearch): 基于 LLM 的多智能体 Web 搜索引擎框架（如 Perplexity.ai Pro 和 SearchGPT）。
3. [nanoPerplexityAI](https://github.com/Yusuke710/nanoPerplexityAI): perplexity.ai 的最简单开源实现。
4. [curiosity](https://github.com/jank/curiosity): 尝试构建类似 Perplexity 的用户体验。

<div align="right">
    <b><a href="#Contents">None↥ 返回顶部</a></b>
</div>

## 书籍 Book

1. [《大规模语言模型：从理论到实践》](https://intro-llm.github.io/)
2. [《大语言模型》](https://llmbook-zh.github.io/)
3. [《动手学大模型Dive into LLMs》](https://github.com/Lordog/dive-into-llms)
4. [《动手做AI Agent》](https://book.douban.com/subject/36884058/)
5. [《Build a Large Language Model (From Scratch)》](https://github.com/rasbt/LLMs-from-scratch)
6. [《多模态大模型》](https://github.com/HCPLab-SYSU/Book-of-MLM)
7. [《Generative AI Handbook: A Roadmap for Learning Resources》](https://genai-handbook.github.io/)
8. [《Understanding Deep Learning》](https://udlbook.github.io/udlbook/)
9. [《Illustrated book to learn about Transformers & LLMs》](https://www.reddit.com/r/MachineLearning/comments/1ew1hws/p_illustrated_book_to_learn_about_transformers/)
10. [《Building LLMs for Production: Enhancing LLM Abilities and Reliability with Prompting, Fine-Tuning, and RAG》](https://www.amazon.com/Building-LLMs-Production-Reliability-Fine-Tuning/dp/B0D4FFPFW8?crid=7OAXELUKGJE4&dib=eyJ2IjoiMSJ9.Qr3e3VSH8LSo_j1M7sV7GfS01q_W1LDYd2uGlvGJ8CW-t4DTlng6bSeOlZBryhp6HJN5K1HqWMVVgabU2wz2i9yLpy_AuaZN-raAEbenKx2NHtzZA3A4k-N7GpnldF1baCarA_V1CRF-aCdc9_3WSX7SaEzmpyDv22TTyltcKT74HAb2KiQqBGLhQS3cEAnzChcqGa1Xp-XhbMnplVwT7xZLApE3tGLhDOgi5GmSi9w.8SY_4NBEkm68YF4GwhDnz0r81ZB1d8jr-gK9IMJE5AE&dib_tag=se&keywords=building+llms+for+production&qid=1716376414&sprefix=building+llms+for+production,aps,101&sr=8-1&linkCode=sl1&tag=whatsai06-20&linkId=ee102fda07a0eb51710fcdd8b8d20c28&language=en_US&ref_=as_li_ss_tl)
11. [《大型语言模型实战指南：应用实践与场景落地》](https://github.com/liucongg/LLMsBook)
12. [《Hands-On Large Language Models》](https://github.com/handsOnLLM/Hands-On-Large-Language-Models)
13. [《自然语言处理：大模型理论与实践》](https://nlp-book.swufenlp.group/)
14. [《动手学强化学习》](https://hrl.boyuai.com/)
15. [《面向开发者的LLM入门教程》](https://datawhalechina.github.io/llm-cookbook/#/)
16. [《大模型基础》](https://github.com/ZJU-LLMs/Foundations-of-LLMs)

<div align="right">
    <b><a href="#Contents">None↥ 返回顶部</a></b>
</div>

## 课程 Course

> [LLM Resources Hub](https://llmresourceshub.vercel.app/)

1. [斯坦福 CS224N: Natural Language Processing with Deep Learning](https://web.stanford.edu/class/cs224n/)
2. [吴恩达: Generative AI for Everyone](https://www.deeplearning.ai/courses/generative-ai-for-everyone/)
3. [吴恩达: LLM series of courses](https://learn.deeplearning.ai/)
4. [ACL 2023 Tutorial: Retrieval-based Language Models and Applications](https://acl2023-retrieval-lm.github.io/)
5. [llm-course: Course to get into Large Language Models (LLMs) with roadmaps and Colab notebooks.](https://github.com/mlabonne/llm-course)
6. [微软: Generative AI for Beginners](https://github.com/microsoft/generative-ai-for-beginners)
7. [微软: State of GPT](https://www.youtube.com/watch?v=bZQun8Y4L2A)
8. [HuggingFace NLP Course](https://huggingface.co/learn/nlp-course/chapter1/1)
9. [清华 NLP 刘知远团队大模型公开课](https://www.bilibili.com/video/BV1UG411p7zv/?vd_source=c739db1ebdd361d47af5a0b8497417db)
10. [斯坦福 CS25: Transformers United V4](https://web.stanford.edu/class/cs25/)
11. [斯坦福 CS324: Large Language Models](https://stanford-cs324.github.io/winter2022/)
12. [普林斯顿 COS 597G (Fall 2022): Understanding Large Language Models](https://www.cs.princeton.edu/courses/archive/fall22/cos597G/)
13. [约翰霍普金斯 CS 601.471/671 NLP: Self-supervised Models](https://self-supervised.cs.jhu.edu/sp2023/index.html)
14. [李宏毅 GenAI课程](https://www.youtube.com/watch?v=yiY4nPOzJEg&list=PLJV_el3uVTsOePyfmkfivYZ7Rqr2nMk3W)
15. [openai-cookbook](https://github.com/openai/openai-cookbook): 使用 OpenAI API 的示例和指南。
16. [Hands on llms](https://github.com/iusztinpaul/hands-on-llms): 通过设计、训练和部署一个实时的金融顾问 LLM 系统，免费学习 LLM、LLMOps 和向量数据库。
17. [滑铁卢大学 CS 886: Recent Advances on Foundation Models](https://cs.uwaterloo.ca/~wenhuche/teaching/cs886/)
18. [Mistral: Getting Started with Mistral](https://www.deeplearning.ai/short-courses/getting-started-with-mistral/)
19. [斯坦福 CS25: Transformers United V4](https://web.stanford.edu/class/cs25/)
20. [Coursera: Chatgpt 应用提示工程](https://www.coursera.org/learn/prompt-engineering)
21. [LangGPT](https://github.com/langgptai/LangGPT): 让每个人都成为提示专家！
22. [mistralai-cookbook](https://github.com/mistralai/cookbook)
23. [Introduction to Generative AI 2024 Spring](https://speech.ee.ntu.edu.tw/~hylee/genai/2024-spring.php)
24. [build nanoGPT](https://github.com/karpathy/build-nanogpt): 关于从头构建 nanoGPT 的视频+代码讲座。
25. [LLM101n](https://github.com/karpathy/LLM101n): 让我们构建一个故事讲述者。
26. [Knowledge Graphs for RAG](https://www.deeplearning.ai/short-courses/knowledge-graphs-rag/)
27. [LLMs From Scratch (Datawhale Version)](https://github.com/datawhalechina/llms-from-scratch-cn)
28. [OpenRAG](https://openrag.notion.site/Open-RAG-c41b2a4dcdea4527a7c1cd998e763595)
29. [通往AGI之路](https://waytoagi.feishu.cn/wiki/QPe5w5g7UisbEkkow8XcDmOpn8e)
30. [Andrej Karpathy - Neural Networks: Zero to Hero](https://www.youtube.com/playlist?list=PLAqhIrjkxbuWI23v9cThsA9GvCAUhRvKZ)
31. [Interactive visualization of Transformer](https://poloclub.github.io/transformer-explainer/)
32. [andysingal/llm-course](https://github.com/andysingal/llm-course)
33. [LM-class](https://lm-class.org/lectures)
34. [Google Advanced: Generative AI for Developers Learning Path](https://www.cloudskillsboost.google/paths/183)
35. [Anthropics：Prompt Engineering Interactive Tutorial](https://github.com/anthropics/courses/tree/master/prompt_engineering_interactive_tutorial/Anthropic%201P)
36. [LLMsBook](https://github.com/liucongg/LLMsBook)
37. [Large Language Model Agents](https://llmagents-learning.org/f24)
38. [Cohere LLM University](https://cohere.com/llmu)
39. [LLMs and Transformers](https://www.ambujtewari.com/LLM-fall2024/)
40. [Smol Vision](https://github.com/merveenoyan/smol-vision): 用于缩小、优化、定制前沿视觉模型的配方。
41. [Multimodal RAG: Chat with Videos](https://www.deeplearning.ai/short-courses/multimodal-rag-chat-with-videos/)
42. [LLMs Interview Note](https://github.com/wdndev/llm_interview_note)
43. [RAG++ : From POC to production](https://www.wandb.courses/courses/rag-in-production): 高级 RAG 课程。
44. [Weights & Biases AI Academy](https://www.wandb.courses/pages/w-b-courses): 微调、使用 LLM 构建、结构化输出等 LLM 课程。
45. [Prompt Engineering & AI tutorials & Resources](https://promptengineering.org/)
46. [Learn RAG From Scratch – Python AI Tutorial from a LangChain Engineer](https://www.youtube.com/watch?v=sVcwVQRHIc8)
47. [LLM Evaluation: A Complete Course](https://www.comet.com/site/llm-course/)

<div align="right">
    <b><a href="#Contents">None↥ 返回顶部</a></b>
</div>

## 教程 Tutorial

1. [动手学大模型应用开发](https://datawhalechina.github.io/llm-universe/#/)
2. [AI开发者频道](https://techdiylife.github.io/blog/blog_list.html)
3. [B站：五里None墩茶社](https://space.bilibili.com/615957867/?spm_id_from=333.999.0.0)
4. [B站：木羽Cheney](https://space.bilibili.com/3537113897241540/?spm_id_from=333.999.0.0)
5. [YTB：AI Anytime](https://www.youtube.com/channel/UC-zVytOQB62OwMhKRi0TDvg)
6. [B站：漆妮妮](https://space.bilibili.com/1262370256/?spm_id_from=333.999.0.0)
7. [Prompt Engineering Guide](https://www.promptingguide.ai/)
8. [YTB: AI超元域](https://www.youtube.com/@AIsuperdomain)
9. [B站：TechBeat人工智能社区](https://space.bilibili.com/209732435)
10. [B站：黄益贺](https://space.bilibili.com/322961825)
11. [B站：深度学习自然语言处理](https://space.bilibili.com/507524288)
12. [LLM Visualization](https://bbycroft.net/llm)
13. [知乎: 原石人类](https://www.zhihu.com/people/zhang-shi-tou-88-98/posts)
14. [B站：小黑黑讲AI](https://space.bilibili.com/1963375439/?spm_id_from=333.999.0.0)
15. [B站：面壁的车辆工程师](https://space.bilibili.com/669720247/?spm_id_from=333.999.0.0)
16. [B站：AI老兵文哲](https://space.bilibili.com/472543316/?spm_id_from=333.999.0.0)
17. [Large Language Models (LLMs) with Colab notebooks](https://mlabonne.github.io/blog/)
18. [YTB：IBM Technology](https://www.youtube.com/@IBMTechnology)
19. [YTB: Unify Reading Paper Group](https://www.youtube.com/playlist?list=PLwNuX3xB_tv91QvDXlW2TjrLGHW51uMul)
20. [Chip Huyen](https://huyenchip.com/blog/)
21. [How Much VRAM](https://github.com/AlexBodner/How_Much_VRAM)
22. [Blog: 科学空间（苏剑林）](https://kexue.fm/)
23. [YTB: Hyung Won Chung](https://www.youtube.com/watch?v=dbo3kNKPaUA)
24. [Blog: Tejaswi kashyap](https://medium.com/@tejaswi_kashyap)
25. [Blog: 小昇的博客](https://xiaosheng.blog/)
26. [知乎: ybq](https://www.zhihu.com/people/ybq-29-32/posts)
27. [W&B articles](https://wandb.ai/fully-connected)
28. [Huggingface Blog](https://huggingface.co/blog/zh)
29. [Blog: GbyAI](https://gby.ai/)
30. [Blog: mlabonne](https://mlabonne.github.io/blog/)
31. [LLM-Action](https://github.com/liguodongiot/llm-action)
32. [Blog: Lil’Log (OponAI)](https://lilianweng.github.io/)

<div align="right">
    <b><a href="#Contents">None↥ 返回顶部</a></b>
</div>

## 论文 Paper

> [!NOTE]
> 🤝[Huggingface Daily Papers](https://huggingface.co/papers)、[Cool Papers](https://papers.cool/)、[ML Papers Explained](https://github.com/dair-ai/ML-Papers-Explained)

1. [Hermes-3-Technical-Report](https://nousresearch.com/wp-content/uploads/2024/08/Hermes-3-Technical-Report.pdf)
2. [The Llama 3 Herd of Models](https://arxiv.org/abs/2407.21783)
3. [Qwen Technical Report](https://arxiv.org/abs/2309.16609)
4. [Qwen2 Technical Report](https://arxiv.org/abs/2407.10671)
5. [Qwen2-vl Technical Report](https://arxiv.org/abs/2409.12191)
6. [DeepSeek LLM: Scaling Open-Source Language Models with Longtermism](https://arxiv.org/abs/2401.02954)
7. [DeepSeek-V2: A Strong, Economical, and Efficient Mixture-of-Experts Language Model](https://arxiv.org/abs/2405.04434)
8. [Baichuan 2: Open Large-scale Language Models](https://arxiv.org/abs/2309.10305)
9. [DataComp-LM: In search of the next generation of training sets for language models](https://arxiv.org/abs/2406.11794)
10. [OLMo: Accelerating the Science of Language Models](https://arxiv.org/abs/2402.00838)
11. [MAP-Neo: Highly Capable and Transparent Bilingual Large Language Model Series](https://arxiv.org/abs/2405.19327)
12. [Chinese Tiny LLM: Pretraining a Chinese-Centric Large Language Model](https://arxiv.org/abs/2404.04167)
13. [Phi-3 Technical Report: A Highly Capable Language Model Locally on Your Phone](https://arxiv.org/abs/2404.14219)
14. [Jamba-1.5: Hybrid Transformer-Mamba Models at Scale](https://arxiv.org/abs/2408.12570v1)
15. [Jamba: A Hybrid Transformer-Mamba Language Model](https://arxiv.org/abs/2403.19887)
16. [Textbooks Are All You Need](https://arxiv.org/abs/2306.11644)
17. [Unleashing the Power of Data Tsunami: A Comprehensive Survey on Data Assessment and Selection for Instruction Tuning of Language Models](https://arxiv.org/abs/2408.02085) `data`
18. [OLMoE: Open Mixture-of-Experts Language Models](https://arxiv.org/abs/2409.02060)
19. [Model Merging Paper](https://huggingface.co/collections/osanseviero/model-merging-65097893623330a3a51ead66)
20. [Baichuan-Omni Technical Report](https://arxiv.org/abs/2410.08565)
21. [1.5-Pints Technical Report: Pretraining in Days, Not Months – Your Language Model Thrives on Quality Data](https://arxiv.org/abs/2408.03506)
22. [Baichuan Alignment Technical Report](https://arxiv.org/abs/2410.14940v1)
23. [Hunyuan-Large: An Open-Source MoE Model with 52 Billion Activated Parameters by Tencent](https://arxiv.org/abs/2411.02265)
24. [Molmo and PixMo: Open Weights and Open Data for State-of-the-Art Multimodal Models](https://arxiv.org/abs/2409.17146)
25. [TÜLU 3: Pushing Frontiers in Open Language Model Post-Training](https://arxiv.org/abs/2411.15124)
26. [Phi-4 Technical Report](https://arxiv.org/abs/2412.08905)
27. [Expanding Performance Boundaries of Open-Source Multimodal Models with Model, Data, and Test-Time Scaling](https://arxiv.org/abs/2412.05271)

<div align="right">
    <b><a href="#Contents">None↥ 返回顶部</a></b>
</div>

## 提示 Tips

1. [What We Learned from a Year of Building with LLMs (Part I)](https://www.oreilly.com/radar/what-we-learned-from-a-year-of-building-with-llms-part-i/)
2. [What We Learned from a Year of Building with LLMs (Part II)](https://www.oreilly.com/radar/what-we-learned-from-a-year-of-building-with-llms-part-ii/)
3. [What We Learned from a Year of Building with LLMs (Part III): Strategy](https://www.oreilly.com/radar/what-we-learned-from-a-year-of-building-with-llms-part-iii-strategy/)
4. [轻松入门大语言模型（LLM）](https://www.bilibili.com/video/BV1pF4m1V7FB/?spm_id_from=333.999.0.0&vd_source=c739db1ebdd361d47af5a0b8497417db)
5. [LLMs for Text Classification: A Guide to Supervised Learning](https://www.striveworks.com/blog/llms-for-text-classification-a-guide-to-supervised-learning)
6. [Unsupervised Text Classification: Categorize Natural Language With LLMs](https://www.striveworks.com/blog/unsupervised-text-classification-how-to-use-llms-to-categorize-natural-language-data)
7. [Text Classification With LLMs: A Roundup of the Best Methods](https://www.striveworks.com/blog/text-classification-with-llms-a-roundup-of-the-best-methods)
8. [LLM Pricing](https://docs.google.com/spreadsheets/d/18GHPEBJzDbICmMStPVkNWA_hQHiWmLcqUdEJA1b4MJM/edit?gid=0#gid=0)
9. [Uncensor any LLM with abliteration](https://huggingface.co/blog/mlabonne/abliteration)
10. [Tiny LLM Universe](https://github.com/datawhalechina/tiny-universe)
11. [Zero-Chatgpt](https://github.com/AI-Study-Han/Zero-Chatgpt)
12. [Zero-Qwen-VL](https://github.com/AI-Study-Han/Zero-Qwen-VL)
13. [finetune-Qwen2-VL](https://github.com/zhangfaen/finetune-Qwen2-VL)
14. [MPP-LLaVA](https://github.com/Coobiw/MPP-LLaVA)
15. [build_MiniLLM_from_scratch](https://github.com/Tongjilibo/build_MiniLLM_from_scratch)
16. [Tiny LLM zh](https://github.com/wdndev/tiny-llm-zh)
17. [MiniMind](https://github.com/jingyaogong/minimind): 3小时完全从0训练一个仅有26M的小参数GPT，最低仅需2G显卡即可推理训练.
18. [LLM-Travel](https://github.com/Glanvery/LLM-Travel): 致力于深入理解、探讨以及实现与大模型相关的各种技术、原理和应用
19. [Knowledge distillation: Teaching LLM's with synthetic data](https://wandb.ai/byyoung3/ML_NEWS3/reports/Knowledge-distillation-Teaching-LLM-s-with-synthetic-data--Vmlldzo5MTMyMzA2)
20. [Part 1: Methods for adapting large language models](https://ai.meta.com/blog/adapting-large-language-models-llms/)
21. [Part 2: To fine-tune or not to fine-tune](https://ai.meta.com/blog/when-to-fine-tune-llms-vs-other-techniques/)
22. [Part 3: How to fine-tune: Focus on effective datasets](https://ai.meta.com/blog/how-to-fine-tune-llms-peft-dataset-curation/)
23. [Reader-LM: Small Language Models for Cleaning and Converting HTML to Markdown](https://jina.ai/news/reader-lm-small-language-models-for-cleaning-and-converting-html-to-markdown/?nocache=1)
24. [LLMs应用构建一年之心得](https://iangyan.github.io/2024/09/08/building-with-llms-part-1/)
25. [LLM训练-pretrain](https://zhuanlan.zhihu.com/p/718354385)
26. [pytorch-llama](https://github.com/hkproj/pytorch-llama): LLaMA 2 implemented from scratch in PyTorch.
27. [Preference Optimization for Vision Language Models with TRL](https://huggingface.co/blog/dpo_vlm) 【[support model](https://huggingface.co/docs/transformers/model_doc/auto#transformers.AutoModelForVision2Seq)】
28. [Fine-tuning visual language models using SFTTrainer](https://huggingface.co/blog/vlms) 【[docs](https://huggingface.co/docs/trl/sft_trainer#extending-sfttrainer-for-vision-language-models)】
29. [A Visual Guide to Mixture of Experts (MoE)](https://newsletter.maartengrootendorst.com/p/a-visual-guide-to-mixture-of-experts)
30. [Role-Playing in Large Language Models like ChatGPT](https://promptengineering.org/role-playing-in-large-language-models-like-chatgpt/)
31. [Distributed Training Guide](https://github.com/LambdaLabsML/distributed-training-guide): Best practices & guides on how to write distributed pytorch training code.
32. [Chat Templates](https://hf-mirror.com/blog/chat-templates)
33. [Top 20+ RAG Interview Questions](https://www.analyticsvidhya.com/blog/2024/04/rag-interview-questions/)
34. [LLM-Dojo 开源大模型学习场所，使用简洁且易阅读的代码构建模型训练框架](https://github.com/mst272/LLM-Dojo)

<div align="right">
    <b><a href="#Contents">None↥ 返回顶部</a></b>
</div>

![](https://camo.githubusercontent.com/2722992d519a722218f896d5f5231d49f337aaff4514e78bd59ac935334e916a/68747470733a2f2f692e696d6775722e636f6d2f77617856496d762e706e67)

如果你觉得本项目对你有帮助，欢迎引用：
```bib
@misc wang2024llm,
      title={awesome-LLM-resourses}, 
      author={Rongsheng Wang},
      year={2024},
      publisher = {GitHub},
      journal = {GitHub repository},
      howpublished = {\url{https://github.com/WangRongsheng/awesome-LLM-resourses}},
```

[![Forkers repo roster for @WangRongsheng/awesome-LLM-resourses](https://reporoster.com/forks/WangRongsheng/awesome-LLM-resourses)](https://github.com/WangRongsheng/awesome-LLM-resourses/network/members)

[![Stargazers repo roster for @WangRongsheng/awesome-LLM-resourses](https://reporoster.com/stars/WangRongsheng/awesome-LLM-resourses)](https://github.com/WangRongsheng/awesome-LLM-resourses/stargazers)

[![Stargazers over time](https://starchart.cc/WangRongsheng/awesome-LLM-resourses.svg)](https://starchart.cc/WangRongsheng/awesome-LLM-resourses)