# ChatGPT 从 0 到 1 系统性学习资料汇总

# 1. 基础概念

## 1.1. ChatGPT

ChatGPT 是由 OpenAI 开发的尖端对话人工智能产品，基于 GPT 系列语言模型设计，旨在生成类似人类的自然语言应答。ChatGPT 因其生成连贯、上下文相关的应答能力而备受欢迎。

![Untitled](ChatGPT%20%E4%BB%8E%200%20%E5%88%B0%201%20%E7%B3%BB%E7%BB%9F%E6%80%A7%E5%AD%A6%E4%B9%A0%E8%B5%84%E6%96%99%E6%B1%87%E6%80%BB%20cbb8bd97914a49c896501fb3aae5de51/Untitled.png)

ChatGPT 建立在多项底层技术之上，包括自然语言处理、循环神经网络、Transformer、Bert 和 GPT。它还使用了一种独特的训练方法，称为 RHLF，即“基于排练、事后体验回放和可遗忘记忆的终身学习”。这种训练方法可以让模型从错误中学习，不断改进。

其最核心的底层语言模型叫做 Generative Pre-trained Transformer，简称 GPT，该系列语言模型最初由 OpenAI 在2018年推出。自那时以来，该公司一直在对模型进行改进，目前历经 1、2、3、4 代，也被称为 GPT1、GPT2 等，而 GPT3.5 可以理解是 OpenAI 为了推出 ChatGPT，在 2022 年 1 月推出的 GPT3 的优化版。

而 ChatGPT 是基于 GPT 系列模型所创建的产品，目前官网的对话机器人 ChatGPT 可以使用 3.5 版本和 4 版本的 GPT 模型。

<aside>
👨🏻‍💻 相关阅读与来源 1

</aside>

- ChatGPT已经席卷全球，这其中有一些原因：
    - 它拥有1,750亿个参数，成为最大的语言模型。
    - 它在各种NLP任务和应用程序上展现出了惊人的性能。
    - 它庞大的大小和多样化的训练数据使其能够生成高质量的文本，并以高准确度回答各种问题。
- 然而，该模型的计算要求以及潜在的偏见和错误在部署它到真实世界应用时是重要的考虑因素。此外，黑客可能会利用它进行成功的攻击。
- 但是让我们面对现实吧，ChatGPT有一个充满希望的未来。它最近从微软获得的投资和订阅试点的推出证明了这一点。
    
    [50 ChatGPT Statistics and Facts You Need to Know](https://blog.invgate.com/chatgpt-statistics)
    

## 1.2. 功能简介

- **基础能力**
    - **对话能力**：理解人类的语言，并生成回答
- **进阶能力**
    - **多轮对话能力**：与市场上泛滥的“人工智障”不同，ChatGPT 可以进行上下文理解和连续的对话，大大提升对话交互体验；
    - **模仿/模拟能力**：可以扮演某种职业或系统，生成特有的文本，例如写诗歌和歌词、模拟 Linux 系统、模拟整个聊天室、玩井字棋和模拟自动提款机等；
    - **审查功能**：查询会通过 OpenAI 公司范围的 API 进行过滤，防止产生冒犯性的输出。可能带有歧视等道德问题的提示将被忽略；
    - **认错能力**：面对不了解问题会承认无知，当用户纠正它时也会承认错误；
- **4 特有的能力**
    - **多模态**（对于图片的理解等）

<aside>
👨🏻‍💻 相关阅读与来源 1

</aside>

- 尽管聊天机器人的核心功能是模仿人类的对话者，但 ChatGPT 是多功能的。例如，它可以编写和调试计算机程序，[[17]](https://en.wikipedia.org/wiki/ChatGPT#cite_note-ChatGPT_can_write_code-18) 作曲、创作电视剧、童话和学生论文；回答测试问题（有时，根据测试，甚至超过了普通人的水平）；[[18]](https://en.wikipedia.org/wiki/ChatGPT#cite_note-19) 写诗和歌词；[[19]](https://en.wikipedia.org/wiki/ChatGPT#cite_note-jpost-20) 模拟 Linux 系统；模拟整个聊天室；玩井字棋等游戏；模拟自动提款机[[20]](https://en.wikipedia.org/wiki/ChatGPT#cite_note-ArsTechnicaTerminal-21)。ChatGPT 的训练数据包括 man 页面和有关互联网现象和编程语言的信息，例如布告板系统和 Python 编程语言。[[20]](https://en.wikipedia.org/wiki/ChatGPT#cite_note-ArsTechnicaTerminal-21)
- 与其前身 InstructGPT 相比，ChatGPT 试图减少有害和欺骗性的回答。[[21]](https://en.wikipedia.org/wiki/ChatGPT#cite_note-22) 在一个例子中，InstructGPT 接受 “告诉我克里斯托弗·哥伦布在2015年来到美国的情况” 的前提是真实的，而 ChatGPT 承认问题的反事实性质，并将其答案框定为如果哥伦布在2015年来到美国，将会发生什么的假设考虑，使用有关哥伦布的航海和现代世界的事实，包括有关哥伦布行动的现代感知。[[8]](https://en.wikipedia.org/wiki/ChatGPT#cite_note-OpenAIInfo-9)
- 与大多数聊天机器人不同，ChatGPT 记住了在同一次对话中给出的先前提示；记者认为这将使 ChatGPT 可以用作个性化治疗师。[[2]](https://en.wikipedia.org/wiki/ChatGPT#cite_note-Roose-2022-2) 为了防止 ChatGPT 产生冒犯性的输出，查询会通过 OpenAI 公司范围的 API 进行过滤，[[22]](https://en.wikipedia.org/wiki/ChatGPT#cite_note-23)[[23]](https://en.wikipedia.org/wiki/ChatGPT#cite_note-24) 可能带有种族主义或性别歧视的提示将被忽略。[[8]](https://en.wikipedia.org/wiki/ChatGPT#cite_note-OpenAIInfo-9)[[2]](https://en.wikipedia.org/wiki/ChatGPT#cite_note-Roose-2022-2)
    
    [ChatGPT](https://en.wikipedia.org/wiki/ChatGPT#Features)
    

## 1.3. 市场反响

ChatGPT 持续创造历史记录：

- 上线仅 5 天，ChatGPT 已经拥有超过 100 万用户
- 推出仅两个月后，在 2023年1月末，月活用户已经突破了 1亿，

以其他的非常受欢迎的消费级应用数据参考：TikTok 达到 1 亿用户用了 9 个月，Instagram 则花了 2 年半的时间。

ChatGPT 也成为了史上用户增长速度最快的消费级应用程序。

![Untitled](ChatGPT%20%E4%BB%8E%200%20%E5%88%B0%201%20%E7%B3%BB%E7%BB%9F%E6%80%A7%E5%AD%A6%E4%B9%A0%E8%B5%84%E6%96%99%E6%B1%87%E6%80%BB%20cbb8bd97914a49c896501fb3aae5de51/Untitled%201.png)

## 【Q&A】常见问题与回答

- **Q：什么是 GPT3、GPT4、ChatGPT？**
    
    GPT-3 (Generative Pretrained Transformer 3) 和 GPT-4 是 OpenAI 开发的语言处理 AI 模型，
    
    ChatGPT 则是使用语言处理 AI 模型创建的一个有高度能力的聊天机器人
    
    简单地说，GPT-3 让用户能够给受过训练的 AI 提供各种文字提示。这些可以是问题、请求在所选主题上撰写文本或大量其他的文字请求。
    
- **Q：ChatGPT 能做什么？**
    
    它具有相当广泛的能力，从在替代宇宙中写关于有感情的屁和陈词滥调的浪漫喜剧，到用简单的术语解释量子力学或撰写全文研究论文和文章。
    
    ![https://images.immediate.co.uk/production/volatile/sites/4/2022/12/Screenshot-2022-12-07-at-11.20.53-090e0ad-e1671540029989.png?quality=90&resize=700,157](https://images.immediate.co.uk/production/volatile/sites/4/2022/12/Screenshot-2022-12-07-at-11.20.53-090e0ad-e1671540029989.png?quality=90&resize=700,157)
    
    © OpenAI
    
    虽然使用OpenAI多年的研究让AI编写糟糕的单口喜剧脚本或回答关于你最喜欢的名人的问题可能很有趣，但它的力量在于其速度和对复杂问题的理解。我们可能会花费数小时研究、理解和撰写有关量子力学的文章，而ChatGPT可以在几秒钟内生成一篇写得不错的替代作品。
    
    它有其局限性，如果你的提示开始变得太复杂，甚至只是走了一条变得有点太小众的路线，其软件就很容易搞砸。同样，它无法处理过于新颖的概念。过去一年发生的世界事件将会面临有限的知识，该模型偶尔会产生虚假或混淆的信息。
    
- **Q：有什么像 GPT 一样的其它的语言处理 AI 模型吗？**
    
    虽然 GPT-3 因其语言能力而声名鹊起，但它不是唯一能够做到这一点的人工智能。目前有一些像 GPT 这样的语言处理 AI 模型，包括：
    
    - BERT（Bidirectional Encoder Representations from Transformers）：Google 开发的预训练语言模型，它使用 Transformer 网络结构，可以生成高质量的文本。
    - RoBERTa（A Robustly Optimized BERT Pretraining Approach）：Facebook 开发的预训练语言模型，使用与 BERT 相同的 Transformer 网络结构，但采用了更大的数据集和训练步骤，以提高性能。
    - T5（Text-to-Text Transfer Transformer）：Google 开发的预训练语言模型，可以处理各种 NLP 任务，例如文本摘要、问答和翻译。
    
    这些模型中大多数并不向公众开放，但 OpenAI 已开始在其测试过程中开放访问 GPT-3，而 Google 的 LaMDA 则以有限的测试能力向选定的群体开放。
    

---

# 2. 底层技术理解

## 2.1. 自然语言处理（NLP, Natural Language Processing）

**自然语言处理（NLP）是计算机程序理解口语和书写的人类语言的能力，也称为自然语言**。NLP 已经存在了 50 多年，起源于语言学领域。它在许多领域具有各种实际应用，包括医学研究、搜索引擎和商业智能等。

- NLP 是什么
    - **目标：使计算机能够像人类一样理解自然语言**（计算机只懂 0 和 1 的计算，而人类的语言则千变万化），特别是自动处理大规模自然语言语料
    - 交叉学科：计算机科学、人工智能和计算语言学
    - 难点：语言本身的复杂性、语境强相关、抽象概念联想、软硬件技术发展限制等
- NLP 解决的五个基本问题
    - 分类：assigning a label to a string
    - 匹配：matching two strings
    - 翻译：transforming one string to another
    - 结构化预测：mapping string to structure
    - 马氏决策过程：deciding next state given previous state and actions

更多阅读：

[****Ben Lutkevich：natural language processing (NLP)****](ChatGPT%20%E4%BB%8E%200%20%E5%88%B0%201%20%E7%B3%BB%E7%BB%9F%E6%80%A7%E5%AD%A6%E4%B9%A0%E8%B5%84%E6%96%99%E6%B1%87%E6%80%BB%20cbb8bd97914a49c896501fb3aae5de51/Ben%20Lutkevich%EF%BC%9Anatural%20language%20processing%20(NLP)%2076aa2c8dbcb8445eac4ffc034b1de00e.md)

[数据挖掘、机器学习、自然语言处理这三者是什么关系？这几个怎么入门啊？ - White Pillow的回答 - 知乎](ChatGPT%20%E4%BB%8E%200%20%E5%88%B0%201%20%E7%B3%BB%E7%BB%9F%E6%80%A7%E5%AD%A6%E4%B9%A0%E8%B5%84%E6%96%99%E6%B1%87%E6%80%BB%20cbb8bd97914a49c896501fb3aae5de51/%E6%95%B0%E6%8D%AE%E6%8C%96%E6%8E%98%E3%80%81%E6%9C%BA%E5%99%A8%E5%AD%A6%E4%B9%A0%E3%80%81%E8%87%AA%E7%84%B6%E8%AF%AD%E8%A8%80%E5%A4%84%E7%90%86%E8%BF%99%E4%B8%89%E8%80%85%E6%98%AF%E4%BB%80%E4%B9%88%E5%85%B3%E7%B3%BB%EF%BC%9F%E8%BF%99%E5%87%A0%E4%B8%AA%E6%80%8E%E4%B9%88%E5%85%A5%E9%97%A8%E5%95%8A%EF%BC%9F%20-%20White%20Pillow%E7%9A%84%2040734e19fa4a4c0aab048617b9ec0712.md)

## 2.2. 自然语言模型与发展历程：Transformer、BERT 与 GPT

**可以理解为自然语言模型是人类为了让机器做 NLP 所设计的机器人**，为了实现这个机器人，我们需要：

1. **设计一个算法**，机器人拿到一堆文本之后，他应该在机器内部做哪些计算，计算出一个什么样的结果输出出来；
2. **用足够多的数据训练它并告诉它正确答案**，类比人类，当你学会了一类数学题的公式之后，你需要做足够多的正确的练习才能掌握；

[自然语言模型简要发展历程](ChatGPT%20%E4%BB%8E%200%20%E5%88%B0%201%20%E7%B3%BB%E7%BB%9F%E6%80%A7%E5%AD%A6%E4%B9%A0%E8%B5%84%E6%96%99%E6%B1%87%E6%80%BB%20cbb8bd97914a49c896501fb3aae5de51/%E8%87%AA%E7%84%B6%E8%AF%AD%E8%A8%80%E6%A8%A1%E5%9E%8B%E7%AE%80%E8%A6%81%E5%8F%91%E5%B1%95%E5%8E%86%E7%A8%8B%20a62b09486e924b899b74fecf959706b4.md)

- 统计语言模型：以统计词频为主要手段的 n-gram模型，只能建立短程依赖，非常受到数据集的影响
- 2010 年，RNN（Recurrent Neural Network）
- 2013 年，word2vec：将每个词变成一个向量
- **2017 年，Transformer：是当下 GPT 盛世的转折点，**改变了以往序列建模和 RNN 划等号的思路，整个结构完全由注意力机制和前馈神经网络构成，架构如下
    
    ![Untitled](ChatGPT%20%E4%BB%8E%200%20%E5%88%B0%201%20%E7%B3%BB%E7%BB%9F%E6%80%A7%E5%AD%A6%E4%B9%A0%E8%B5%84%E6%96%99%E6%B1%87%E6%80%BB%20cbb8bd97914a49c896501fb3aae5de51/Untitled%202.png)
    
- 2018 年，GPT：GPT 系列的起点，利用了 Transformer 的解码器部分作为特征提取，可以理解是让机器做文本续写
- 2018 年，BERT：利用了 Transformer 的编码器部分，对训练集进行双向训练，可以理解是让机器做完形填空

相关阅读：

[NLP 模型发展简要史：从 bags of words 到 Transformer 家族](ChatGPT%20%E4%BB%8E%200%20%E5%88%B0%201%20%E7%B3%BB%E7%BB%9F%E6%80%A7%E5%AD%A6%E4%B9%A0%E8%B5%84%E6%96%99%E6%B1%87%E6%80%BB%20cbb8bd97914a49c896501fb3aae5de51/NLP%20%E6%A8%A1%E5%9E%8B%E5%8F%91%E5%B1%95%E7%AE%80%E8%A6%81%E5%8F%B2%EF%BC%9A%E4%BB%8E%20bags%20of%20words%20%E5%88%B0%20Transformer%20%E5%AE%B6%E6%97%8F%2081f64a1bb12448b88b6aa7833b4780c6.md)

[****Transformer论文逐段精读****](ChatGPT%20%E4%BB%8E%200%20%E5%88%B0%201%20%E7%B3%BB%E7%BB%9F%E6%80%A7%E5%AD%A6%E4%B9%A0%E8%B5%84%E6%96%99%E6%B1%87%E6%80%BB%20cbb8bd97914a49c896501fb3aae5de51/Transformer%E8%AE%BA%E6%96%87%E9%80%90%E6%AE%B5%E7%B2%BE%E8%AF%BB%20c5f61fb9b1e74714baadae45eed80b65.md)

## 2.3. 从 GPT1 到 GPT4

```jsx
$todo$
```

[【强烈推荐】****GPT，GPT-2，GPT-3 论文精读****](ChatGPT%20%E4%BB%8E%200%20%E5%88%B0%201%20%E7%B3%BB%E7%BB%9F%E6%80%A7%E5%AD%A6%E4%B9%A0%E8%B5%84%E6%96%99%E6%B1%87%E6%80%BB%20cbb8bd97914a49c896501fb3aae5de51/%E3%80%90%E5%BC%BA%E7%83%88%E6%8E%A8%E8%8D%90%E3%80%91GPT%EF%BC%8CGPT-2%EF%BC%8CGPT-3%20%E8%AE%BA%E6%96%87%E7%B2%BE%E8%AF%BB%20164a92a853014b7cb3f537b3ae7d7cfc.md)

[36Kr：****聊聊Chat GPT-1到GPT-4的发展历程****](ChatGPT%20%E4%BB%8E%200%20%E5%88%B0%201%20%E7%B3%BB%E7%BB%9F%E6%80%A7%E5%AD%A6%E4%B9%A0%E8%B5%84%E6%96%99%E6%B1%87%E6%80%BB%20cbb8bd97914a49c896501fb3aae5de51/36Kr%EF%BC%9A%E8%81%8A%E8%81%8AChat%20GPT-1%E5%88%B0GPT-4%E7%9A%84%E5%8F%91%E5%B1%95%E5%8E%86%E7%A8%8B%20f6e75860ae8f4639923ce711295e41ae.md)

## 2.4. LLM、AGI 与展望

## 【Q&A】常见问题与回答

- **Q：？**

---

# 3. 行业观察

## 3.1. 最新新闻（每日更新）

## 3.2. 行业概览与发展历程

## 3.3.  产业链及相关公司

## 3.4. 更多视角

## 【Q&A】常见问题与回答

- **Q：？**

---

# 4. 应用场景

---

# 5. 实操技巧