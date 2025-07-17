# 精选开源 AI 工具列表 [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

[🇨🇳 中文版](README_CN.md) | [🇺🇸 English](README.md)

一份精心整理的 737+ 个开源 AI 工具与项目清单，按应用类型和功能分类。

本列表专注于开发者可以使用、修改、贡献的开源 AI 工具。每个工具都经过严格筛选，依据其功能性、代码质量、社区活跃度及实际应用价值。所有项目均为持续维护状态，并具备社区采用度。

## 目录

- [商业管理（6 个工具）](#商业管理)
- [聊天机器人与虚拟助手（149 个工具）](#聊天机器人与虚拟助手)
- [编程与开发（106 个工具）](#编程与开发)
- [开发者工具与基础设施（4 个工具）](#开发者工具与基础设施)
- [教育与翻译（6 个工具）](#教育与翻译)
- [游戏与娱乐（6 个工具）](#游戏与娱乐)
- [图像生成与编辑（214 个工具）](#图像生成与编辑)
- [营销与广告（5 个工具）](#营销与广告)
- [音乐与音频（18 个工具）](#音乐与音频)
- [其他 AI 工具（32 个工具）](#其他-ai-工具)
- [研究与数据分析（112 个工具）](#研究与数据分析)
- [视频与动画（38 个工具）](#视频与动画)
- [语音合成与转换（4 个工具）](#语音合成与转换)
- [写作与编辑（37 个工具）](#写作与编辑)
- [项目统计](#项目统计)
- [贡献指南](#贡献指南)

## 商业管理

面向企业流程、工作流优化和生产力提升的 AI 解决方案。

- **[apache/airflow](https://github.com/apache/airflow)** ⭐ 41,023 - Apache Airflow：用于编排、调度和监控工作流的平台
- **[paperless-ngx/paperless-ngx](https://github.com/paperless-ngx/paperless-ngx)** ⭐ 24,458 - 社区支持的开源文档管理系统，具有机器学习功能的无纸化数字档案系统
- **[joaomdmoura/crewAI](https://github.com/joaomdmoura/crewAI)** ⭐ 22,996 - 角色扮演自主 AI 智能体框架。通过简单的 Python 来创建协作性自主 AI 智能体。
- **[microsoft/TaskWeaver](https://github.com/microsoft/TaskWeaver)** ⭐ 6,013 - 一个面向代码优先的智能体框架，可无缝规划和执行数据分析任务。
- **[microsoft/autogen](https://github.com/microsoft/autogen)** ⭐ 35,755 - 一个编程框架，用于构建具有可定义智能体的多智能体对话系统
- **[microsoft/semantic-kernel](https://github.com/microsoft/semantic-kernel)** ⭐ 23,019 - 将尖端 LLM 技术快速轻松地集成到您的应用程序中

## 聊天机器人与虚拟助手

支持对话的 AI 系统，从客户服务到个人助理。

- **[ollama/ollama](https://github.com/ollama/ollama)** ⭐ 131,023 - 使用 Llama 3.2、Mistral、Gemma 2 等大语言模型的本地运行工具
- **[ggerganov/llama.cpp](https://github.com/ggerganov/llama.cpp)** ⭐ 81,194 - LLaMA 模型的 C/C++ 实现端口
- **[microsoft/autogen](https://github.com/microsoft/autogen)** ⭐ 35,755 - 一个编程框架，用于构建具有可定义智能体的多智能体对话系统
- **[mudler/LocalAI](https://github.com/mudler/LocalAI)** ⭐ 33,881 - 开源的 OpenAI、Claude 等的免费替代品。自托管和本地优先。无需 GPU 的 OpenAI 替代品
- **[microsoft/semantic-kernel](https://github.com/microsoft/semantic-kernel)** ⭐ 23,019 - 将尖端 LLM 技术快速轻松地集成到您的应用程序中
- **[joaomdmoura/crewAI](https://github.com/joaomdmoura/crewAI)** ⭐ 22,996 - 角色扮演自主 AI 智能体框架
- **[continuedev/continue](https://github.com/continuedev/continue)** ⭐ 21,923 - ⏩ 开源的 AI 代码助手
- **[suno-ai/bark](https://github.com/suno-ai/bark)** ⭐ 41,524 - 🔊 文本提示生成音频模型
- **[LangflowAI/langflow](https://github.com/LangflowAI/langflow)** ⭐ 41,471 - ⛓️ Langflow 是一个低代码的 AI 应用构建平台
- **[immich-app/immich](https://github.com/immich-app/immich)** ⭐ 59,688 - 高性能的自托管照片和视频管理解决方案
- **[lobehub/lobe-chat](https://github.com/lobehub/lobe-chat)** ⭐ 59,593 - 🤯 Lobe Chat - 现代化设计的开源 ChatGPT/Claude/Gemini/Ollama 聊天框架
- **[lencx/ChatGPT](https://github.com/lencx/ChatGPT)** ⭐ 55,119 - 🔮 ChatGPT 桌面应用程序（Mac、Windows 和 Linux）
- **[LAION-AI/Open-Assistant](https://github.com/LAION-AI/Open-Assistant)** ⭐ 37,623 - OpenAssistant 是一个基于聊天的助手，可以理解任务，与第三方系统交互并动态检索信息
- **[Mintplex-Labs/anything-llm](https://github.com/Mintplex-Labs/anything-llm)** ⭐ 35,089 - 一个全栈应用程序，将任何文档转换为智能聊天机器人
- **[Chanzhaoyu/chatgpt-web](https://github.com/Chanzhaoyu/chatgpt-web)** ⭐ 31,859 - 使用 Express 和 Vue3 搭建的 ChatGPT 演示网页
- **[qdrant/qdrant](https://github.com/qdrant/qdrant)** ⭐ 21,989 - Qdrant - 大规模向量数据库和向量搜索引擎
- **[ChatGPTNextWeb/ChatGPT-Next-Web](https://github.com/ChatGPTNextWeb/ChatGPT-Next-Web)** ⭐ 82,737 - 跨平台的 ChatGPT/Gemini 用户界面（Web / PWA / Linux / Win / MacOS）
- **[SillyTavern/SillyTavern](https://github.com/SillyTavern/SillyTavern)** ⭐ 9,956 - 面向高级用户的 LLM 前端
- **[reworkd/AgentGPT](https://github.com/reworkd/AgentGPT)** ⭐ 32,593 - 🤖 在浏览器中组装、配置和部署自主 AI 智能体
- **[mckaywrigley/chatbot-ui](https://github.com/mckaywrigley/chatbot-ui)** ⭐ 30,503 - 适用于每个人的开源 AI 聊天机器人 UI
- **[Bin-Huang/chatbox](https://github.com/Bin-Huang/chatbox)** ⭐ 23,083 - 多平台的桌面 AI 聊天客户端
- **[mlc-ai/web-llm](https://github.com/mlc-ai/web-llm)** ⭐ 16,180 - 通过 WebGPU 在浏览器中运行大型语言模型
- **[chatchat-space/Langchain-Chatchat](https://github.com/chatchat-space/Langchain-Chatchat)** ⭐ 34,189 - Langchain-Chatchat（原 Langchain-ChatGLM）基于 Langchain 与 ChatGLM 等大语言模型的本地知识库问答应用
- **[all-in-one-ai/all-in-one-ai](https://github.com/all-in-one-ai/all-in-one-ai)** ⭐ 8,756 - 一站式 AI 聊天平台
- **[FlowiseAI/Flowise](https://github.com/FlowiseAI/Flowise)** ⭐ 33,999 - 拖拽式 LLM 应用构建器
- **[embedchain/embedchain](https://github.com/embedchain/embedchain)** ⭐ 9,593 - 记忆化 AI 应用程序框架
- **[mlc-ai/mlc-llm](https://github.com/mlc-ai/mlc-llm)** ⭐ 20,397 - 通用部署解决方案，让每个人都能在各种硬件后端和原生应用程序上本地运行大型语言模型
- **[invoke-ai/InvokeAI](https://github.com/invoke-ai/InvokeAI)** ⭐ 25,070 - Invoke 是一个用于稳定扩散模型的领先创意引擎
- **[danny-avila/LibreChat](https://github.com/danny-avila/LibreChat)** ⭐ 20,834 - 增强的 ChatGPT 克隆版：具有 OpenAI、Claude、Bing、PaLM 2、AI21、Cohere、Llama、Hugging Face 等功能
- **[GaiZhenbiao/ChuanhuChatGPT](https://github.com/GaiZhenbiao/ChuanhuChatGPT)** ⭐ 15,451 - GUI for ChatGPT API and many LLMs. Supports agents, file-based QA, GPT finetuning and query with web search
- **[langgenius/dify](https://github.com/langgenius/dify)** ⭐ 69,242 - Dify 是一个开源的 LLM 应用开发平台
- **[QuivrHQ/quivr](https://github.com/QuivrHQ/quivr)** ⭐ 38,026 - 开源 RAG 框架，用于使用 AI 构建聊天机器人
- **[streamlit/streamlit](https://github.com/streamlit/streamlit)** ⭐ 36,824 - Streamlit - 更快构建和共享数据应用程序的方式
- **[Significant-Gravitas/AutoGPT](https://github.com/Significant-Gravitas/AutoGPT)** ⭐ 172,166 - AutoGPT 是自主 AI 智能体的先驱框架
- **[openai-translator/openai-translator](https://github.com/openai-translator/openai-translator)** ⭐ 25,673 - 基于 ChatGPT API 的划词翻译浏览器插件和跨平台桌面端应用
- **[nomic-ai/gpt4all](https://github.com/nomic-ai/gpt4all)** ⭐ 73,047 - GPT4All: 运行本地大型语言模型的开源生态系统
- **[langchain-ai/langchain](https://github.com/langchain-ai/langchain)** ⭐ 109,242 - 🦜🔗 构建语言模型应用程序的框架
- **[microsoft/ChatTTS](https://github.com/microsoft/ChatTTS)** ⭐ 36,584 - 为聊天场景设计的文本转语音模型
- **[THUDM/ChatGLM-6B](https://github.com/THUDM/ChatGLM-6B)** ⭐ 41,136 - ChatGLM-6B: 开源双语对话语言模型
- **[ChaoningZhang/MobileLLM](https://github.com/ChaoningZhang/MobileLLM)** ⭐ 3,845 - [ICML 2024] MobileLLM：针对移动设备优化子 10 亿参数语言模型
- **[TabbyML/tabby](https://github.com/TabbyML/tabby)** ⭐ 23,806 - 自托管 AI 编码助手
- **[run-llama/llama_index](https://github.com/run-llama/llama_index)** ⭐ 38,893 - LlamaIndex 是一个用于 LLM 应用程序的数据框架
- **[microsoft/DeepSpeed](https://github.com/microsoft/DeepSpeed)** ⭐ 37,221 - DeepSpeed 是一个深度学习优化库
- **[Aider-AI/aider](https://github.com/Aider-AI/aider)** ⭐ 25,568 - aider 是在您的终端中运行的 AI 配对编程工具
- **[Qwen/Qwen](https://github.com/Qwen/Qwen)** ⭐ 14,658 - 阿里云发布的第一个大规模语言模型系列。
- **[microsoft/JARVIS](https://github.com/microsoft/JARVIS)** ⭐ 24,336 - JARVIS，一个连接 LLM 和 ML 社区的系统
- **[gpt-engineer-org/gpt-engineer](https://github.com/gpt-engineer-org/gpt-engineer)** ⭐ 53,221 - 从自然语言规范构建整个代码库
- **[openai/whisper](https://github.com/openai/whisper)** ⭐ 79,168 - 通过大规模弱监督实现的鲁棒语音识别
- **[OpenDevin/OpenDevin](https://github.com/OpenDevin/OpenDevin)** ⭐ 40,399 - 🐚 OpenDevin：能够执行复杂工程任务的 AI 软件工程师
- **[chaitin/SafeLine](https://github.com/chaitin/SafeLine)** ⭐ 13,839 - 一款足够简单、足够好用、足够强的免费 WAF
- **[geekan/MetaGPT](https://github.com/geekan/MetaGPT)** ⭐ 46,568 - 多智能体框架：给定一行需求，返回产品需求文档、设计、任务、代码
- **[xinntao/Real-ESRGAN](https://github.com/xinntao/Real-ESRGAN)** ⭐ 31,719 - Real-ESRGAN 旨在开发用于通用图像/视频修复的实用算法
- **[gradio-app/gradio](https://github.com/gradio-app/gradio)** ⭐ 36,262 - 通过友好的 web 界面快速创建 AI 应用
- **[microsoft/vscode](https://github.com/microsoft/vscode)** ⭐ 169,298 - Visual Studio Code
- **[huggingface/transformers](https://github.com/huggingface/transformers)** ⭐ 145,751 - 🤗 Transformers：适用于 Pytorch、TensorFlow 和 JAX 的最先进机器学习
- **[microsoft/graphrag](https://github.com/microsoft/graphrag)** ⭐ 24,123 - 一个利用大型语言模型从非结构化文本中创建知识图谱的模块化图形支持检索增强生成（RAG）系统
- **[langchain-ai/langgraph](https://github.com/langchain-ai/langgraph)** ⭐ 9,953 - 使用 LLM 构建有状态、多参与者应用程序
- **[assafelovic/gpt-researcher](https://github.com/assafelovic/gpt-researcher)** ⭐ 17,135 - GPT 研究员是一个自主智能体，专为各种任务的全面在线研究而设计
- **[karpathy/nanoGPT](https://github.com/karpathy/nanoGPT)** ⭐ 42,262 - 用于训练/微调中等大小 GPT 的最简单、最快的存储库
- **[RVC-Project/Retrieval-based-Voice-Conversion-WebUI](https://github.com/RVC-Project/Retrieval-based-Voice-Conversion-WebUI)** ⭐ 27,739 - 基于检索的实时语音转换
- **[open-mmlab/mmdetection](https://github.com/open-mmlab/mmdetection)** ⭐ 30,615 - OpenMMLab 检测工具箱和基准
- **[mouredev/Hello-Python](https://github.com/mouredev/Hello-Python)** ⭐ 28,094 - 从零学习 Python 编程语言课程
- **[dani-garcia/vaultwarden](https://github.com/dani-garcia/vaultwarden)** ⭐ 42,076 - 用 Rust 编写的非官方 Bitwarden 兼容服务器
- **[paul-gauthier/aider](https://github.com/paul-gauthier/aider)** ⭐ 25,568 - aider 是 AI 配对编程在您的终端中
- **[1Panel-dev/1Panel](https://github.com/1Panel-dev/1Panel)** ⭐ 25,199 - 🔥🔥🔥 现代化、开源的 Linux 服务器运维管理面板
- **[microsoft/playwright](https://github.com/microsoft/playwright)** ⭐ 69,952 - Playwright 是一个为现代网络应用程序设计的框架
- **[apple/ml-ferret](https://github.com/apple/ml-ferret)** ⭐ 8,674 - Ferret: 参考和定位多模态大型语言模型
- **[microsoft/PowerToys](https://github.com/microsoft/PowerToys)** ⭐ 115,436 - Windows 系统实用工具
- **[netease-youdao/QAnything](https://github.com/netease-youdao/QAnything)** ⭐ 12,693 - 问答系统：基于任何可视化和本地或云端 LLM
- **[CopilotKit/CopilotKit](https://github.com/CopilotKit/CopilotKit)** ⭐ 14,503 - React UI + 聊天机器人优先 AI 智能体框架
- **[reflex-dev/reflex](https://github.com/reflex-dev/reflex)** ⭐ 21,639 - 🕸️ 纯 Python 构建和部署 web 应用程序。立即在几秒钟内部署

## 编程与开发

为开发者设计的编程、调试、代码生成和软件开发的 AI 工具。

- **[microsoft/vscode](https://github.com/microsoft/vscode)** ⭐ 169,298 - Visual Studio Code
- **[github/copilot.vim](https://github.com/github/copilot.vim)** ⭐ 8,704 - GitHub Copilot 的 Neovim 插件
- **[continuedev/continue](https://github.com/continuedev/continue)** ⭐ 21,923 - ⏩ 开源的 AI 代码助手
- **[gpt-engineer-org/gpt-engineer](https://github.com/gpt-engineer-org/gpt-engineer)** ⭐ 53,221 - 从自然语言规范构建整个代码库
- **[Aider-AI/aider](https://github.com/Aider-AI/aider)** ⭐ 25,568 - aider 是在您的终端中运行的 AI 配对编程工具
- **[OpenDevin/OpenDevin](https://github.com/OpenDevin/OpenDevin)** ⭐ 40,399 - 🐚 OpenDevin：能够执行复杂工程任务的 AI 软件工程师
- **[TabbyML/tabby](https://github.com/TabbyML/tabby)** ⭐ 23,806 - 自托管 AI 编码助手
- **[microsoft/DeepSpeed](https://github.com/microsoft/DeepSpeed)** ⭐ 37,221 - DeepSpeed 是一个深度学习优化库
- **[microsoft/JARVIS](https://github.com/microsoft/JARVIS)** ⭐ 24,336 - JARVIS，一个连接 LLM 和 ML 社区的系统
- **[geekan/MetaGPT](https://github.com/geekan/MetaGPT)** ⭐ 46,568 - 多智能体框架：给定一行需求，返回产品需求文档、设计、任务、代码
- **[karpathy/nanoGPT](https://github.com/karpathy/nanoGPT)** ⭐ 42,262 - 用于训练/微调中等大小 GPT 的最简单、最快的存储库
- **[microsoft/playwright](https://github.com/microsoft/playwright)** ⭐ 69,952 - Playwright 是一个为现代网络应用程序设计的框架
- **[microsoft/PowerToys](https://github.com/microsoft/PowerToys)** ⭐ 115,436 - Windows 系统实用工具
- **[paul-gauthier/aider](https://github.com/paul-gauthier/aider)** ⭐ 25,568 - aider 是 AI 配对编程在您的终端中
- **[1Panel-dev/1Panel](https://github.com/1Panel-dev/1Panel)** ⭐ 25,199 - 🔥🔥🔥 现代化、开源的 Linux 服务器运维管理面板
- **[CopilotKit/CopilotKit](https://github.com/CopilotKit/CopilotKit)** ⭐ 14,503 - React UI + 聊天机器人优先 AI 智能体框架
- **[huggingface/transformers](https://github.com/huggingface/transformers)** ⭐ 145,751 - 🤗 Transformers：适用于 Pytorch、TensorFlow 和 JAX 的最先进机器学习
- **[pytorch/pytorch](https://github.com/pytorch/pytorch)** ⭐ 86,951 - Python 中的张量和动态神经网络，具有强大的 GPU 加速
- **[tensorflow/tensorflow](https://github.com/tensorflow/tensorflow)** ⭐ 189,133 - 适用于所有人的开源机器学习框架
- **[scikit-learn/scikit-learn](https://github.com/scikit-learn/scikit-learn)** ⭐ 62,100 - scikit-learn：Python 中的机器学习
- **[microsoft/ML-For-Beginners](https://github.com/microsoft/ML-For-Beginners)** ⭐ 71,701 - 所有人的 12 周，26 节课，52 个测验，经典机器学习课程
- **[fastai/fastai](https://github.com/fastai/fastai)** ⭐ 27,003 - fastai 深度学习库
- **[ageitgey/face_recognition](https://github.com/ageitgey/face_recognition)** ⭐ 54,242 - 世界上最简单的 Python 人脸识别 API
- **[CompVis/stable-diffusion](https://github.com/CompVis/stable-diffusion)** ⭐ 72,041 - 潜在扩散模型的高分辨率图像合成存储库
- **[facebookresearch/fairseq](https://github.com/facebookresearch/fairseq)** ⭐ 31,324 - Facebook AI Research 序列到序列工具包
- **[google-research/google-research](https://github.com/google-research/google-research)** ⭐ 35,956 - Google 研究
- **[openai/gym](https://github.com/openai/gym)** ⭐ 35,479 - 用于开发和比较强化学习算法的工具包
- **[deepfakes/faceswap](https://github.com/deepfakes/faceswap)** ⭐ 54,256 - 面向所有人的 Deepfake 软件
- **[apache/spark](https://github.com/apache/spark)** ⭐ 40,752 - Apache Spark - 大数据的统一分析引擎
- **[3b1b/manim](https://github.com/3b1b/manim)** ⭐ 72,041 - 用于解释数学视频的动画引擎
- **[comfyanonymous/ComfyUI](https://github.com/comfyanonymous/ComfyUI)** ⭐ 70,061 - 最强大且模块化的稳定扩散 GUI
- **[microsoft/LightGBM](https://github.com/microsoft/LightGBM)** ⭐ 17,012 - 快速、分布式、高性能梯度提升
- **[facebook/prophet](https://github.com/facebook/prophet)** ⭐ 18,669 - 为具有线性或非线性趋势的时间序列数据生成高质量预测的工具
- **[explosion/spaCy](https://github.com/explosion/spaCy)** ⭐ 30,765 - 💫 Python 和 Cython 中的工业级自然语言处理
- **[keras-team/keras](https://github.com/keras-team/keras)** ⭐ 62,465 - 人类深度学习
- **[apache/airflow](https://github.com/apache/airflow)** ⭐ 41,023 - Apache Airflow - 以编程方式创作、调度和监控工作流的平台
- **[Textualize/rich](https://github.com/Textualize/rich)** ⭐ 50,734 - Rich 是一个 Python 库，用于在终端中创建丰富的文本和美丽的格式
- **[microsoft/TypeScript](https://github.com/microsoft/TypeScript)** ⭐ 102,675 - TypeScript 是 JavaScript 的超集，可编译为干净的 JavaScript 输出
- **[alibaba/arthas](https://github.com/alibaba/arthas)** ⭐ 36,085 - Alibaba Java 诊断利器 Arthas/Alibaba Java Diagnostic Tool Arthas
- **[open-mmlab/mmdetection](https://github.com/open-mmlab/mmdetection)** ⭐ 30,615 - OpenMMLab 检测工具箱和基准
- **[yunjey/pytorch-tutorial](https://github.com/yunjey/pytorch-tutorial)** ⭐ 30,759 - 深度学习研究人员的 PyTorch 教程
- **[josephmisiti/awesome-machine-learning](https://github.com/josephmisiti/awesome-machine-learning)** ⭐ 66,847 - 精选的机器学习框架、库和软件列表
- **[donnemartin/system-design-primer](https://github.com/donnemartin/system-design-primer)** ⭐ 287,433 - 学习如何设计大规模系统
- **[tensorflow/models](https://github.com/tensorflow/models)** ⭐ 77,419 - 使用 TensorFlow 构建的模型和示例
- **[toddmotto/public-apis](https://github.com/toddmotto/public-apis)** ⭐ 324,264 - 用于软件和 Web 开发的免费 API 集合列表
- **[jackfrued/Python-100-Days](https://github.com/jackfrued/Python-100-Days)** ⭐ 162,110 - Python - 100 天从新手到大师
- **[TheAlgorithms/Python](https://github.com/TheAlgorithms/Python)** ⭐ 198,113 - 所有算法在 Python 中实现
- **[vinta/awesome-python](https://github.com/vinta/awesome-python)** ⭐ 230,738 - 精选的 Python 框架、库、软件和资源列表
- **[karpathy/minGPT](https://github.com/karpathy/minGPT)** ⭐ 22,269 - OpenAI GPT (生成预训练变换器) 训练的最小 PyTorch 重新实现
- **[facebookresearch/detectron2](https://github.com/facebookresearch/detectron2)** ⭐ 31,511 - Detectron2 是 FAIR 的下一代库，提供最先进的检测和分割算法
- **[microsoft/Web-Dev-For-Beginners](https://github.com/microsoft/Web-Dev-For-Beginners)** ⭐ 84,498 - 24 节课，12 周，适合所有人的 Web 开发
- **[microsoft/Data-Science-For-Beginners](https://github.com/microsoft/Data-Science-For-Beginners)** ⭐ 28,673 - 10 周，20 节课，所有人的数据科学课程！
- **[microsoft/AI-For-Beginners](https://github.com/microsoft/AI-For-Beginners)** ⭐ 36,170 - 12 周，24 节课，所有人的 AI 课程！
- **[microsoft/generative-ai-for-beginners](https://github.com/microsoft/generative-ai-for-beginners)** ⭐ 68,792 - 21 节课，为所有人提供生成式 AI 入门教程
- **[openai/gym](https://github.com/openai/gym)** ⭐ 35,479 - 开发和比较强化学习算法的工具包
- **[huggingface/datasets](https://github.com/huggingface/datasets)** ⭐ 20,374 - 🤗 具有快速、易用和高效数据操作工具的 ML 模型即用数据集的最大中心
- **[deepfakes/faceswap](https://github.com/deepfakes/faceswap)** ⭐ 54,256 - 面向所有人的 Deepfake 软件
- **[ray-project/ray](https://github.com/ray-project/ray)** ⭐ 35,298 - Ray 是一个统一框架，用于扩展 AI 和 Python 应用程序
- **[plotly/dash](https://github.com/plotly/dash)** ⭐ 22,006 - 用 Python、R、Julia 和 Jupyter 构建数据应用程序
- **[pallets/flask](https://github.com/pallets/flask)** ⭐ 69,068 - Python 微框架，用于构建 web 应用程序
- **[django/django](https://github.com/django/django)** ⭐ 82,458 - 完美主义者与期限的 Web 框架
- **[encode/django-rest-framework](https://github.com/encode/django-rest-framework)** ⭐ 29,132 - Web APIs for Django，简单实用
- **[celery/celery](https://github.com/celery/celery)** ⭐ 25,549 - 基于分布式消息传递的异步任务队列/作业队列
- **[ansible/ansible](https://github.com/ansible/ansible)** ⭐ 63,890 - Ansible 是一个极其简单的 IT 自动化平台
- **[python/cpython](https://github.com/python/cpython)** ⭐ 65,126 - Python 编程语言
- **[psf/requests](https://github.com/psf/requests)** ⭐ 52,931 - 人类的 HTTP 库 ™
- **[numpy/numpy](https://github.com/numpy/numpy)** ⭐ 28,827 - 使用 Python 进行科学计算的基础包
- **[pandas-dev/pandas](https://github.com/pandas-dev/pandas)** ⭐ 44,316 - 灵活且强大的 Python 数据分析/操作库
- **[matplotlib/matplotlib](https://github.com/matplotlib/matplotlib)** ⭐ 21,073 - matplotlib：Python 中的绘图
- **[jupyter/notebook](https://github.com/jupyter/notebook)** ⭐ 12,039 - Jupyter 互动笔记本
- **[scipy/scipy](https://github.com/scipy/scipy)** ⭐ 13,417 - 开源科学工具生态系统 for Python
- **[sympy/sympy](https://github.com/sympy/sympy)** ⭐ 13,407 - Python 符号数学库
- **[ipython/ipython](https://github.com/ipython/ipython)** ⭐ 16,448 - 官方 IPython 存储库
- **[Zulko/moviepy](https://github.com/Zulko/moviepy)** ⭐ 13,095 - Python 中的视频编辑
- **[ytdl-org/youtube-dl](https://github.com/ytdl-org/youtube-dl)** ⭐ 134,007 - 从 YouTube.com 和其他视频站点下载视频的命令行程序
- **[python-pillow/Pillow](https://github.com/python-pillow/Pillow)** ⭐ 12,730 - Python 图像库（PIL 的分支）
- **[RasaHQ/rasa](https://github.com/RasaHQ/rasa)** ⭐ 19,265 - 💬 开源机器学习框架，用于自动化基于文本和语音的对话
- **[optuna/optuna](https://github.com/optuna/optuna)** ⭐ 11,398 - 一个超参数优化框架
- **[scrapy/scrapy](https://github.com/scrapy/scrapy)** ⭐ 53,821 - Scrapy，快速高级 web 爬虫框架
- **[requests/requests-html](https://github.com/requests/requests-html)** ⭐ 14,305 - 人类的 Pythonic HTML 解析
- **[aio-libs/aiohttp](https://github.com/aio-libs/aiohttp)** ⭐ 15,468 - Python 异步 HTTP 客户端/服务器框架
- **[encode/httpx](https://github.com/encode/httpx)** ⭐ 13,676 - Python 的下一代 HTTP 客户端
- **[sqlalchemy/sqlalchemy](https://github.com/sqlalchemy/sqlalchemy)** ⭐ 10,041 - Python SQL 工具包和对象关系映射器
- **[alembic/alembic](https://github.com/alembic/alembic)** ⭐ 2,863 - SQLAlchemy 的数据库迁移工具
- **[pydantic/pydantic](https://github.com/pydantic/pydantic)** ⭐ 22,552 - 使用 Python 类型注释进行数据验证
- **[tiangolo/fastapi](https://github.com/tiangolo/fastapi)** ⭐ 79,834 - FastAPI 框架，高性能，易于学习，快速编码，生产就绪
- **[instillai/TensorFlow-Course](https://github.com/instillai/TensorFlow-Course)** ⭐ 16,371 - 🛰️ 简单且易于使用的 TensorFlow 教程
- **[Mikoto10032/DeepLearning](https://github.com/Mikoto10032/DeepLearning)** ⭐ 16,139 - 深度学习入门教程, 优秀文章
- **[ddbourgin/numpy-ml](https://github.com/ddbourgin/numpy-ml)** ⭐ 16,125 - 机器学习，用 numpy 实现
- **[piskvorky/gensim](https://github.com/piskvorky/gensim)** ⭐ 16,099 - 人类的主题建模
- **[cmusatyalab/openface](https://github.com/cmusatyalab/openface)** ⭐ 15,312 - 深度神经网络人脸识别
- **[kailashahirwar/cheatsheets-ai](https://github.com/kailashahirwar/cheatsheets-ai)** ⭐ 15,252 - 深度学习和机器学习研究人员的基本备忘单
- **[ty4z2008/Qix](https://github.com/ty4z2008/Qix)** ⭐ 14,873 - Machine Learning、Deep Learning、PostgreSQL、Distributed System、Node.Js、Golang
- **[iterative/dvc](https://github.com/iterative/dvc)** ⭐ 14,664 - 🦉 数据版本控制和机器学习实验
- **[tensorflow/tfjs-models](https://github.com/tensorflow/tfjs-models)** ⭐ 14,562 - TensorFlow.js 的预训练模型
- **[karpathy/nn-zero-to-hero](https://github.com/karpathy/nn-zero-to-hero)** ⭐ 14,522 - 神经网络：从零到英雄
- **[mrdbourke/pytorch-deep-learning](https://github.com/mrdbourke/pytorch-deep-learning)** ⭐ 14,365 - 学习 PyTorch 深度学习课程的材料
- **[stas00/ml-engineering](https://github.com/stas00/ml-engineering)** ⭐ 14,328 - 机器学习工程开放书籍
- **[virgili0/Virgilio](https://github.com/virgili0/Virgilio)** ⭐ 14,136 - 您的数据科学电子学习新导师
- **[davidsandberg/facenet](https://github.com/davidsandberg/facenet)** ⭐ 14,134 - 使用 Tensorflow 的人脸识别
- **[davisking/dlib](https://github.com/davisking/dlib)** ⭐ 14,066 - 在 C++ 中制作现实世界机器学习和数据分析应用程序的工具包
- **[cvat-ai/cvat](https://github.com/cvat-ai/cvat)** ⭐ 14,060 - 使用 CVAT 进行更好的注释，机器学习的行业领先数据引擎
- **[aishwaryanr/awesome-generative-ai-guide](https://github.com/aishwaryanr/awesome-generative-ai-guide)** ⭐ 13,358 - 生成式 AI 研究更新、面试资源、笔记本等的一站式存储库！
- **[visenger/awesome-mlops](https://github.com/visenger/awesome-mlops)** ⭐ 13,229 - MLOps 参考资料的精选列表
- **[DataTalksClub/mlops-zoomcamp](https://github.com/DataTalksClub/mlops-zoomcamp)** ⭐ 13,003 - DataTalks.Club 的免费 MLOps 课程
- **[carla-simulator/carla](https://github.com/carla-simulator/carla)** ⭐ 12,730 - 自动驾驶研究的开源模拟器
- **[apache/tvm](https://github.com/apache/tvm)** ⭐ 12,450 - 用于 CPU、GPU 和专用加速器的开放深度学习编译器堆栈
- **[tensorflow/playground](https://github.com/tensorflow/playground)** ⭐ 12,439 - 玩转神经网络！
- **[jikexueyuanwiki/tensorflow-zh](https://github.com/jikexueyuanwiki/tensorflow-zh)** ⭐ 12,378 - 谷歌全新开源人工智能系统 TensorFlow 官方文档中文版
- **[zalandoresearch/fashion-mnist](https://github.com/zalandoresearch/fashion-mnist)** ⭐ 12,360 - 类似 MNIST 的时尚产品数据库。基准测试 👇
- **[marcotcr/lime](https://github.com/marcotcr/lime)** ⭐ 11,937 - Lime：解释任何机器学习分类器的预测
- **[AccumulateMore/CV](https://github.com/AccumulateMore/CV)** ⭐ 11,800 - ✔（已完结）最全面的 深度学习 笔记
- **[dair-ai/ML-Papers-of-the-Week](https://github.com/dair-ai/ML-Papers-of-the-Week)** ⭐ 11,627 - 🔥 每周突出展示顶级机器学习论文
- **[DLR-RM/stable-baselines3](https://github.com/DLR-RM/stable-baselines3)** ⭐ 11,105 - PyTorch 版本的 Stable Baselines，强化学习算法的可靠实现
- **[rushter/MLAlgorithms](https://github.com/rushter/MLAlgorithms)** ⭐ 10,865 - 机器学习算法实现的最小和干净示例
- **[qubvel-org/segmentation_models.pytorch](https://github.com/qubvel-org/segmentation_models.pytorch)** ⭐ 10,679 - 具有 500+ 预训练卷积和变换器骨干网络的语义分割模型
- **[aws/amazon-sagemaker-examples](https://github.com/aws/amazon-sagemaker-examples)** ⭐ 10,591 - 示例 📓 Jupyter 笔记本，演示如何使用 🧠 Amazon SageMaker 构建、训练和部署机器学习模型
- **[DataTalksClub/machine-learning-zoomcamp](https://github.com/DataTalksClub/machine-learning-zoomcamp)** ⭐ 10,539 - 免费学习 4 个月的机器学习工程！
- **[kedro-org/kedro](https://github.com/kedro-org/kedro)** ⭐ 10,433 - Kedro 是生产就绪数据科学的工具箱
- **[ultralytics/yolov3](https://github.com/ultralytics/yolov3)** ⭐ 10,421 - YOLOv3 in PyTorch > ONNX > CoreML > TFLite
- **[lexfridman/mit-deep-learning](https://github.com/lexfridman/mit-deep-learning)** ⭐ 10,326 - MIT 深度学习相关课程的教程、作业和竞赛
- **[doccano/doccano](https://github.com/doccano/doccano)** ⭐ 10,144 - 面向机器学习从业者的开源注释工具
- **[Yorko/mlcourse.ai](https://github.com/Yorko/mlcourse.ai)** ⭐ 10,119 - 开放机器学习课程
- **[wandb/wandb](https://github.com/wandb/wandb)** ⭐ 10,095 - AI 开发者平台。使用 Weights & Biases 训练和微调模型，管理从实验到生产的模型
- **[timzhang642/3D-Machine-Learning](https://github.com/timzhang642/3D-Machine-Learning)** ⭐ 10,026 - 3D 机器学习资源存储库
- **[ymcui/Chinese-BERT-wwm](https://github.com/ymcui/Chinese-BERT-wwm)** ⭐ 10,020 - 中文 BERT-wwm 系列模型的全词遮蔽预训练
- **[bigscience-workshop/petals](https://github.com/bigscience-workshop/petals)** ⭐ 9,721 - 🌸 在家运行大语言模型，BitTorrent 风格。微调和推理速度比离线快 10 倍
- **[jadore801120/attention-is-all-you-need-pytorch](https://github.com/jadore801120/attention-is-all-you-need-pytorch)** ⭐ 9,288 - "Attention is All You Need" 中 Transformer 模型的 PyTorch 实现
- **[oceanbase/oceanbase](https://github.com/oceanbase/oceanbase)** ⭐ 9,270 - 适用于事务、分析和 AI 工作负载的最快分布式数据库
- **[Netflix/metaflow](https://github.com/Netflix/metaflow)** ⭐ 8,973 - 构建、管理和部署 AI/ML 系统
- **[vahidk/EffectiveTensorflow](https://github.com/vahidk/EffectiveTensorflow)** ⭐ 8,610 - TensorFlow 教程和最佳实践
- **[openvinotoolkit/openvino](https://github.com/openvinotoolkit/openvino)** ⭐ 8,582 - OpenVINO™ 是用于优化和部署 AI 推理的开源工具包
- **[postgresml/postgresml](https://github.com/postgresml/postgresml)** ⭐ 6,391 - 带有 GPU 的 Postgres，用于 ML/AI 应用
- **[lyogavin/airllm](https://github.com/lyogavin/airllm)** ⭐ 5,850 - AirLLM 70B 推理，单个 4GB GPU
- **[mishushakov/llm-scraper](https://github.com/mishushakov/llm-scraper)** ⭐ 5,312 - 使用大语言模型将任何网页转换为结构化数据
- **[argilla-io/argilla](https://github.com/argilla-io/argilla)** ⭐ 4,581 - Argilla 是 AI 工程师和领域专家构建高质量数据集的协作工具
- **[objectbox/objectbox-java](https://github.com/objectbox/objectbox-java)** ⭐ 4,525 - Android 和 JVM 数据库 - 首个快速、轻量级设备端向量数据库
- **[crate/crate](https://github.com/crate/crate)** ⭐ 4,265 - CrateDB 是一个分布式和可扩展的 SQL 数据库，用于近实时存储和分析大量数据
- **[neo4j-labs/llm-graph-builder](https://github.com/neo4j-labs/llm-graph-builder)** ⭐ 3,709 - 使用大语言模型从非结构化数据构建 Neo4j 图
- **[cozodb/cozo](https://github.com/cozodb/cozo)** ⭐ 3,667 - 使用 Datalog 查询的事务型关系图向量数据库。AI 的海马体！
- **[SciSharp/TensorFlow.NET](https://github.com/SciSharp/TensorFlow.NET)** ⭐ 3,360 - Google TensorFlow 的 .NET Standard 绑定，用于在 C# 和 F# 中开发、训练和部署机器学习模型
- **[filipecalegario/awesome-generative-ai](https://github.com/filipecalegario/awesome-generative-ai)** ⭐ 2,956 - 生成式 AI 工具、作品、模型和参考资料的精选列表
- **[pinecone-io/examples](https://github.com/pinecone-io/examples)** ⭐ 2,916 - 帮助您实际操作 Pinecone 向量数据库的 Jupyter 笔记本
- **[bighuang624/AI-research-tools](https://github.com/bighuang624/AI-research-tools)** ⭐ 2,705 - 🔨 AI 方向好用的科研工具
- **[tensorchord/pgvecto.rs](https://github.com/tensorchord/pgvecto.rs)** ⭐ 2,080 - Postgres 中可扩展、低延迟和混合启用的向量搜索。革命性的向量搜索，而非数据库
- **[zilliztech/attu](https://github.com/zilliztech/attu)** ⭐ 2,061 - Milvus 向量数据库的 Web UI
- **[Mintplex-Labs/vector-admin](https://github.com/Mintplex-Labs/vector-admin)** ⭐ 1,965 - 向量数据库管理的通用工具套件。管理 Pinecone、Chroma、Qdrant、Weaviate 等
- **[dingodb/dingo](https://github.com/dingodb/dingo)** ⭐ 1,600 - 支持使用统一 SQL（MySQL 兼容）对结构化和非结构化数据进行向量查询的多模态向量数据库
- **[juji-io/datalevin](https://github.com/juji-io/datalevin)** ⭐ 1,277 - 简单、快速且多功能的 Datalog 数据库

## 视频与动画

_用于视频创作、编辑和动画的 AI 应用程序。_

- **[hacksider/Deep-Live-Cam](https://github.com/hacksider/Deep-Live-Cam)** ⭐ 71,787 - 实时面部交换和仅使用单张图像的一键视频深度伪造
- **[Developer-Y/cs-video-courses](https://github.com/Developer-Y/cs-video-courses)** ⭐ 69,381 - 带有视频讲座的计算机科学课程列表
- **[deepfakes/faceswap](https://github.com/deepfakes/faceswap)** ⭐ 54,256 - 面向所有人的 Deepfake 软件
- **[xinntao/Real-ESRGAN](https://github.com/xinntao/Real-ESRGAN)** ⭐ 31,719 - Real-ESRGAN 旨在开发用于通用图像/视频修复的实用算法
- **[google-ai-edge/mediapipe](https://github.com/google-ai-edge/mediapipe)** ⭐ 30,651 - 跨平台的实时流媒体的可定制 ML 解决方案
- **[huggingface/diffusers](https://github.com/huggingface/diffusers)** ⭐ 29,800 - 🤗 Diffusers：PyTorch 和 FLAX 中的最先进扩散模型，用于图像、视频和音频生成
- **[wandb/openui](https://github.com/wandb/openui)** ⭐ 21,591 - OpenUI 让您用想象力描述 UI，然后看到它实时渲染
- **[serengil/deepface](https://github.com/serengil/deepface)** ⭐ 19,697 - 用于 Python 的轻量级人脸识别和面部属性分析（年龄、性别、情感和种族）库
- **[graphdeco-inria/gaussian-splatting](https://github.com/graphdeco-inria/gaussian-splatting)** ⭐ 17,765 - "用于实时辐射场渲染的 3D 高斯散射" 的原始参考实现
- **[dair-ai/ML-YouTube-Courses](https://github.com/dair-ai/ML-YouTube-Courses)** ⭐ 16,714 - 📺 发现 YouTube 上最新的机器学习 / AI 课程
- **[k4yt3x/video2x](https://github.com/k4yt3x/video2x)** ⭐ 13,938 - 基于机器学习的视频超分辨率和帧插值框架
- **[owainlewis/awesome-artificial-intelligence](https://github.com/owainlewis/awesome-artificial-intelligence)** ⭐ 12,071 - 人工智能（AI）课程、书籍、视频讲座和论文的精选列表
- **[Hvass-Labs/TensorFlow-Tutorials](https://github.com/Hvass-Labs/TensorFlow-Tutorials)** ⭐ 9,279 - 带有 YouTube 视频的 TensorFlow 教程
- **[activeloopai/deeplake](https://github.com/activeloopai/deeplake)** ⭐ 8,723 - AI 数据库。存储向量、图像、文本、视频等。与大语言模型/LangChain 一起使用
- **[open-mmlab/mmagic](https://github.com/open-mmlab/mmagic)** ⭐ 7,205 - OpenMMLab 多模态高级、生成和智能创作工具箱。解锁魔法 🪄：生成式 AI（AIGC）
- **[enricoros/big-AGI](https://github.com/enricoros/big-AGI)** ⭐ 6,538 - 由最先进模型驱动的 AI 套件，提供高级 AI/AGI 功能
- **[vladmandic/sdnext](https://github.com/vladmandic/sdnext)** ⭐ 6,453 - SD.Next：AI 生成图像和视频创作的一体化 WebUI
- **[MODSetter/SurfSense](https://github.com/MODSetter/SurfSense)** ⭐ 5,981 - NotebookLM / Perplexity / Glean 的开源替代品，连接到搜索引擎等外部源
- **[nateraw/stable-diffusion-videos](https://github.com/nateraw/stable-diffusion-videos)** ⭐ 4,611 - 通过探索潜在空间和在文本提示之间变形，使用 Stable Diffusion 创建 🔥 视频
- **[Picsart-AI-Research/Text2Video-Zero](https://github.com/Picsart-AI-Research/Text2Video-Zero)** ⭐ 4,197 - [ICCV 2023 Oral] 文本到图像扩散模型是零样本视频生成器
- **[OpenGVLab/Ask-Anything](https://github.com/OpenGVLab/Ask-Anything)** ⭐ 3,268 - [CVPR2024 Highlight][VideoChatGPT] 具有视频理解的 ChatGPT！
- **[crmne/ruby_llm](https://github.com/crmne/ruby_llm)** ⭐ 2,556 - 停止玩弄 AI SDK！RubyLLM 为 OpenAI、Anthropic、Gemini、Bedrock、OpenRouter 提供一个令人愉快的 Ruby 接口
- **[cirosantilli/china-dictatorship](https://github.com/cirosantilli/china-dictatorship)** ⭐ 2,468 - 反中共政治宣传库
- **[6174/comflowyspace](https://github.com/6174/comflowyspace)** ⭐ 2,297 - Comflowyspace 是一个直观、用户友好的开源 AI 工具，用于生成图像和视频
- **[milvus-io/bootcamp](https://github.com/milvus-io/bootcamp)** ⭐ 2,178 - 处理所有非结构化数据，如反向图像搜索、音频搜索、分子搜索、视频分析、问答系统等
- **[CiaraStrawberry/TemporalKit](https://github.com/CiaraStrawberry/TemporalKit)** ⭐ 1,961 - 通过 automatic1111 扩展为 Stable Diffusion 渲染添加时间稳定性的一体化解决方案
- **[kyechan99/capsule-render](https://github.com/kyechan99/capsule-render)** ⭐ 1,470 - 🌈 动态彩色图像渲染
- **[universome/stylegan-v](https://github.com/universome/stylegan-v)** ⭐ 378 - [CVPR 2022] StyleGAN-V：具有 StyleGAN2 价格、图像质量和优势的连续视频生成器

## 语音生成与转换

_用于语音克隆、合成和转换的高级 AI 系统。_

- **[babysor/MockingBird](https://github.com/babysor/MockingBird)** ⭐ 36,452 - 🚀AI 拟声: 5 秒内克隆您的声音并生成任意语音内容
- **[mudler/LocalAI](https://github.com/mudler/LocalAI)** ⭐ 33,881 - 🤖 OpenAI、Claude 等的免费开源替代品。自托管和本地优先
- **[FunAudioLLM/CosyVoice](https://github.com/FunAudioLLM/CosyVoice)** ⭐ 15,194 - 多语言大型语音生成模型，提供推理、训练和部署的全栈能力
- **[FurkanGozukara/Stable-Diffusion](https://github.com/FurkanGozukara/Stable-Diffusion)** ⭐ 2,479 - FLUX、Stable Diffusion、SDXL、SD3、LoRA、微调、DreamBooth、训练、Automatic1111、Forge WebUI、SwarmUI、深度伪造、AI 生成图像

## 写作与编辑

_用于内容创作、文本生成和语言处理的 AI 驱动工具。_

- **[xtekky/gpt4free](https://github.com/xtekky/gpt4free)** ⭐ 64,645 - 官方 gpt4free 存储库 | 各种强大语言模型的集合 | o4、o3 和 deepseek r1、gpt-4.1
- **[dair-ai/Prompt-Engineering-Guide](https://github.com/dair-ai/Prompt-Engineering-Guide)** ⭐ 59,501 - 🐙 提示工程的指南、论文、讲座、笔记本和资源
- **[mlabonne/llm-course](https://github.com/mlabonne/llm-course)** ⭐ 57,429 - 进入大型语言模型（LLMs）的课程，包含路线图和 Colab 笔记本
- **[exacity/deeplearningbook-chinese](https://github.com/exacity/deeplearningbook-chinese)** ⭐ 36,576 - 深度学习书籍中文翻译
- **[hankcs/HanLP](https://github.com/hankcs/HanLP)** ⭐ 35,374 - 中文分词 词性标注 命名实体识别 依存句法分析 成分句法分析 语义依存分析 语义角色标注 指代消解 风格转换 语义相似度 新词发现 关键词短语提取 自动摘要 文本分类聚类 拼音简繁转换 自然语言处理
- **[eugeneyan/applied-ml](https://github.com/eugeneyan/applied-ml)** ⭐ 28,116 - 📚 公司分享在生产中进行数据科学和机器学习工作的论文和技术博客
- **[JaidedAI/EasyOCR](https://github.com/JaidedAI/EasyOCR)** ⭐ 27,279 - 支持 80+ 语言和所有流行书写脚本的即用型 OCR
- **[pytorch/examples](https://github.com/pytorch/examples)** ⭐ 23,224 - PyTorch 在视觉、文本、强化学习等方面的示例集合
- **[jingyaogong/minimind](https://github.com/jingyaogong/minimind)** ⭐ 23,109 - 🚀🚀 「大模型」2 小时完全从 0 训练 26M 的小参数 GPT！
- **[karpathy/minGPT](https://github.com/karpathy/minGPT)** ⭐ 22,269 - OpenAI GPT（生成预训练变换器）训练的最小 PyTorch 重新实现
- **[keon/awesome-nlp](https://github.com/keon/awesome-nlp)** ⭐ 17,340 - 📖 专门用于自然语言处理（NLP）的资源精选列表
- **[NLP-LOVE/ML-NLP](https://github.com/NLP-LOVE/ML-NLP)** ⭐ 16,948 - 此项目是机器学习、深度学习、NLP 面试中常考到的知识点和代码实现
- **[AI4Finance-Foundation/FinGPT](https://github.com/AI4Finance-Foundation/FinGPT)** ⭐ 16,653 - FinGPT：开源金融大型语言模型！革命性 🔥
- **[oxford-cs-deepnlp-2017/lectures](https://github.com/oxford-cs-deepnlp-2017/lectures)** ⭐ 15,848 - 牛津深度 NLP 2017 课程
- **[graykode/nlp-tutorial](https://github.com/graykode/nlp-tutorial)** ⭐ 14,668 - 深度学习研究人员的自然语言处理教程
- **[donnemartin/awesome-aws](https://github.com/donnemartin/awesome-aws)** ⭐ 13,607 - 精选的 Amazon Web Services（AWS）库、开源存储库、指南、博客和其他资源列表
- **[Lightning-AI/litgpt](https://github.com/Lightning-AI/litgpt)** ⭐ 12,494 - 20+ 高性能大语言模型，包含预训练、微调和大规模部署的配方
- **[karpathy/char-rnn](https://github.com/karpathy/char-rnn)** ⭐ 11,810 - Torch 中用于字符级语言模型的多层递归神经网络（LSTM、GRU、RNN）
- **[TheR1D/shell_gpt](https://github.com/TheR1D/shell_gpt)** ⭐ 11,115 - 由 GPT-4 等 AI 大语言模型驱动的命令行生产力工具
- **[google/sentencepiece](https://github.com/google/sentencepiece)** ⭐ 11,088 - 基于神经网络的文本生成的无监督文本分词器
- **[databrickslabs/dolly](https://github.com/databrickslabs/dolly)** ⭐ 10,807 - Databricks 的 Dolly，在 Databricks 机器学习平台上训练的大型语言模型
- **[fastai/numerical-linear-algebra](https://github.com/fastai/numerical-linear-algebra)** ⭐ 10,540 - fast.ai 计算线性代数课程的免费在线 Jupyter 笔记本教科书
- **[huggingface/text-generation-inference](https://github.com/huggingface/text-generation-inference)** ⭐ 10,328 - 大型语言模型文本生成推理
- **[yandexdataschool/nlp_course](https://github.com/yandexdataschool/nlp_course)** ⭐ 10,178 - YSDA 自然语言处理课程
- **[stanfordnlp/CoreNLP](https://github.com/stanfordnlp/CoreNLP)** ⭐ 9,934 - CoreNLP：用于分词、句子分割、命名实体识别、解析、共指、情感分析等的 Java 核心 NLP 工具套件
- **[brightmart/nlp_chinese_corpus](https://github.com/brightmart/nlp_chinese_corpus)** ⭐ 9,744 - 大规模中文自然语言处理语料
- **[NirantK/awesome-project-ideas](https://github.com/NirantK/awesome-project-ideas)** ⭐ 8,420 - 机器学习、NLP、视觉、推荐系统项目想法的精选列表
- **[friuns2/BlackFriday-GPTs-Prompts](https://github.com/friuns2/BlackFriday-GPTs-Prompts)** ⭐ 8,260 - 不需要 plus 订阅的免费 GPT 列表
- **[civitai/civitai](https://github.com/civitai/civitai)** ⭐ 6,728 - 模型、文本反转等的存储库
- **[RediSearch/RediSearch](https://github.com/RediSearch/RediSearch)** ⭐ 5,876 - Redis 的查询和索引引擎，提供二级索引、全文搜索、向量相似性搜索和聚合引擎
- **[trigaten/Learn_Prompting](https://github.com/trigaten/Learn_Prompting)** ⭐ 4,523 - Learn Prompting 的提示工程、生成式 AI 和大语言模型指南
- **[infiniflow/infinity](https://github.com/infiniflow/infinity)** ⭐ 3,894 - 为大语言模型应用构建的 AI 原生数据库，提供令人难以置信的快速混合搜索
- **[GanymedeNil/document.ai](https://github.com/GanymedeNil/document.ai)** ⭐ 3,679 - 基于向量数据库与 GPT3.5 的通用本地知识库方案
- **[phodal/prompt-patterns](https://github.com/phodal/prompt-patterns)** ⭐ 3,078 - Prompt 编写模式：如何将思维框架赋予机器，以设计模式的形式来思考 prompt
- **[kuzudb/kuzu](https://github.com/kuzudb/kuzu)** ⭐ 2,825 - 为速度而构建的嵌入式属性图数据库。内置向量搜索和全文搜索。实现 Cypher
- **[peremartra/Large-Language-Model-Notebooks-Course](https://github.com/peremartra/Large-Language-Model-Notebooks-Course)** ⭐ 1,649 - 关于大型语言模型的实用课程
- **[jackaduma/Recurrent-LLM](https://github.com/jackaduma/Recurrent-LLM)** ⭐ 193 - 论文的开源大语言模型实现：RecurrentGPT：（任意）长文本的交互式生成。AI 写小说

## 项目统计

_来自我们 AI 工具发现和分类系统的真实数据。_

### 收录概览

- **📊 项目总数**：737 个开源 AI 工具
- **🔍 数据来源**：通过自动分类爬取的 GitHub 存储库
- **📅 最后更新**：2025 年 1 月
- **🌟 质量筛选**：最低 50 星标要求

### 分类分布

| 分类                     | 项目数 | 百分比 |
| ------------------------ | ------ | ------ |
| **图像生成与编辑**       | 214    | 29.0%  |
| **聊天机器人与虚拟助手** | 149    | 20.2%  |
| **研究与数据分析**       | 112    | 15.2%  |
| **编程与开发**           | 106    | 14.4%  |
| **视频与动画**           | 38     | 5.2%   |
| **写作与编辑**           | 37     | 5.0%   |
| **其他 AI 工具**         | 32     | 4.3%   |
| **音乐与音频**           | 18     | 2.4%   |
| **游戏与娱乐**           | 6      | 0.8%   |
| **教育与翻译**           | 6      | 0.8%   |
| **商业管理**             | 6      | 0.8%   |
| **营销与广告**           | 5      | 0.7%   |
| **语音生成与转换**       | 4      | 0.5%   |
| **开发者工具与基础设施** | 4      | 0.5%   |

### 质量指标

- **高影响力（10,000+ ⭐）**：具有大规模社区采用的顶级项目
- **流行（1,000-9,999 ⭐）**：具有强大社区的成熟项目
- **成长中（100-999 ⭐）**：显示潜力的新兴项目
- **新项目（50-99 ⭐）**：达到我们最低门槛的新鲜项目

## 贡献指南

欢迎贡献！请先阅读[贡献指南](CONTRIBUTING.md)。

### 收录标准：

- ✅ **开源**：必须有公开可用的源代码
- ✅ **AI/ML 焦点**：具有明确的人工智能或机器学习功能
- ✅ **活跃开发**：定期提交和维护（12 个月内更新）
- ✅ **质量门槛**：最少 50 个 GitHub 星标或经过验证的社区采用
- ✅ **功能性**：工作实现，而不仅仅是概念或废弃项目
- ✅ **文档完善**：清晰的 README 和使用说明

### 如何贡献：

1. Fork 此存储库
2. 遵循格式：`**[工具名称](链接)** ⭐ 星数 - 简要描述`
3. 确保工具符合我们的收录标准
4. 提交带有清晰描述的拉取请求

### 自动化更新

此列表通过自动爬取 GitHub 存储库进行维护。我们的系统：

- 🔍 **发现** 通过基于关键词的搜索发现新的 AI 工具
- 📊 **分析** 项目质量指标（星标、分叉、活跃度）
- ✅ **验证** 相关性和功能性
- 📈 **更新** 定期更新统计数据和排名

## 社区交流

欢迎加入我们的 AI 工具交流群，与同行分享经验、讨论最新 AI 技术！

<div align="center">
  <img src="1752668627893.jpg" alt="微信交流群二维码" width="200">
  <p>扫码加入AI工具交流群</p>
</div>

## 许可证

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

此作品根据 [Creative Commons Zero v1.0 Universal](https://creativecommons.org/publicdomain/zero/1.0/) 许可证授权。
