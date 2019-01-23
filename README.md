# 理工科论文阅读与写作

理工科论文阅读和写作是一项基本和重要的工作，因此必须重视对它们的训练和提升。本文是对ViaX论文写作课的直播总结，内容主要来自老师的讲解和PPT，也会附带一些自己的感想。以后也会实时更新。

## 1 为什么要读文献

文献是对已有知识成果的结构化总结，通过阅读文献，可以了解到新的研究领域和研究成果，利用文献综述可以快速地切入某一个研究点，也可以找到适合自己的研究方向，掌握前沿的研究方法和工具，同时也可以找到自己刚兴趣的研究单位和研究工作者，此外，阅读英文文献也是一个练习英语的机会。从理工科研究者的角度来说，阅读文献肯定是一项必须的工作，而且也是“积累的过程”，最后以达到高屋建瓴，“站在巨人的肩膀上”的目的。

## 2 如何读文献

### 2.1 文献种类

- 期刊论文 journal
- 会议论文 conference
- 学位论文 thesis/dissertation

### 2.2 搜索文献

在搜索之前，最好先确定自己的关键词以及年份，对于特别经典的文章，不一定非得看，得自己根据需要和专业进行取舍。确定好自己的关键词后，在Web of Science和Google Scholar进行搜索，然后根据领域内的优秀研究机构或者团队，年份，优秀的期刊或者会议进行筛选，比如计算机视觉领域的有三大顶会(CVPR, ICCV, ECCV)之类的。

之后，确定领域内的优秀的工作论文库和相关学者以及研究团队的个人网站，比如计算机视觉领域的有[arXiv](https://arxiv.org/)(如果嫌这个不好用，可以试试这个[Arxiv snaity preserver](http://www.arxiv-sanity.com/))和[慕尼黑工大的计算机视觉小组](https://vision.in.tum.de/)。

第三步是确定一下领域内最出色学校的博士论文数据库，毕竟博士论文通常是对一个细分领域的全面总结，而且一般来说国外大学的博士论文数据库都是免费开放的。比如CS&AI方面的有：MIT、 Standford、CMU等。

所以一般来说，就是通过关键词搜索，慢慢找到适合的点和研究机构，最后划定范围，经常去重点follow这些研究者的最新成果，然后通过积累慢慢形成自己的研究体系。

### 2.3 怎么去阅读

#### 2.3.1 理工科学术论文的要素

- **What**: 这篇文章要解决什么问题？
- **Why**：这篇文章为什么要解决这个问题？解决这个问题有什么意义？
  - Importance, implication, relevance
  - 切入点：现有文献、研究方法
- **How**: 这篇文章如何解决了这个问题？
  - Problem formulation, research methods, data, experiments, etc
- **What**: 这篇文章解决这个问题后得到了什么样的结论？
  - Conclusions, perspectives, outlook, etc.

#### 2.3.2 论文阅读的类型并判断是否值得读

从调研到了解，到后面的研究，论文的阅读深度应当逐渐增加的，宽度也在慢慢变小。

- 经典综述类文章 review articles (初入某一领域)
- 经典挖坑类文章 (发现寻找相关的领域研究点)
- 经典problem formulation, theory, algorithm, experimental design, etc.(经典的问题和通用的解法，以及基本的框架和思想等)
- 经典教科书 (对整个框架，细节都想了解把握)
- 其他相关类文章：prerequisite、互补、对比 (相关方法的优劣选择，激发自己的思考点)

文章太多，为了判断是否值得读，需要进行取舍和筛选。因为并非每篇文章都相关，也并非每篇文章都值得一读，大约1/4发表的文章都没有任何引用。尽量选择有知名度的实验室和作者，根据相关的行业标准选择适合的期刊或者会议，就计算机视觉来说，成果发展更迭的速度很快，一般选择看顶会文章，例如: ICCV, CVPR, ECCV, ICRA 等和 arXiv。

- 广泛浏览，看是否值得去重点读
  - **标题**--是否相关
  - **读摘要**--微缩版本的论文
  - **看图，读图注**--做了什么实验，结果或者效果怎么样
  - **读结论**--前后关联

通过以上四步确定是否需要自己重点阅读。当然，看论文的作者和机构也是可以那来衡量好坏的一个标准。

#### 2.3.3 理工科论文重点阅读流程

理工科论文的阅读不该是从头读到尾，遇到不会的词翻译一下，然后把全文的字面意思搞懂了，这种阅读方式不推崇，否则最后最多只是知道这篇文章的作者做了什么，提出了什么的东西，然而他的创新点在哪里，解决了什么问题，为什么这样做，或者这样做可以，还是没个概念。正确的思路是，这篇文章是想要解决什么问题，背景和动机是什么，然后看前人解决是用的什么方法解决的，然后现在的研究者都在关注什么方面来进行创新和提升，最后看本文的作者是属于其中的创新还是另辟蹊径，如果是另辟蹊径，他又是从何而知的？**实际上，我们对问题的解决应当是尽可能地了解这个问题的本质，然后去思考解决问题的途径。不一定要按照别人给搭好的框架来解决，而是想想如何快速有效地解决其中的问题或者是某个环节的问题。研究论文确实不应该是技术的堆砌，而是应该布满逻辑，表达思想**。

阅读时，着重于论文的关键部分，比如 **methods** 和**experiments** 部分。

- 抽丝剥茧、庖丁解牛：快速抓取核心要素

- 结构化阅读：to what level of details

- 建立自己的知识框架及思维结构，输入而后输出

- 旁征博引、交叉创新

- 重现论文结果 (reproduction)
  - 熟悉研究方法
  - 熟悉数据结构
  - 建立和论文作者的合作关系

## 3 理工科论文的写作

理工科的论文写作不应当是一件困难的事情，只要有研究内容，有研究成果，而且同时自己也认同自己的工作的时候，那么写起来就会很轻松，尤其是对那些常看论文的研究者更是如此。如果言之无物，写无可写，那么就会感到痛苦。

此外，写论文不单是信息的输出和表达，应当是个思辨的过程，应当是有着信息完整、清晰的称述和缜密的逻辑，可以站在读者的角度（“同理”，“共情”）。要想写出一篇能够包含了自己的思想，同时又能易被大多数读者接受，了解的文章，是需要自己不断地练习：多读，多想，多写。

### 3.1 写作的流程

一个好的 idea 不是凭空出现的，是在于平时的积累与思考，要在日常的阅读和发现中，勤记笔记，
多做调研，而且要把握重心，不要囫囵吞枣，随便看看。

写作的大概流程：

- Idea search（长期 / 短期）
  - 长期：积累，多读多想多讨论，思维框架及知识体系、connecting the dots 
  - 短期–几类创新思路:
    - 改进已有的方法 
    - 解决悬而未决的行业基准
    - 提出新的应用场景（确保尚未被发表）

- 文献调研

- 初步验证 proof-of-concept

- 深入探究

- 论文写作

- 总结、反思、展望

写作的内容也需要按照理工科论文的要素来。我们在解决问题的时候是从问题出发，然后改进了或者提出一些解决办法，写作的时候应该是倒着来的。文章的内容应该包括问题是什么，为什么要解决，怎么解决的，最后结果怎么样，结论是什么。尽量确保论文具有一定的创新性，合理性和可读性。Story-telling.

### 3.2 写作的逻辑和架构
一篇论文通常包含以下几个部分：

- 标题 title
- 关键词 key words
- 摘要 abstract
- 引言/研究动机 introduction and motivation
- 文献综述 literature review
- 问题描述 problem formulation
- 结果 results
- 讨论 discussions/remarks
- 结论summary/conclusions/perspectives/outlook
- 引用 reference/bibliography
- (optional)
  - 附录 appendix
  - 补充材料 supplemental materials
  - 符号表 notation table

不过正式发表论文的一般结构通常更加简化，更符合阅读习惯，适合信息输入：

- **(TA)IMRaDC**
  - **(Title & Abstract)**
  - **Introduction**
  - **Methods**
  - **Results and Discussion**
  - **Conclusion**

不过一般来说，实验性的学术论文可能不会从头开始一步步写，而是按照**MI(F)RaDCAT**的是顺序：

- **Methods**--while/upon doing experiments and analysis
- **Introduction**--out of literature review, clear when choosing the topic
- **(Figures and Tables, including captions)**--upon completion of experiments and analysis
- **Results and Discussion**--on the basis of figures and tables (including captions)
- **Conclusions**--summary of the findings based on results and discussion
- **Abstract**--summary of the paper
- **Title**

#### 3.2.1 Methods

在这一部分介绍自己是如何进行实验和分析的。

- 可以在实验时就进行相关的准备

- 将实验过程和分析步骤转换成合适的语言，并且记下实验环境，实验设备等相关细节，注意按照一定的顺序

- 介绍具体研究方法，包括方法选择的合理性，数据的采集，实验的过程等

- Checklist：framework + algorithms + derivation + experiments + …

  - 方法选择的合理性和优势

  - 数据采集过程和数据整理归类步骤

  - 重点变量的衡量方法

  - 实验过程、步骤

    

#### 3.2.2 Introduction (Motivation, Literature Review, Problem Formulation)

其实个人感觉Introduction部分最难的是动机部分。因为可能大多数国内的研究生/博士的课题并不是自己选择和感兴趣的，因此最大的动机就是”毕业“或者”评奖“之类，不过正式的论文肯定不能这门写了，必须要突出该问题的背景以及意义，突出没有这个课题不行，或者这个问题不解决不行，同时也可以讲讲未来可以改进或者发展的方向。

这部分的写作要点就是：**大背景 + 重要性 + 扩充版 abstract + future works + outline (recommended)**

**Literature Review**：（提前做好准备，可以从他人的文章中获取灵感，没必要涵盖领域的方方面面）

- 交代研究问题在整个领域的位置，文章的切入点及其与现存文献的关系
- 目的：介绍研究问题、方法、数据选择的重要性/原创性
- 写作要点：（**介绍研究问题的重要性以及与以往研究的关系，不只是单纯的总结和梳理**）
  - 该领域目前的知识水平
  - 你的研究依据什么样的先验知识
  - 以前的相关工作解决了什么问题，还有什么问题没解决，他们又是基于什么样的假设条件
  - 用文献支持研究问题选择和问题切入点选择的合理性
  - 用文献解释方法和数据选择的合理性

**Problem Formulation：**

这一部分其实在文献综述部分就可以完成。不过还是可以说下，毕竟也是把问题进行数学抽象的过程。

- 对要解决的问题进行建模、简化、假设、抽象成可解决的模型
- 目的：建立模型，speak the language, what to do and what not to
- 要求：实际问题抽象化，抽象问题具体化

最后一段话基本上是描述本文的结构安排，工作安排。

#### 3.2.3 Figures and Tables including caption

好的、规范的图表是给文章增色的大筹码。它们是对文章实验或者理论的展现，是对自己工作的总结。

- 图表的内容肯定是依据实验和数据集的，而且也是文章后面Results & Discussion的基础。在内容方面，因人而异，但是肯定要能最大限度的反映自己的工作，同时紧凑，有力。
- 需要注意的是，平时要加强对相关绘图或者可视化软件，库的应用，比如matlab，python等，也可以自己试着做一个自己的风格化模板，方便以后自己随时调用。这也是我本人正在寻找和练习的技能。
- 注意可以在图标加上一些细节，同时使得图标的重点突出，对比明显。

#### 3.2.4 Results & Discussion

**What did you find, and what does it mean?**

- Results是陈述事实，Discussion是解释最终的结果。
- 基于图和表来写，按照先后顺序，向读者解释图表的内容和关键信息，然后写出自己的想法（A增加是因为.../B没有作用是因为.../C的作用比D更突出）。尽量覆盖到每个图表，把每个图表当成一个小单元来进行描述总结。
- 写Results时不要复制图表的信息，而是描述事实。
- Discussion是总结主要的发现，”就事论事“，不过也要与前面的Introduction部分相关联，是不是相符，有没有什么不同的发现，创新点在哪，同时也可以进行自我批判，自己的工作是否可靠，置信度是多少。

#### 3.2.5 Conclusions/Summary/Perspectives/Outlook

- 总结全文，反思不足，展望未来，遵循”简洁“，”恰当“，”精准“的原则。
- 写作要点：
  - 研究问题
  - 假设
  - 研究方法
  - 结论
  - 贡献
  - 不足与限制，领域大背景下的位置
  - 未来的研究方向 

#### 3.2.6 Abstract（不要过分重复每个部分已有的内容和句子）

 一段原创的，简短的，描述一篇文章全部工作的论述，目的是总结全文，概括信息，点明主题。我们往往放到最后才写摘要，因为论文在写作的过程中会经常改动，有些新的idea可能会加进来，所以要等最后确定了文章的内容才开始写。

摘要是全文的门面，也是大多读者首先看的地方，而且摘要在一定程度上代表着整篇论文，在各类场合都可以用到 (conference submission, elevator pitch, seminar, conferences, etc.)，**因此好的摘要对论文很重要。类似于一个好的故事，在组织语言时，要首先组织好思维**。

那么如何在有限的字数下写好摘要，怎样”一言以蔽之“，却又能让读者产生读下去的欲望，怎样在现有的知识框架下总结并呈现自己的工作的发现？

- 写作要点：
  - **P: Problem** 文章要解决什么问题
  - **A: Approach** 文章运用了什么方法
  - **R: Result** 得到了什么结果，这些结果能得出什么结论
  - **I: Impact** 这些结论有什么具体的影响
- 注意事项：
  - 摘要是一个微缩版本的论文，要确保各部分连成一个整体，比如研究对象定义清晰明确，研究对象贯穿始终，恰当的逻辑连词使用等。
- How to write a good abstract--A bit more detail (*Nature* guidelines)
  - One or two sentences providing a basic introduction to the field, comprehensible to a scientist in any discipline.
  - Two to three sentences of more detailed background, comprehensible to scientists in related disciplines.
  - One sentence clearly stating the general problem being addressed by this particular study.
  - Two or three sentences explaining what the main result reveals in direct comparison to what was thought to be the case previously, or how the main result adds to previous knowledge.
  - One or two sentences to put the results into a more generalcontext.
  - Two or three sentences to provide a broader perspective, readily comprehensive to a scientist in ant discipline, may be included
    in the first paragraph if the editor considers that accessibility of the paper is significantly enhanced by their inclusion.
  - Collect commonly used phrases (applies to all parts of your manuscript): 
    - During… the process of… are…
    - Hypotheses…include…
    - However,…unknown…
    - Here, we found/show…
    - Furthermore,…
    - Our results demonstrate…
    - We propose…
    - Furthermore…
    - In conclusion,…
- Pay attention to these details:
  - Write DIRECT sentences, not: according to…, taking into…, …
  - Noun-verb agreement (the study shows, but the studies show)
  - Pay attention to grammar: verbs, nouns, adjectives
  - Define all new terms, concepts, abbreviations

#### 3.2.7 Title & Key words

**Title:**

- 目的：准确概述文章内容，吸引读者阅读
- 要求：精准，简洁，有吸引力 (optional)
- 经典风格
  - Descriptive/Informative:
    - 问题 (like：）
      - Transactive Control in Smart Cities
      - Iterative Value-Aware Model Learning
    - 问题 + 解决方法/key deliverable：
      - Policy Gradient Methods for Reinforcement Learning with Function Approximation
      - Human-Level Control Through Deep Reinforcement Learning
  - Story telling
    - Autonomous Taxis Could Greatly Reduce Greenhouse-Gas Emissions of US Light-Duty Vehicles
    - How Does Batch Normalization Help Optimization? (No, It Is Not about Internal Covariate Shift)

**Key words:**

- 目的：准确概述，吸引读者阅读，方便索引/检索
- 可包含：领域、问题、方法、new terminologies
- 五个左右为宜，不要包含太多的修饰词。

#### 3.2.8 References

- 注意格式，一些文献管理软件和工具可减轻负担



## 4 结语

多阅读，多思考，多练习，牢牢把握每个部分的核心功能。论文的写作不是一蹴而就的，同时每次写论文也不是一次就会成功的，需要不断地修改，比如可以分散任务到不同的周期，写第一遍的时候，重点关注信息表达本身，”把话说清楚“，不必关注语言和文章的行文以及架构，在第二遍的时候，解决逻辑漏洞，顺序不当，语言不妥的问题，不过太过担心语言的技巧问题，不必用太多的从句，使用简单的英语就足够了。

- 先做加法，再做减法。先把想写的，都能写的都写进去，后期进行提炼总结和删减，使得逻辑性和可读性更强。
- 以图表串联。注重图表的重要性，不要写太多的理论和公式，图表往往更容易接受。
- Story telling. 写作风格不一定要很冷淡，可以再严谨的前提下，适当增加一定的趣味性，让文章更容易通读。
- No free lunch, tradeoff and how to formulate, stop doing list. idea 和理论固然重要，但是时间和练习是必不可少的。
- 整体把握，现有腹稿，紧扣核心思想。
- 合理地 sell 但绝不 oversell. 展现自己的工作是有意义的，但是不要过分卖弄。
- 提高可读性：主旨清晰，结构及凑，逻辑合理，承接自然，语言简洁，论点鲜明，论据有力。
- LaTex versus Word/Pages. 各有各的好处。
- 合作。学会与他人合作进行论文工作的写作
