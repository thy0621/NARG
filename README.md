# NARG
NRAG: A Knowledge Graph-Enhanced Large Language Model Approach for Neurosurgical Disease Diagnosis

神外医学诊断大模型项目（NRAG）拟通过大模型方式实现神经外科领域疾病诊断及知识问答等任务，推动神外领域知识问答、临床辅助诊疗等领域的快速发展。

目前针对神经外科领域的疾病诊断任务，发布了神外疾病诊断指令微调大模型NRAG。



## 更新日志
[2025/07] 论文投稿中

[2025/06] 面向神经外科领域的疾病诊断的大模型NRAG

[2024/09] 项目启动

## A Quick Start
1. 首先需要下载ChatGLM3-6B原始模型代码和参数，并配置依赖环境（ChatGLM3-6B: [https://github.com/THUDM/ChatGLM3](https://github.com/THUDM/ChatGLM3) ）。
2. 下载 NRAG 模型参数，将checkpoint压缩文件解压到 ChatGLM3-6B/ptuning/ 路径下。
3. 参考ChatGLM3-6B项目，调用制定checkpoint路径下的训练参数，激活模型。
   
夸克网盘链接: https://pan.quark.cn/s/2b9f55fbf46c    提取码：GzTe

## 致谢
本项目参考了以下开源项目，在此对相关项目和研究开发人员表示感谢。
- ChatGLM-6B: https://github.com/THUDM/ChatGLM-6B
- Chinese-LLaMA-Alpaca: https://github.com/ymcui/Chinese-LLaMA-Alpaca
- Stanford Alpaca: https://github.com/tatsu-lab/stanford_alpaca
- Huatuo: https://github.com/SCIR-HI/Huatuo-Llama-Med-Chinese

  
## 免责声明

本项目相关资源仅供学术研究之用，严禁用于商业用途。使用涉及第三方代码的部分时，请严格遵循相应的开源协议。模型生成的内容受模型计算、随机性和量化精度损失等因素影响，本项目无法对其准确性作出保证。本项目数据集绝大部分由模型生成，即使符合某些医学事实，也不能被用作实际医学诊断的依据。对于模型输出的任何内容，本项目不承担任何法律责任，亦不对因使用相关资源和输出结果而可能产生的任何损失承担责任。
