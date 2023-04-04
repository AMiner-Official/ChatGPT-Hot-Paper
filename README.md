# 3月“ChatGPT”相关热门论文-AMiner
过去的整个三月，可以说是“GPT"的三月，不管是学术圈、工业界人士、媒体、投资者、创业者们都在讨论“GPT”。国外主要是围绕着谷歌、Meta和OpenAI之间的竞争话题，国内则纷纷在讨论谁将会第一个打造中国版“ChatGPT”。
### 以下是3月份“ChatGPT"相关的热门论文！(以下综述内容皆有AMiner基于大模型生成，对话可直接点击论文链接）
#### A Survey of Large Language Models
Wayne Xin Zhao,Kun Zhou,Junyi Li,Tianyi Tang,Xiaolei Wang,Yupeng Hou,Yingqian Min,Beichen Zhang,Junjie Zhang,Zican Dong,Yifan Du,Chen Yang,Yushuo Chen,Zhipeng Chen,Jinhao Jiang,Ruiyang Ren,Yifan Li,Xinyu Tang,Zikang Liu,Peiyu Liu,Jian-Yun Nie,Ji-Rong Wen
这篇文章是关于大型语言模型（LLMs）的综述。LLMs是由大规模语料库预训练的Transformer模型，具有强大的自然语言处理能力。研究人员发现，模型规模的增加可以提高模型性能，当模型参数规模超过一定程度时，LLMs不仅能够显著提高性能，还具有一些小型模型所不具备的特殊能力。文章介绍了LLMs的背景、主要技术和研究进展，特别关注LLMs的预训练、调整、利用和容量评估等四个方面，并对开发LLMs的可用资源和未来研究方向进行了总结。
论文链接：[https://www.aminer.cn/pub/642a43bc90e50fcafd9b1555](https://www.aminer.cn/pub/642a43bc90e50fcafd9b1555?f=g)

#### DERA: Enhancing Large Language Model Completions with Dialog-Enabled Resolving Agents
Varun Nair,Elliot Schumacher,Geoffrey Tso,Anitha Kannan
这篇文章介绍了一种名为DERA的对话式解决方案，可使用大型语言模型GPT-4来进行临床任务，如医疗会话摘要和护理计划生成，并在人类专家参与的偏好评估和数量指标中显示出明显的性能改善。并且作者还发现，在MedQA问答数据集的开放式版本中，GPT-4的表现良好，DERA的性能也相似。文章的目的是增强大型语言模型的完成能力，并提高生成的结果的准确性和完整性。
论文链接：[https://www.aminer.cn/pub/64264f7a90e50fcafd68d7ac](https://www.aminer.cn/pub/64264f7a90e50fcafd68d7ac?f=g)

#### Scaling Down to Scale Up: A Guide to Parameter-Efficient Fine-Tuning
Vladislav Lialin,Vijeta Deshpande,Anna Rumshisky
这篇论文提出了一种解决大型语言模型微调的不可行性和不切实际性的方法，即仅训练一小部分参数的参数有效微调方法，并对超过40篇相关论文进行了系统概述和比较。文章介绍了广泛的方法分类，并着重探讨了现实效率和微调数十亿规模的语言模型。
论文链接：[https://www.aminer.cn/pub/6423ac7790e50fcafd55eaa0](https://www.aminer.cn/pub/6423ac7790e50fcafd55eaa0?f=g)

#### Language Models can Solve Computer Tasks
Geunwoo Kim,Pierre Baldi,Stephen McAleer
这篇文章说明了一种名为“递归批判改进”（RCI）的新方法可以使用自然语言命令指导预训练的大型语言模型代理执行计算机任务，并在MiniWoB++基准测试中明显优于现有的LLM方法。RCI方法只需要每项任务的数十个示范，而不需要大量的专家演示和任务特定的奖励函数，并且在增强学习和监督学习方法上都表现出色，并可用于提高LLMs的推理能力。
论文链接：[https://www.aminer.cn/pub/64264f7b90e50fcafd68dfd1](https://www.aminer.cn/pub/64264f7b90e50fcafd68dfd1?f=g)

#### HuggingGPT: Solving AI Tasks with ChatGPT and its Friends in HuggingFace
Yongliang Shen,Kaitao Song,Xu Tan,Dongsheng Li,Weiming Lu,Yueting Zhuang
文章介绍了如何利用大型语言模型（LLMs）来管理和整合已有的AI模型，从而解决复杂的AI任务。文章提出了HuggingGPT系统，该系统利用ChatGPT作为控制器，连接不同的AI模型来解决不同领域和模态的AI任务。HuggingGPT系统利用ChatGPT的强大语言能力和HuggingFace中丰富的AI模型，能够处理不同模态和领域的复杂AI任务，并在语言理解、生成、交互、推理以及视觉、语音等多个方面取得了卓越的成果。文章的关注点在于如何利用语言模型作为整合AI模型的接口，以达到更高层次的人工智能水平。
论文链接：[https://www.aminer.cn/pub/64264f7b90e50fcafd68e162](https://www.aminer.cn/pub/64264f7b90e50fcafd68e162?f=g)

#### Training Language Models with Language Feedback at Scale
Jérémy Scheurer,Jon Ander Campos,Tomasz Korbak,Jun Shern Chan,Angelica Chen,Kyunghyun Cho,Ethan Perez
本文介绍了基于语言反馈的语言模型训练方法ILF，旨在解决预训练语言模型生成与人类偏好不符的输出问题。ILF利用更具信息量的语言反馈，包含三个迭代步骤：首先，在输入、初始输出和反馈的基础上，条件化语言模型生成细化。其次，选择其中包含最多反馈意见的细化。第三，微调语言模型以最大化考虑输入时所选择的细化的可能性。实验证明，ILF的有效性在一个有控制的小规模任务和一个现实的摘要任务上都得到了验证，同时学习语言反馈和比较反馈的方法显著优于各自独立使用的方法，达到了人类级别的摘要表现。
论文链接：[https://www.aminer.cn/pub/6424fe3490e50fcafd78b7ee](https://www.aminer.cn/pub/6424fe3490e50fcafd78b7ee?f=g)

#### Language Models Trained on Media Diets Can Predict Public Opinion
Eric Chu,Jacob Andreas,Stephen Ansolabehere,Deb Roy
这篇文章介绍了一种新的方法来预测公众舆论，即通过训练语言模型来模拟特定群体对媒体内容的反应。研究表明，这种方法可以提高预测精度，有助于补充调查和预测公众舆论，并提示需要进一步研究神经语言模型预测人类反应的准确性。
论文链接：[https://www.aminer.cn/pub/6424fe3490e50fcafd78b853](https://www.aminer.cn/pub/6424fe3490e50fcafd78b853?f=g)

#### TaskMatrix.AI: Completing Tasks by Connecting Foundation Models with Millions of APIs
Yaobo Liang,Chenfei Wu,Ting Song,Wenshan Wu,Yan Xia,Yu Liu,Yang Ou,Shuai Lu,Lei Ji,Shaoguang Mao,Yun Wang,Linjun Shou,Ming Gong,Nan Duan
该文章中主要阐述了目前人工智能在解决一般任务上的进展和基于特定领域数据的任务上的瓶颈，介绍了一个新的人工智能生态系统TaskMatrix.AI，旨在连接基础模型和数百万API，以完成从数字到物理领域的各种不同任务。文章还阐述了该生态系统的组成部分和实现该愿景的主要挑战。
论文链接：[https://www.aminer.cn/pub/6424fe3390e50fcafd78b51d](https://www.aminer.cn/pub/6424fe3390e50fcafd78b51d?f=g)

#### BloombergGPT: A Large Language Model for Finance
Shijie Wu,Ozan Irsoy,Steven Lu,Vadim Dabravolski,Mark Dredze,Sebastian Gehrmann,Prabhanjan Kambadur,David Rosenberg,Gideon Mann
本文介绍了一种专门针对金融领域的大型语言模型，BloombergGPT，该模型使用了广泛的金融数据进行训练，并在标准的大型语言模型基准测试、金融基准测试以及内部基准测试中取得了较好的表现。同时，文章还介绍了该模型的建模选择、训练过程和评估方法，并计划发布训练日志以进一步分享经验。文章表明，在金融科技领域中使用自然语言处理技术是广泛而复杂的，并且仍然存在挑战。
论文链接：[https://www.aminer.cn/pub/64267642158fc30f5977f354](https://www.aminer.cn/pub/64267642158fc30f5977f354?f=g)

#### Bilex Rx: Lexical Data Augmentation for Massively Multilingual Machine Translation
Alex Jones,Isaac Caswell,Ishank Saxena,Orhan Firat
这篇文章探讨了神经机器翻译在使用单语文本数据进行无监督翻译时，仍然存在诸多问题，尤其是在翻译常见名词方面。为解决这个问题，文章提出了一种廉价且充足的资源——双语词典来进行数据增强，从而提高翻译质量。文章通过实际测试表明，使用词典数据增强可以显著提高无监督翻译的性能，不同数据增强方法也可以相互结合以实现更好的效果，同时，精心筛选的词典的效果甚至优于大而杂乱的词典。最后，作者开源了一个针对26种低资源语言的多语言词典GATITOS，并证明它在实验中表现最佳。
论文链接：[https://www.aminer.cn/pub/64225b7e90e50fcafde15035](https://www.aminer.cn/pub/64225b7e90e50fcafde15035?f=g)

#### Exposing and Addressing Cross-Task Inconsistency in Unified Vision-Language Models
Adyasha Maharana,Amita Kamath,Christopher Clark,Mohit Bansal,Aniruddha Kembhavi
这篇文章讨论了统一视觉和语言模型在不同任务之间的一致性问题，并提出了一个基准数据集（COCOCON）和度量方法来评估模型的一致性。研究发现，现有的模型在更异质的任务中表现出更高的不一致性。最后，文章提出了使用基于排名相关性的辅助目标来提高多任务一致性的方法，并保持模型在下游任务上的原始准确度。
论文链接：[https://www.aminer.cn/pub/6423ac7890e50fcafd55f0fc](https://www.aminer.cn/pub/6423ac7890e50fcafd55f0fc?f=g)

#### Exploring the Impact of Instruction Data Scaling on Large Language Models: An Empirical Study on Real-World Use Cases
Yunjie Ji,Yong Deng,Yan Gong,Yiping Peng,Qiang Niu,Lei Zhang,Baochang Ma,Xiangang Li
本文研究了大型语言模型在不同量级的指令数据下的性能表现。实验构建了一个由12个主要在线使用案例组成的评估数据集，并使用Bloomz-7B1-mt作为基础模型进行了实验。结果表明，仅增加指令数据量就能使开放生成等任务的性能持续提升，但对于数学和代码等任务，则是性能曲线保持相对平稳。研究还分析了这些现象可能的原因，并提出了未来研究方向。该研究还将发布其训练和评估数据集以及模型检查点。
论文链接：[https://www.aminer.cn/pub/6423ac7890e50fcafd55f0fc](https://www.aminer.cn/pub/6423ac7890e50fcafd55f0fc?f=g)

#### LLaMA-Adapter: Efficient Fine-tuning of Language Models with Zero-init Attention
Renrui Zhang,Jiaming Han,Aojun Zhou,Xiangfei Hu,Shilin Yan,Pan Lu,Hongsheng Li,Peng Gao,Yu Qiao
该论文介绍了一种名为LLaMA-Adapter的轻量级适应方法，可以更有效地对LLaMA进行微调，将其转变为一个指令-following模型。使用52000个自我指导演示，LLaMA-Adapter只在冻结的LLaMA 7B模型上引入了1.2M可学习参数，且在8个A100 GPU上微调时间不到一小时。具体而言，该方法采用可学习的适应提示集，将其预置于输入文本令牌的较高变压器层中。然后，提出了一种零初始化注意机制，其中零门控适应地将新的指令提示注入LLaMA，同时有效地保留其预训练的知识。通过高效的训练，LLaMA-Adapter生成了高质量的响应，与全面微调7B参数的Alpaca相当。此外，该方法还可以简单地扩展到多模态输入，例如图像，用于在ScienceQA中实现优越的推理能力。作者已释放了他们的代码。
论文链接：[https://www.aminer.cn/pub/6423ac7890e50fcafd55f26b](https://www.aminer.cn/pub/6423ac7890e50fcafd55f26b?f=g)

#### ChatGPT Outperforms Crowd-Workers for Text-Annotation Tasks
Fabrizio Gilardi,Meysam Alizadeh,Maël Kubli
这篇文章讨论了在自然语言处理中进行手动数据注释的问题及其解决方案。作者使用了一个样本来证明，ChatGPT超过了众包工人在几个注释任务上的表现，包括相关性、态度、主题和框架检测。ChatGPT的零-shot准确率优于众包工人中的四项任务，同时，ChatGPT的编码者间一致性在所有任务中均优于众包工人和专业注释员。此外，ChatGPT的每个注释成本不到0.003美元，是MTurk的大约二十倍便宜。这些结果表明了大型语言模型在文本分类效率方面的潜在作用。
论文链接：[https://www.aminer.cn/pub/64225b7d90e50fcafde14d48](https://www.aminer.cn/pub/64225b7d90e50fcafde14d48?f=g)

#### ChatDoctor: A Medical Chat Model Fine-tuned on LLaMA Model using Medical Domain Knowledge
Yunxiang Li,Zihan Li,Kai Zhang,Ruilong Dan,You Zhang
本文说明了当前通用领域的大型语言模型在医疗领域中无法准确诊断和推荐药物等问题。为了解决这个问题，研究者们通过收集疾病及其症状、推荐药物和必要的医学检查等信息，生成了5K个医生-患者对话，通过对这些对话模型的微调，提高了模型对于患者需求的理解、能够提供有价值的建议，并为各种医疗相关领域提供了有价值的协助。此外，研究者们还开放了数据集、代码和模型权重，以推动医学领域对话模型的进一步发展。
论文链接：[https://www.aminer.cn/pub/6421094d90e50fcafdb0302b](https://www.aminer.cn/pub/6421094d90e50fcafdb0302b?f=g)

#### Scaling Expert Language Models with Unsupervised Domain Discovery
Suchin Gururangan,Margaret Li,Mike Lewis,Weijia Shi,Tim Althoff,Noah A. Smith,Luke Zettlemoyer
本文介绍了一种简单而有效的方法，可以异步训练大规模、稀疏的语言模型，并在推理时将它们组合成一个稀疏集合。这种方法通过自动发现每个专家的域，将全局参数训练转化为本地参数训练，从而减少了通信开销，并在多个文集和少射击任务中胜过密集基准线。同时，文章指出，将专家特定于有意义的集群是实现这些收益的关键。本方法的效率和可访问性随专家数量和训练数据规模的增加而提高，建议这是一种高效的训练大型语言模型的方法。
论文链接：[https://www.aminer.cn/pub/6421094e90e50fcafdb032b5](https://www.aminer.cn/pub/6421094e90e50fcafdb032b5?f=g)

#### Artificial muses: Generative Artificial Intelligence Chatbots Have Risen to Human-Level Creativity
Jennifer Haase,Paul H. P. Hanel
文章说明了通过对比人类生成的创意和六个生成式人工智能聊天机器人生成的创意，发现在创造力的质量上，人工智能和人类没有明显的区别，虽然创意生成的方式有所不同。同时，研究者还发现，9.4%的人类比最有创意的一种人工智能GPT-4更有创意。文章认为生成式人工智能可以成为创意过程中有价值的助手，但我们也需要进一步研究和发展这种技术在创意任务中的潜在利益和缺陷，以及生成式人工智能是否具备真正的创造力。
论文链接：[https://www.aminer.cn/pub/641a71fb90e50fcafd720364](https://www.aminer.cn/pub/641a71fb90e50fcafd720364?f=g)

#### MEGA: Multilingual Evaluation of Generative AI
Kabir Ahuja,Rishav Hada,Millicent Ochieng,Prachi Jain,Harshita Diddee,Samuel Maina,Tanuja Ganu,Sameer Segal,Maxamed Axmed,Kalika Bali,Sunayana Sitaram
文章说明了生成式人工智能模型（generative AI models）在自然语言处理中的表现令人印象深刻，但评估这些模型的能力和限制非常具有挑战性，并且目前针对生成式大型语言模型（LLMs）的研究大多局限于英语，在理解和生成其他语言方面的能力还不清楚，因此需要进行全面评估和比较。作者提出了MEGA评估框架，涵盖了8种不同类型的自然语言处理任务和33种语言，还将生成式LLMs的表现与SOTA非自回归模型进行了比较，提出了未来在多语言环境下进一步提高生成式LLMs表现需要考虑的因素和方向。
论文链接：[https://www.aminer.cn/pub/641bc38c90e50fcafdc14450](https://www.aminer.cn/pub/641bc38c90e50fcafdc14450?f=g)

#### Catalyzing next-generation Artificial Intelligence through NeuroAI.
Anthony Zador,Sean Escola,Blake Richards,Bence Ölveczky,Yoshua Bengio,Kwabena Boahen,Matthew Botvinick,Dmitri Chklovskii,Anne Churchland,Claudia Clopath,James DiCarlo,Surya Ganguli,Jeff Hawkins,Konrad Körding,Alexei Koulakov,Yann LeCun,Timothy Lillicrap,Adam Marblestone,Bruno Olshausen,Alexandre Pouget,Cristina Savin,Terrence Sejnowski,Eero Simoncelli,Sara Solla,David Sussillo,Andreas S Tolias,Doris TsaoLess
这篇文章讨论了如何通过神经科学和人工智能的结合来促进下一代人工智能的发展，并提出了“具身图灵测试”的概念，即让人工智能模型能够与感觉运动世界以类似于它们生物对应物种的水平互动。这个测试的目的是将人工智能研究从那些已经发展得特别好或仅适用于人类的能力转移到那些所有动物都共享的能力上，以此为基础，为下一代的人工智能提供路线图。
论文链接：[https://www.aminer.cn/pub/641d7f7190e50fcafd62cdfb](https://www.aminer.cn/pub/641d7f7190e50fcafd62cdfb?f=g)

#### Can AI-Generated Text be Reliably Detected?
Vinu Sankar Sadasivan,Aounon Kumar,Sriram Balasubramanian,Wenxiao Wang,Soheil Feizi
本文探讨了如何可靠地检测由人工智能生成的文本，因为未受监管的使用可能导致恶意后果。最近的研究尝试通过使用文本输出中存在的特定模型签名或应用水印技术来解决这个问题。然而，本文经过实验和理论分析发现，这些检测器在实际情况下都不可靠，并且即使是最好的检测器也只能略微好于随机分类器。此外，即使使用水印技术保护的大型语言模型也可能容易受到欺骗攻击。这些结果表明，需要对人工智能生成文本的道德和可靠使用进行诚实的讨论。
论文链接：[https://www.aminer.cn/pub/6419209390e50fcafda93008](https://www.aminer.cn/pub/6419209390e50fcafda93008?f=g)

#### PanGu-Σ: Towards Trillion Parameter Language Model with Sparse Heterogeneous Computing
Xiaozhe Ren,Pingyi Zhou,Xinfan Meng,Xinjing Huang,Yadao Wang,Weichao Wang,Pengfei Li,Xiaoda Zhang,Alexander Podolskiy,Grigory Arshinov,Andrey Bout,Irina Piontkovskaya,Jiansheng Wei,Xin Jiang,Teng Su,Qun Liu,Jun Yao
本文介绍了利用Ascend 910 AI处理器和MindSpore框架训练了一个拥有1.085T参数的语言模型PanGu-{\Sigma}的系统，并通过使用随机路由专家(RRE)和专家计算和存储分离(ECSS)等技术，将密集Transformer模型扩展为稀疏模型，从而在异构计算中实现了6.3倍的训练吞吐量增加。实验结果表明，PanGu-{\Sigma}在零样本学习各种中文NLP下游任务方面显示了最先进的性能，同时在开放领域对话、问答、机器翻译和代码生成的应用数据上表现出了强大的能力。
论文链接：[https://www.aminer.cn/pub/6419208e90e50fcafda927c5](https://www.aminer.cn/pub/6419208e90e50fcafda927c5?f=g)

#### Sparks of Artificial General Intelligence: Early experiments with GPT-4
Sébastien Bubeck,Varun Chandrasekaran,Ronen Eldan,Johannes Gehrke,Eric Horvitz,Ece Kamar,Peter Lee,Yin Tat Lee,Yuanzhi Li,Scott Lundberg,Harsha Nori,Hamid Palangi,Marco Tulio Ribeiro,Yi Zhang
本文主要介绍了人工智能领域最新的语言模型 GPT-4，揭示了其能够解决跨领域的新颖难题，且性能接近甚至超过人类水平。作者认为，GPT-4 可能是一个早期的人工通用智能 (AGI) 系统，但仍存在许多挑战和限制，需要进一步深入研究。同时，本文也探讨了这种新技术对社会的影响和未来的研究方向。
论文链接：[https://www.aminer.cn/pub/64264f7a90e50fcafd68d7ac](https://www.aminer.cn/pub/64264f7a90e50fcafd68d7ac?f=g)

#### GPTs are GPTs: An Early Look at the Labor Market Impact Potential of Large Language Models
Tyna Eloundou,Sam Manning,Pamela Mishkin,Daniel Rock
该研究调查了生成式预训练变压器（GPT）模型及其相关技术对美国劳动力市场的潜在影响。通过一种新的评估标准，结合人类专业知识和 GPT-4 的分类，评估工作岗位与 GPT 能力的对应情况。研究发现，约 80% 的美国劳动力可能会受到 GPT 引进的影响，他们的工作任务至少有 10% 可能会受到影响，而约 19% 的工人则可能看到至少 50% 的工作任务受到影响。这种影响涵盖了所有工资水平，高收入工作可能面临更大的风险。值得注意的是，影响并不仅限于近期生产率增长较高的行业。研究得出结论：生成式预训练变压器具有通用技术特征（GPTs），表明这些模型可能具有显著的经济、社会和政策影响。
论文链接：[https://www.aminer.cn/pub/6417d04b90e50fcafd8408ef](https://www.aminer.cn/pub/6417d04b90e50fcafd8408ef?f=g)

#### GPT-4 Technical Report
OpenAI
该文章介绍了GPT-4的技术报告，其中提到了该模型可以接受图像和文本输入，并生成文本输出。该模型在某些专业和学术基准测试中展现出了人类水平的表现，包括在模拟的律师考试中得分达到了前10%的水平。该模型是基于Transformer的，预先训练来预测文档中的下一个标记。文章还提到了开发基础架构和优化方法的重要性，以便能够在广泛的规模下实现可预测的行为。同时，该模型的某些性能可以根据使用不到GPT-4计算能力的模型进行准确预测。
论文链接：[https://www.aminer.cn/pub/641130e378d68457a4a2986f](https://www.aminer.cn/pub/641130e378d68457a4a2986f?ff=g)

#### Visual ChatGPT: Talking, Drawing and Editing with Visual Foundation Models
Chenfei Wu,Shengming Yin,Weizhen Qi,Xiaodong Wang,Zecheng Tang,Nan Duan
本文介绍了一个名为Visual ChatGPT的系统，它结合了不同的视觉基础模型，使用户能够通过发送和接收图像，以及提供复杂的视觉问题或视觉编辑指令来与ChatGPT交互。作者指出，虽然ChatGPT在语言方面具有出色的对话能力和推理能力，但它目前无法处理或生成来自视觉世界的图像。因此，他们利用Visual Foundation Models的视觉理解和生成能力，设计了一系列提示，将视觉模型信息注入ChatGPT，实现了多步骤、多输入输出的协作。实验表明，Visual ChatGPT为研究ChatGPT在视觉方面的作用打开了大门。
论文链接：[https://www.aminer.cn/pub/64094eeb90e50fcafd4785ad](https://www.aminer.cn/pub/64094eeb90e50fcafd4785ad?f=g)

#### Foundation Models for Decision Making: Problems, Methods, and Opportunities
Sherry Yang,Ofir Nachum,Yilun Du,Jason Wei,Pieter Abbeel,Dale Schuurmans
本文讨论了基础模型与决策制定之间的关系，并探讨了使用不同方法使基础模型与其他实体和代理进行长期推理的范例。它还介绍了最近的方法，并讨论了该领域的共同挑战和未解决的问题。该文强调了研究基础模型与决策制定的交叉领域的潜力。
论文链接：[https://www.aminer.cn/pub/6407fd3f90e50fcafd2748ac](https://www.aminer.cn/pub/6407fd3f90e50fcafd2748ac?f=g)

#### Prompt, Generate, then Cache: Cascade of Foundation Models makes Strong Few-shot Learners
Renrui Zhang,Xiangfei Hu,Bohao Li,Siyuan Huang,Hanqiu Deng,Hongsheng Li,Yu Qiao,Peng Gao
本文介绍了一个名为CaFo的模型，它将多种预训练模型的先前知识级联起来，以提高few-shot学习的效果。CaFo结合了CLIP的语言对比知识、DINO的视觉对比知识、DALL-E的视觉生成知识和GPT-3的语言生成知识。具体而言，CaFo通过“提示、生成、缓存”来工作。第一步，利用GPT-3生成丰富的下游语义输入来提示CLIP。然后，通过DALL-E生成合成图像来扩展few-shot训练数据。最后，引入一个可学习的缓存模型来自适应地融合CLIP和DINO的预测结果。通过这种协作方式，CaFo可以发挥不同预训练方法的潜力，并将它们统一为few-shot分类的最新技术。
论文链接：[https://www.aminer.cn/pub/640559c790e50fcafddb5392](https://www.aminer.cn/pub/640559c790e50fcafddb5392?f=g)

#### Check Your Facts and Try Again: Improving Large Language Models with External Knowledge and Automated Feedback
Baolin Peng,Michel Galley,Pengcheng He,Hao Cheng,Yujia Xie,Yu Hu,Qiuyuan Huang,Lars Liden,Zhou Yu,Weizhu Chen,Jianfeng Gao
该论文介绍了使用外部知识和自动反馈来改进大型语言模型（LLMs）的方法，以解决LLMs在实际的任务中生成虚幻输出和无法使用外部知识等问题。该研究提出了LLM-Augmenter系统，该系统使用一组可插拔模块来增强黑匣子LLM，使其生成基于外部知识的响应，同时使用实用函数（例如LLM生成响应的事实得分）生成反馈来迭代地修订LLM提示以改善模型响应。该系统在两种关键任务场景中进行了实证验证，即面向任务的对话和开放领域问答，结果表明LLM-Augmenter显著降低了ChatGPT的幻觉，同时保持了其响应的流畅性和信息量。作者公开了源代码和模型。
论文链接：[https://www.aminer.cn/pub/63fc1f5090e50fcafda638cf](https://www.aminer.cn/pub/63fc1f5090e50fcafda638cf?f=g)

#### Language Is Not All You Need: Aligning Perception with Language Models
Shaohan Huang,Li Dong,Wenhui Wang,Yaru Hao,Saksham Singhal,Shuming Ma,Tengchao Lv,Lei Cui,Owais Khan Mohammed,Barun Patra,Qiang Liu,Kriti Aggarwal,Zewen Chi,Johan Bjorck,Vishrav Chaudhary,Subhojit Som,Xia Song,Furu Wei
本文介绍了一个名为Kosmos-1的多模态大型语言模型（MLLM），它可以感知多种模态、在上下文中（即少样本学习）学习和遵循指令（即零样本学习）。作者指出，多模态感知、行动和世界建模的大集成是通向人工通用智能的重要步骤。实验结果表明，Kosmos-1在语言理解、生成，以及感知-语言任务（如对话、图像说明、视觉问答）和视觉任务（如使用文本说明对图像分类）等方面取得了令人印象深刻的成果。作者还介绍了一个诊断MLLM非语言推理能力的Raven IQ测试数据集，试图将语言和多模态之间的知识互相转移。因此，本文的主要问题是多模态大型语言模型的设计和应用。
论文链接：[https://www.aminer.cn/pub/63fd715f90e50fcafd1476d4](https://www.aminer.cn/pub/63fd715f90e50fcafd1476d4?f=g)

#### Larger language models do in-context learning differently
Jerry Wei,Jason Wei,Yi Tay,Dustin Tran,Albert Webson,Yifeng Lu,Xinyun Chen,Hanxiao Liu,Da Huang,Denny Zhou,Tengyu Ma
本文研究了语言模型在上下文学习（ICL）时受语义先验和输入-标签映射的影响。通过在不同模型家族（GPT-3、InstructGPT、Codex、PaLM和Flan-PaLM）中进行ICL实验，发现模型规模对覆盖语义先验的能力具有重要影响。较小的语言模型在ICL中会忽略上下文中的反转标签，主要依赖于预训练的语义先验，而较大的模型可以在收到与先验相矛盾的上下文示例时覆盖语义先验。此外，本文还研究了SUL-ICL，即标签与输入无关的ICL，发现只有足够大的语言模型才能学习输入-标签映射并执行任务。最后，本文还研究了指令调优模型，并发现指令调优可增强使用语义先验和学习输入-标签映射的能力，但以前者更为明显。
论文链接：[https://www.aminer.cn/pub/6407fd3e90e50fcafd274681](https://www.aminer.cn/pub/6407fd3e90e50fcafd274681?f=g)
