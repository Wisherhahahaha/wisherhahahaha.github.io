---
title: 人类代谢-C2-细胞层面
date: 2026-05-28 00:00:00 +0800
last_modified_at: 2026-05-28 00:01:00 +0800
categories: [科研, 代谢] # 最多两层
tags: [科研, 代谢, book]
# toc: false # 关闭目录
math: true
mermaid: true # diagram generation
---


## Chapter 2

## Cellular aspects of metabolic regulation

本章的核心逻辑：**人体不仅在宏观上存在“摄入”与“支出”的空间错位，在微观的细胞层面，更存在极其精准的“短、中、长期”调控网络，以决定某种营养素在特定的细胞内究竟是该“进”、该“出”、该“存”还是该“烧”。**

## 模块一：时空维度的代谢控制战略

代谢调节的本质，是**根据身体需要控制代谢物在通路中的流量（Flux）**。这种调节在时间和空间上展现出极其优美的层次感：

### 1. 空间维度：组织特异性（Tissue Specificity）

每个器官在人体中扮演的角色不同，其细胞内的酶谱配置也完全不同：

* **肝脏（慷慨的利他主义者）：** 表达**葡萄糖-6-磷酸酶（G6-Pase）**。当血糖降低时，肝脏能将肝糖原分解出的 G6-P 脱去磷酸，转化为自由葡萄糖释放入血，救济全身。
* **骨骼肌（自私的利己主义者）：** **不表达** G6-Pase。肌糖原分解出的 G6-P 只能留在肌细胞内进行糖酵解，供自己运动发电，绝不外调。
* **大脑（特权阶层）：** 无论你刚吃饱还是在挨饿，大脑都必须以相对恒定的速率消耗葡萄糖。为了实现这一生理目的，大脑神经元特异性地表达了高亲和力的葡萄糖运输蛋白，确保“不管血糖怎么干涸，先满足大脑”。

### 2. 时间维度：短、中、长期调控网络

* **短期调控（几分之一秒至数分钟）：** 应对突发状况（如短跑运动员听到发令枪响）。主要通过**别构调节**和**共价修饰（如磷酸化/去磷酸化）**，不改变酶的数量，只瞬间切换酶的活性开关。
* **长期调控（数小时、数天至数周）：** 应对生活方式的变化（如长期高糖饮食、断食、耐力训练）。主要通过**基因表达（Gene Expression）**调控，直接改变细胞内酶和运输蛋白的**绝对数量（合成与降解速率）**。

---

## 模块二：细胞膜上的“守门人”——底物运输蛋白家族

材料明确指出：**底物穿透膜的流动是代谢调节的关键位点。** 细胞膜的磷酸化双分子层排斥极性分子，因此所有小分子营养素的进出都必须依赖特异性的运输蛋白（Solute Transporters，系统命名为 SLC 家族）。

### 1. 葡萄糖运输蛋白：GLUTs（协同扩散）与 SGLTs（继发性主动运输）

根据米氏动力学（Michaelis–Menten kinetics），运输蛋白对底物的亲和力（$K_m$ 值）直接决定了该组织的代谢命运：

* **GLUT3（大脑特异）：** $K_m$ 值极低（约 1.6 mmol/l）。这意味着在正常血糖（5 mmol/l）甚至极低血糖下，大脑的 GLUT3 都处于完全饱和、满负荷运转状态。**大脑的智慧不会因为一顿饭没吃就瞬间垮掉，这正是低 $K_m$ 值的进化优势。**
* **GLUT2（肝、胰岛 $\beta$ 细胞）：** $K_m$ 值极高（7–20 mmol/l），属于**低亲和力、高容量**运输蛋白。流入细胞的葡萄糖速率与血浆葡萄糖浓度成正比。血糖越高，进得越快，这让肝脏能完美充当血糖缓冲器，也让胰岛 $\beta$ 细胞能精准感知血糖并释放胰岛素。
* **GLUT4（脂肪与肌肉特异——胰岛素敏感型）：** 平时藏在细胞质内部的囊泡（Vesicles）中。当胰岛素与受体结合，触发信号级联放大，这些囊泡会迅速向细胞膜易位（Translocation）并融合，使膜上的 GLUT4 数量暴增数倍，疯狂吸纳血糖。当胰岛素撤离，GLUT4 重新内吞回吐（见图2.2）。
* **SGLT1/SGLT2（肠道与肾小管的主动运输）：** 逆着浓度梯度强行吸收葡萄糖。它们利用钠泵（$Na^+-K^+-ATPase$）制造的 $Na^+$ 顺浓度梯度流作为动力，把葡萄糖协同带入细胞。*（注：现代临床使用的糖尿病新药 SGLT2 抑制剂，就是通过抑制肾脏对葡萄糖的重吸收，让多余的糖直接随尿排出）。*

### 2. 氨基酸与脂肪酸的跨膜调控

* **氨基酸运输：** 细胞内的游离氨基酸浓度远高于细胞外（如肌肉中谷氨酰胺细胞内外的比例高达 34:1）。这种逆浓度差完全依赖 **$Na^+$偶联的主动运输系统（如系统 A）**。
* **脂肪酸（NEFA）运输：** 脂肪酸穿膜既靠物理上的“翻转跳跃（Flip-flop）”，也依赖专职看门人——**CD36（FAT）**和 **FATP 家族**。进入细胞后，脂肪酸立即被**酰基辅酶A合成酶（ACS）**进行硫酯化活化，加上辅酶 A 的外套。这不仅消除了脂肪酸的洗涤剂毒性，更将其**锁定在细胞内**，维持了膜两侧的内低外高梯度。**在运动或胰岛素刺激下，CD36 也会像 GLUT4 一样发生向细胞膜的易位回收。**

---

## 模块三：短期调控的精细艺术——构象、共价与底物循环

快速调节的核心在于**改变蛋白质的构象（Protein Conformation）**。

### 1. 别构调节（Allostery）——细胞内的高效反馈回路

酶除了催化位点外，还拥有一个别构位点。当特定的代谢物（别构剂）结合在此处时，酶的整体三维结构会在“紧绷态（T态，低活）”与“松弛态（R态，高活）”之间切换。

* *典型范例*：糖酵解的关键限速酶 **PFK-1（磷酸果糖激酶-1）** 会被过剩的 $ATP$ 别构抑制。当细胞能量充足时，$ATP$ 结合别构位点，直接叫停糖酵解，避免资源浪费。

### 2. 共价修饰（Covalent Modification）——开关机制

利用激酶（Kinase）消耗 $ATP$ 挂上磷酸基团，或利用磷酸酶（Phosphatase）摘掉磷酸基团。

* **代谢的总战略规律：** 绝大多数负责**燃料动员（Catabolic，分解）**的酶，在**磷酸化**状态下被激活（如糖原磷酸化酶、激素敏感性脂肪酶 HSL）；而负责**燃料储存（Anabolic，合成）**的酶，在**去磷酸化**状态下被激活（如糖原合酶）。这一精妙的设计确保了合成与分解通路绝不会同时打架。

### 3. 能量传感器：$ATP$ 之外的 $NAD$ 宇宙

我们熟知 $ATP/AMP$ 比例激活 AMPK 是细胞的能量仪表盘。但材料指出了另一个前沿机制：**$NAD^+/NADH$（氧化还原状态）也是核心能量信号。**

* **Sirtuins（去乙酰化酶家族，如 Sir2）：** 它们是 **$NAD^+$ 依赖性酶**。当细胞处于热量限制（Calorie Restriction）或受到红酒提取物白藜芦醇（Resveratrol）刺激时，$NAD^+$ 浓度升高，激活 Sirtuins。
* Sirtuins 会切断 $NAD^+$ 并释放 ADP-核糖，以此为接收器，**强行剥离**众多代谢酶和组蛋白上的乙酰基（Acetylation）标记。这种去乙酰化修饰深刻改变了细胞的代谢程序，与促进长寿、提高线粒体抗氧化能力密切相关（见图 2.5.1）。

### 4. 底物循环（Substrate Cycling / 虚无循环）——代谢的“怠速状态”

在 Figure 2.3 中，正向反应（Enz 2A）和逆向反应（Enz 2B）在细胞内同时低速率运行。这看似浪费 $ATP$，实则是进化的高明之处：

> **专家视点：** 如果正向流量是 10，逆向是 9，净流量只有 1。此时如果身体突然需要爆发，只需要将逆向反应（Enz 2B）抑制 50%（变成 4.5），净流量瞬间飙升至 5.5（大涨 450%）。**底物循环就像让跑车在起跑线上保持发动机“怠速”运转，只要松开一点刹车，就能实现惊人的瞬间加速度。**

---

## 模块四：长期调控的核心——营养素对基因表达的跨界操纵

当饮食结构或环境发生长达数天或更久的改变时，细胞内的**核受体与转录因子**启动，直接修改 mRNA 的转录版图。材料介绍了四大最为经典的调控系统：

```
[高糖饮食] ➔ 产生G6-P等 ➔ 激活PP2A ➔ ChREBP去磷酸化 ➔ 入核 ➔ 启动脂肪合成基因 (FAS, ACC)
[高脂饮食] ➔ 游离脂肪酸 ➔ 结合核受体 PPARs ➔ 与RXR结合成二聚体 ➔ 启动脂肪氧化/储存基因

```

### 1. 碳水化合物应答系统：ChREBP 机制

当我们摄入大量糖类时，即使不依赖胰岛素，葡萄糖代谢产生的中间体（如 G6-P、木酮糖-5-磷酸）也会激活蛋白磷酸酶 PP2A。

* PP2A 将细胞质中的 **ChREBP（碳水化合物应答元素结合蛋白）** 去磷酸化，使其获得“通行证”进入细胞核，结合在 DNA 的 ChRE 启动子区域。
* **后果：** 开启**脂肪合成大军**（乙酰辅酶A羧化酶 ACC、脂肪酸合酶 FAS、硬脂酰辅酶A去饱和酶 SCD 等基因暴涨），将多余的碳水化合物彻底固化为脂肪储存起来（见图2.6）。
* 反之，在饥饿时，胰高血糖素通过 cAMP 激活 PKA，将 ChREBP 强行磷酸化，将其驱逐出细胞核，叫停脂肪合成。

### 2. 脂质应答系统：PPARs 家族（核受体的艺术）

脂肪酸及其衍生物本身就是**脂质调控基因的配体（Ligands）**。它们进入细胞核，结合 PPAR 家族，随后必须与类视黄醇 X 受体（RXR，配体为维生素A衍生物）结成异二聚体（Heterodimer），在辅 activator（如 **PGC-1$\alpha$**）的协助下，轰炸 DNA 上的 PPRE 区域（见图2.7）：

* **PPAR-$\alpha$（主要在肝脏、心肌）：** 感知脂肪酸增多，疯狂上调 CPT-1 及线粒体/过氧化物酶体的 $\beta$-氧化酶类。**“既然脂肪来了，就开足马力烧掉它”**。*（临床降脂药“贝特类/Fibrates”正是 PPAR-$\alpha$ 的人工配体）*。
* **PPAR-$\gamma$（主要在脂肪组织）：** 促进前脂肪细胞分化为新的、健康的小脂肪细胞，并上调 GLUT4 和脂蛋白酶（LPL），把血液中的游离脂肪酸和葡萄糖强行拽进脂肪细胞锁死。*（临床降糖药“噻唑烷二酮类/Glitazones”即通过激活 PPAR-$\gamma$，把乱窜的毒性脂肪酸收纳进脂肪细胞，从而解除骨骼肌的胰岛素抵抗）*。
* **PPAR-$\delta$（主要在骨骼肌）：** 实验中实验性上调该基因的骨骼肌细胞，线粒体爆发式增长，白肌纤维转变为耐力型红肌纤维。拥有这种基因操纵的小鼠在跑步机上跑几个小时不知疲倦，被称为“马拉松小鼠（Marathon Mice）”。

### 3. 胆固醇应答系统：SREBP 负反馈刹车

细胞如何监控自己的胆固醇水位？

* 正常情况下，全长的 **SREBP** 蛋白和感应器 **SCAP** 联手镇守在内质网（ER）膜上。如果膜内胆固醇高，SCAP 会死死拽住 SREBP 不松手。
* 当细胞内胆固醇水位下降，SCAP 发生构象改变，打包 SREBP 转移至高尔基体。在高尔基体中，SREBP 遭到专职蛋白酶的**蛋白水解剪切（Proteolytic Cleavage）**。
* 被切下的 N端活性片段（成熟 SREBP-2）单刀直入冲进细胞核，疯狂启动 **HMG-CoA还原酶（胆固醇合成限速酶）** 和 **LDL受体（从血液中抢夺胆固醇的触手）** 基因的转录（见图2.8）。
* *补充：其同胞兄弟 **SREBP-1c** 则主要受到胰岛素操纵，负责介导脂肪的合成储存。*

### 4. 氨基酸与蛋白质合成的舵手：mTORC1 通路

细胞在打算合成蛋白质扩张“家产”前，必须同时确认两件事：能量够不够？原材料（氨基酸）齐不齐？

* **mTORC1（哺乳动物雷帕霉素靶蛋白复合体1）** 就是这个终极审计师。它能直接被亮氨酸（Leucine，核心必需氨基酸）和胰岛素激活。
* 激活后的 mTORC1 磷酸化下游靶点，启动 mRNA 的**翻译起始（Translation Initiation）**，拉开蛋白质合成与肌肉生长的序幕。这也是运动训练后促使肌肉肥大的底层分子开关。

---

## 模块五：环境与时钟的宏观统御——昼夜节奏与低氧应答

细胞长期调控不仅听从营养素的指挥，还受到体内生物钟和外在环境氧气的绝对统治。

### 1. 细胞内的昼夜时钟：CLOCK / BMAL1 振荡回路

即使把你关在没有光线的地下室，你细胞内的代谢活动依然保持着大约 24 小时的起伏波动（Circadian Rhythms）。

* 在细胞核内，**CLOCK** 和 **BMAL1** 两种蛋白结合成转录因子，启动 **Period (Per)** 和 **Cryptochrome (Cry)** 基因的转录。
* 随着 Per 和 Cry 蛋白在细胞质中越积越多，它们会形成复合体反向杀回细胞核，**直接死死抑制住它们的启动者——CLOCK/BMAL1 复合体**。
* 随着 CLOCK/BMAL1 被抑制，Per 和 Cry 的产出停止，逐渐被细胞降解。当它们降解殆尽后，CLOCK/BMAL1 再次重获自由，开启下一轮转录。
* **代谢关联：** 这一自我否定、周而复始的转录-翻译反馈回路（TTO Loop）刚好耗时约 24 小时（见图2.5）。在此期间，全人类接近一半的代谢酶基因都在顺应这一振荡频率，决定了我们“白天高效消化、夜晚安全修复”的 innate 代谢节律。而这一切的神经总司令，是大脑视交叉上核（SCN）通过褪黑素（Melatonin）对全身外周时钟进行的强行光线校准。

### 2. 生死存亡的氧气传感器：HIF-1 机制

当人体长期处于低氧环境（如高原生活、剧烈运动导致的组织局部缺血或缺氧）时：

* 缺氧会迅速激活转录因子 **HIF-1（低氧诱导因子-1）**。
* HIF-1 进核启动灾难自救程序：
1. 疯狂上调 **GLUT1/GLUT3 和全部糖酵解酶类**（因为无氧酵解是不依赖氧气的唯一残存发电手段）。
2. 启动促红细胞生成素（EPO）基因，逼迫骨骼造血，增加血液运氧载体。
3. 启动**血管生成（Angiogenesis）**，在缺氧组织周围疯狂加盖微血管网络，改善灌注。



> **本章核心总结：** 细胞层面的代谢调节，是一场由**转运蛋白控流、别构与共价修饰把关（短期）、核受体与转录因子重塑数量（长期），并在昼夜时钟与氧气环境的宏观天幕下**共同编织的交响乐章。各大组织通过这些微观机制各司其职，最终达成了全人类整体生存的生化奇迹。

## Key learning points

•	 Flux through metabolic pathways needs to be controlled. Different tissues need different patterns of metabolism according to their roles in the body. In addition, metabolic pathway flux needs to change with time, for instance to store nutrients after a meal or mobilise them between meals, or to provide fuel for exercise. 

•	 Mechanisms for regulating metabolic flux might be divided into (i) features specific to individual tissue, (ii) short-term dynamic changes (over periods of minutes or hours), and (iii) longer-term changes (over periods of days or longer). 

•	 Many key metabolic enzymes exist in different isoforms (coded for by different genes), expressed in different tissues. Usually the isoforms catalyse the same reaction but the regulation is different. 

•	 The flow of substrates across membranes is a potential site for regulation. Families of transporter proteins exist for all major ‘energy metabolites’: glucose, fatty acids, amino acids; also for cholesterol and glycerol, and even water. Tissue-specific expression of different isoforms of these transporters confers metabolic specificity on tissues. 

•	 Short-term metabolic regulation often involves covalent modification of enzymes, especially phosphorylation/dephosphorylation. It may also involve allosteric effects, or translocation of proteins within a cell. Many of these processes involve changes in the conformation of proteins. 

•	 Metabolic pathways are also regulated over each 24-hour cycle by innate circadian rhythms, governed by ‘clock mechanisms’ within cells and coordinated by the brain. 

Metabolic flux may need to be regulated over longer periods, for instance to allow the body to adapt to changes in lifestyle (e.g. changes in diet or exercise level). They involve changes in the amounts of proteins, most commonly brought about by changes in the rate of transcription of the genes concerned into mRNA. The overall process leading from a gene to its product is called gene expression. 

Nutrients and other major metabolic substrates also regulate gene expression. Glucose regulates gene expression through a specific protein, the carbohydrate response element binding protein (ChREBP), that binds to carbohydrate response elements in gene promoter regions. 

Fatty acids act through nuclear receptors known as peroxisome proliferator-activated receptors (PPARs), largely to regulate fat oxidation and fat storage. Cholesterol acts through a sterol regulatory element binding protein, SREBP-2, to regulate the genes involved in its own synthesis and in bringing cholesterol into cells. Amino acids also regulate gene expression by several systems. 

Oxidative metabolism generally is regulated by the production of new mitochondria and/or the amounts of enzymes within existing mitochondria. Oxygen availability (especially hypoxia, low oxygen content) regulates gene expression through a transcription factor known as hypoxiainducible factor-1 (HIF-1). 

## 2.1 What is metabolic regulation?

In Chapter 1 we saw that metabolism consists of pathways that deliver nutrients into storage forms, pathways that deliver useful substrates from storage forms, pathways that produce energy from nutrients or other substrates, and many other processes such as synthesis and breakdown of the components of DNA and RNA. The first three will be of particular interest to us. 

However, these pathways are not universal and static. They differ from tissue to tissue, often from cell to cell within one tissue, and they change with time. This is what we will call metabolic regulation.1 Metabolic regulation, then, might be defined as controlling the flow of metabolites along metabolic pathways according to the body’s needs. 

There are various aspects to this. One is the partitioning of nutrients or metabolic substrates between tissues and organs in different nutritional states. Mechanisms for this tissue-specificity of metabolism will be discussed below, and metabolic differences between tissues at length in Chapter 5. But there is also a dynamic aspect. 

Metabolic fluxes within and between tissues may need to change, sometimes gradually, sometimes very rapidly. Mechanisms for bringing this about will involve changes within tissues, described below, but also often communication between tissues, the subject of Chapter 3. 

## 2.2 What makes one tissue different from another?

## 2.2.1 Tissue-specific enzyme expression

The characteristics of individual cells or tissues ‘set the scene’ for metabolic regulation. For instance, the metabolic characteristics of the liver mean that it can take up excess glucose from plasma, whereas other tissues cannot adjust their rates of utilisation so readily. Therefore, the liver is likely to play an important role in glucose metabolism whenever plasma glucose levels are high. The brain, in contrast, has a pathway for utilising glucose at a rate that is relatively constant whatever the plasma glucose concentration (within reasonable limits) – a very reasonable adaptation since we would not want to be super-intelligent only after eating carbohydrate, and intellectually challenged between meals. 

Tissue specificity is largely achieved by the expression of particular enzymes or proteins that impart specific metabolic properties to that tissue. For instance, some tissues do not express particular enzymes, others do. An example is glucose-6-phosphatase, the enzyme for making glucose from glucose 6-phosphate (produced either from glycogen breakdown or from gluconeogenesis). Liver cells (hepatocytes) express this enzyme: skeletal muscle cells do not. Therefore, liver glycogen breakdown can contribute directly to blood glucose; skeletal muscle glycogen breakdown cannot. The enzymes of the urea cycle are expressed only in hepatocytes (although there are small amounts in other tissues): therefore the liver is the key site for disposal of amino-nitrogen as urea. In addition, many key enzymes in metabolism have more than one isoform (often called isoenzymes or isozymes), related in structure and function, but usually produced from different genes, and with different regulatory properties. There are different isoforms of both glycogen synthase and glycogen phosphorylase expressed in liver and muscle (and a third brain isoform for glycogen phosphorylase), coded for by different genes. They catalyse identical reactions but their regulatory properties are subtly different. The family of glucose transporters (GLUTs), to be described later, is another example: tissue-specific expression gives different characteristics to tissues in terms of glucose uptake. The first step in the metabolism of glucose within cells is always phosphorylation on the 6-carbon (to form glucose 6-phosphate) and this is brought about by a member of the hexokinase family of enzymes; again, different members of this family with different kinetic and regulatory properties are expressed in a tissue-specific manner. There may also be different protein products produced from one gene, by alternative splicing of RNA transcripts. The enzyme hormone-sensitive lipase will be discussed in this book mainly as a component of the pathway for hydrolysis of triacylglycerols in adipose tissue (Section 5.2.2.2, Figure  5.10). However, alternative splicing of exons gives rise to a variety of mRNA and protein sizes and sequences in adipose tissue, pancreatic β-cells, ovaries, and testes. In testes, hormone-sensitive lipase is involved more with steroid metabolism – it acts as a cholesteryl esterase, necessary for generation of testosterone from cholesterol and provision of sterols for spermatozoa formation. 

Tissue-specific protein expression is a function of epigenetic modification – all cells in one individual have the same DNA sequence, but modifications to the DNA structure change expression. The bases in the DNA may be chemically altered (typically by methylation of cytosine bases), or the proteins that wrap the DNA up into chromosomes, the histones, may be altered, and such changes will affect the expression of genes (i.e. their transcription – the reading off into mRNA). Histones are modified most commonly by acetylation (using acetyl-CoA), phosphorylation (using ATP) or addition of other groups. These acetyl ‘markings’ may also be removed in the process of histone deacetylation by a histone deacetylase enzyme (HDAC). Most of the epigenetic ‘markings’ are removed at meiosis (cell division to form a gamete) so that a new organism begins, at least approximately, ‘from scratch,’ but some are undoubtedly carried over from one generation to another. 

## 2.2.2 Movement of substances across membranes

Tissues vary in the means and the ease by which nutrients cross cell membranes, reflecting differences in specific protein expression between the tissues. 

Cell membranes, as we saw in Chapter 1, are composed of bilayers of phospholipid molecules (Figure 1.5). Molecules crossing this membrane must pass through both the hydrophilic, polar faces, and the hydrophobic interior. In general, this presents less of a problem for non-polar hydrophobic molecules, and many hydrophobic drugs are able to enter cells readily. It was at one time assumed that all hydrophobic molecules enter cells by simple diffusion, but this is now clearly not so: more and more specific transporter proteins are being described. This should not surprise us, because the movement of molecules in and out of cells by simple diffusion is, by its very nature, not a process over which any control can be exerted. On the other hand, if the movement occurs by a carrier-mediated process, then immediately there are possibilities for regulation: some cells may have more carriers than others, or the number or activity of the carriers may be altered by hormones. General characteristics of the movement of substances across membranes are discussed in Box 2.1. 

## Box 2.1 Movement of molecules across membranes

The cell membrane, and membranes within cells, are formed from a phospholipid bilayer (Figure 1.5). Most biological molecules, especially polar molecules and ions, will not diffuse freely across such a membrane. Instead, there are specific proteins embedded in the membranes, which ‘transport’ molecules and ions from one side to the other. This box describes some general properties of the movement of molecules across membranes. 

A substance will cross a membrane to move from one solution to another if (i) the membrane is permeable to the substance, and (ii) there is a concentration gradient in the appropriate direction: that is, a substance will move from a region of high concentration to a region of lower concentration. (In reality, there will be movement in both directions because of random molecular movements, but the net movement will be down the concentration gradient.) 

There are three major means by which such movement may occur: 

•	 Free diffusion, unassisted movement by diffusion, is brought about simply by the overall effect of random molecular motions. 

•	 Facilitated diffusion (carrier-mediated diffusion) is movement assisted by a specific transporter protein. 

•	 Active transport, in which substances may move up a concentration gradient – that is, from a lower concentration to a higher one. This can only be brought about by the supply of energy, either electrical (charge on the membrane) or chemical; for instance, the Na+ -K+ -ATPase is a membrane protein that hydrolyses ATP and pumps sodium ions out of cells against a strong concentration gradient, and potassium ions in – also against a strong concentration gradient. 

The two forms of movement down concentration gradients – free diffusion and facilitated diffusion – can be distinguished by their kinetic characteristics. Since the movement of substances by a transporter protein is similar in many ways to enzyme catalysis, it has similar characteristics: there is a characteristic affinity of the transporter protein for the molecule, and a maximum rate of transfer of the molecule which will depend, in turn, on the intrinsic ‘rate of action’ of the protein, and the number of transporters available in the membrane. Thus, if we measure the rate of transport at differing concentrations of the substrate to be transported, we will find a hyperbolic curve similar to a Michaelis–Menten plot of enzyme action. [This is the simplest form of enzyme kinetics, resulting in a hyperbolic curve of reaction velocity plotted against substrate concentration. See Box 2.2 for further use of Michaelis-Menten kinetics.] On the other hand, if transport occurs by free diffusion, there is no limitation to the rate, and it will be simply proportional to the concentration gradient of the substrate across the membrane. These are illustrated in Figure 2.1.1. 

![image](/assets/images/human_metabolism_images/73749e10b2b48c523bfc6025c7a825bd.jpg)



Figure 2.1.1


The presence of active transport will usually be identified by its need for energy. Blocking of ATP synthesis (for instance, by inhibition of oxidative phosphorylation) will usually reduce or abolish such transport. 

## 2.2.2.1 Glucose transport

A particularly important mechanism from the point of view of energy metabolism is the way that glucose crosses cell membranes. There are two families of glucose transporters, each family comprising several homologous proteins encoded by different genes and having different kinetic properties. These are summarised in Box 2.2. The ‘GLUT’ family are all facilitative (passive) transporters, whereas members of the sodium-glucose cotransporter (SGLT) family are active glucose transporters. SGLT1, expressed in the small intestine, needs to be able to move glucose from a low to high concentration, to ensure virtually complete absorption from the intestinal lumen. This is achieved by linking glucose transport to that of sodium: sodium moves down a strong concentration gradient, carrying glucose with it up a concentration gradient. This process is illustrated in Figure 2.1. SGLT1 to SGLT3 are expressed in the renal tubule. SGLT2 in particular is involved in reabsorption of glucose filtered at the glomerulus (this process will be described further in Section 5.5.2) and is a target for drugs now being used in type 2 diabetes, that inhibit its activity, resulting in loss of glucose in the urine (Chapter 12, Table 12.3). The function of SGLT3 is unclear. It does not transport glucose but does transport ions (Na+ and H+ ) in a glucose-stimulated manner, suggesting that it is a glucose sensor. 

![image](/assets/images/human_metabolism_images/c5d6d24c51eec7f8fd4dc32acf940c3a.jpg)



Figure 2.1 Sodium-linked active transport. By co-transport with Na+ ions, substance X may move up a concentration gradient. The Na+ ions move down a gradient maintained by the activity of the Na+ -K+ -linked ATPase or ‘sodium pump,’ which uses energy derived from ATP to pump Na+ ions out of, and K+ ions into the cell, both against concentration gradients. Substance X may be glucose (if the transporter belongs to the SGLT family) or an amino acid. The linking of transport down, and transport against a concentration gradient is known as secondary active transport.


## Box 2.2 Transport of glucose across cell membranes

It has long been known that glucose enters cells by carrier-mediated diffusion (facilitated diffusion) rather than by free diffusion across the cell membrane (see Box 2.1 for definitions). In recent years the genes for the specific glucose transporter molecules have been cloned and sequenced; the transporters have been expressed in cell lines and their characteristics studied. There are two families of glucose transporters. The more widespread family consists of passive transporters, allowing the movement of glucose across cell membranes only down a concentration gradient. They are called GLUTn (GLUcose Transporter), where n is a number distinguishing different members. There are 14 members of this family but only five (shown in Table 2.2.1) have wellcharacterised function. The other family consists of active transporters, enabling glucose to move up a concentration gradient (i.e. it may be concentrated by the transporter) because sodium ions, co-transported with the glucose, are moving down a concentration gradient (Figure 2.1). These are known as the Sodium-GLucose coTransporter family, 

SGLTn. The expression of all these transporters is tissue specific, and their properties are an integral part of the regulation of glucose metabolism in the particular tissue. 

The effect which the characteristics of the glucose transporter may have on the rate of glucose entry into cells is illustrated in Figure 2.2.1. (This refers to facilitated diffusion, i.e. passive transport, only). 

The term $K _ { \mathfrak { m } }$ (Michaelis–Menten constant) is often used in this context, borrowed from enzyme kinetics (see note in Box 2.1). An alternative terminology relates to affinity. Imagine that at a very high concentration of substrate (glucose outside the cell), there will be a certain maximum rate of glucose transport (the ‘plateau’: you can see this on Figure 2.2.1 for the $K _ { \mathrm { m } } = 1 . 6 \ : \mathrm { m m o l } \ : \Gamma ^ { 1 }$ transporter). The $K _ { \mathfrak { m } }$ is the substrate concentration at which half this rate is achieved. With a glucose transporter whose $K _ { \mathfrak { m } }$ for glucose entry is 1.6 mmol l−1 (e.g. GLUT3), the rate of glucose uptake is relatively independent of the extracellular glucose concentration over the normal, physiological range of plasma glucose 


Table 2.2.1


<table><tr><td>Protein name</td><td>Gene name</td><td>Tissue distribution</td><td>Approximate <eq>K_m</eq> (for inward transport of glucose or a glucose analogue)</td><td>Size (no. of amino acids)</td><td>Important features</td></tr><tr><td>GLUT1</td><td>SLC2A1</td><td>Erythrocytes, foetal tissue, placenta, brain blood vessels, and glial cells</td><td>5–7 mmol l-1</td><td>492</td><td></td></tr><tr><td>GLUT2</td><td>SLC2A2</td><td>Liver, kidney, intestine, pancreatic β-cell</td><td>High (7–20 mmol l-1)</td><td>524</td><td>High <eq>K_m</eq> allows glucose to ‘equilibrate’ across the membrane</td></tr><tr><td>GLUT3</td><td>SLC2A3</td><td>Brain (neuronal cells)</td><td>Low (1.6 mmol l-1)</td><td>496</td><td>Low <eq>K_m</eq> allows relatively constant rate of glucose uptake independent of extracellular concentration over the normal range</td></tr><tr><td>GLUT4</td><td>SLC2A4</td><td>Muscle, adipose tissue</td><td>5 mmol l-1</td><td>509</td><td>The ‘insulin regulatable’ glucose transporter: see Figure 2.2</td></tr><tr><td>GLUT5</td><td>SLC2A5</td><td>Jejunum</td><td>5 mmol l-1 for fructose</td><td>501</td><td>Probably responsible for fructose uptake from intestine</td></tr><tr><td>SGLT1</td><td>SLC5A1</td><td>Duodenum, jejunum, renal tubules</td><td></td><td>664</td><td>The sodium-glucose cotransporter of the small intestine (not part of the same family as GLUT1–5). Co-transports 1 mol sugar with 2 mol Na+</td></tr><tr><td>SGLT2</td><td>SLC5A2</td><td>Renal tubules</td><td></td><td>672</td><td>Homologous to SGLT1; SGLT2 has high capacity and low affinity (high <eq>K_m</eq> for glucose). Co-transports 1 mol sugar with 1 mol Na+</td></tr><tr><td>SGLT3</td><td>SLC5A4</td><td>Widespread including small intestine, renal tubules, and muscle</td><td></td><td>659</td><td>SGLT3 appears to be a glucose-sensitive ion channel rather than a glucose transporter, and may act as a glucose sensor</td></tr></table>

## Box 2.2 Transport of glucose across cell membranes (continued)

![image](/assets/images/human_metabolism_images/639a720831b4c815ea688fadaf42dd3f.jpg)



Figure 2.2.1


concentrations (well above the $K _ { \mathfrak { m } } )$ . This would be appropriate in, for instance, the brain, where the rate of glucose uptake needs to be constant despite cycles of feeding and fasting. With a $K _ { \mathfrak { m } }$ for glucose entry of 20 mmol $| ^ { - 1 }$ (e.g. GLUT2), the rate of glucose entry is almost proportional to the extracellular glucose concentration (the higher the external concentration, the greater the rate of entry). Alternatively, we may describe GLUT2 as having low affinity for glucose – it is sometimes called a lowaffinity transporter. We could imagine that because the affinity for glucose is low, a high concentration is needed to produce maximal transport. Conversely, GLUT3 would be a high-affinity transporter (low concentrations produce high transport rates). 

The lines on Figure 2.2.1 are plotted assuming Michaelis–Menten kinetics. This is only true if glucose within the cells is removed as fast as it enters. Therefore, the enzyme responsible for phosphorylation of glucose (hexokinase or glucokinase) must have similar characteristics to (or a greater capacity than) the glucose transporter in order for these kinetics to be expressed. The removal of glucose 6-phosphate must also occur at approximately the same rate as glucose enters the cell; the pathways of glucose metabolism are regulated hormonally so as to coordinate all these events (Figure 5.2). 

The terminology is that GLUT refers to the proteins. These are related, and all have 12 membrane-spanning regions. The genes encoding them are called SLC2A1 (the gene for GLUT1, member no. 1 of the SoLute Carrier family 2A), SLC2A2 (for GLUT2), and so on. The genes for the SGLT proteins belong to the SoLute Carrier family 5A. This is explained further in Box 2.3. 

GLUT4 has special characteristics relevant for metabolic regulation. Many years ago it was recognised that when insulin stimulates glucose uptake by muscle preparations, it appears to do so by increasing the maximal rate of uptake (the $V _ { \mathrm { m a x } } )$ rather than by changing the $K _ { \mathrm { m } } .$ . There is a large cellular store of the transporter GLUT4, sequestered in membrane vesicles within the cell. When insulin binds to its receptor, these vesicles move to, and become incorporated in, the cell membrane and, therefore, the amount of GLUT4 available for glucose transport into the cell is increased. When insulin action decreases, these transporters recycle into intracellular vesicles (Figure 2.2). 

![image](/assets/images/human_metabolism_images/8b76b4160bf25c30eb7528e30a289ddc.jpg)



Figure 2.2 GLUT4 recruitment to the cell membrane. There is an intracellular pool of GLUT4 in membranous vesicles that can translocate to the cell membrane when insulin binds to its receptor. When the insulin signal is withdrawn, the GLUT4 proteins return to their intracellular pool. A similar mechanism may operate for GLUT2 translocation in the small intestine, stimulated by the presence of glucose in the intestinal lumen: see Section 4.3.1.


## Box 2.3 Classification of solute transporters

The GLUT and SGLT glucose transporters described in Box 2.2, the amino acid transporters in Table 2.2, and some of the fatty acid transporters listed in Table 2.3 belong to a large group of solute transporters. Nomenclature of this large group may be confusing as common names (e.g. GLUT4) are seen alongside systematic names, and gene names often look very different from protein names. Here we try to explain the different terminologies. 

Solute transporters are integral membrane proteins which contain hydrophobic transmembrane regions and hydrophilic intra- and extra-cellular loops. They may be monomers or comprise several subunits. They occur in distinct families. These families are defined by their function, and there is little or no sequence homology (similarity) between families. Members of a particular family are subdivided into subfamilies and often have multiple, related members – isoforms – with particular tissue distribution (the GLUTs, described in Box 2.2, are a good example). Subfamily members (isoforms) have >20% sequence homology, and hence have an evolutionary connection with other members. Classification is challenging (and ongoing), and several systems exist; for humans they may be classified according to their gene, using the HUGO (Human Genome Organisation) Gene Nomenclature (HGNC); or by their protein product according to the web-accessible Transporter Classification Database (TCDB), http://www.tcdb.org/. The HGNC classification is based on the following proforma: 

SLCnXm 

where SCL = SoLute Carrier family 

n = family 

X = subfamily 

m = member (isoform) 

Listed below are the main solute carrier families responsible for transport of carbohydrate, amino acid, and lipid substrates. 


Box 2.3 Classification of solute transporters (continued)


<table><tr><td>Family (and gene) name</td><td>Transporter type</td><td>Functional (or protein) nomenclature</td></tr><tr><td>SLC1A 1-7</td><td>High affinity glutamate and neutral aa transporter</td><td>ASCT; EAAT1-5</td></tr><tr><td>SLC2A 1-14</td><td>Facilitative glucose transporter</td><td>GLUT</td></tr><tr><td>SLC3A 1-2</td><td>Heavy subunit of heterodimeric aa transporter</td><td></td></tr><tr><td>SLC5A 1-12</td><td>Sodium-glucose co-transporter</td><td>SGLT</td></tr><tr><td>SLC6A 1-20</td><td>aa transporters – various, large subfamilya</td><td>PROT, AA0, AA0,+, B0</td></tr><tr><td>SLC7A 1-4</td><td>Cationic aa transporter</td><td>CAT</td></tr><tr><td>SLC7A 5-14</td><td>L-type aa transporter</td><td>LAT(L)</td></tr><tr><td>SLC16A 1-14</td><td>Monocarboxylate (including aromatic aa) transporter</td><td>T, TAT1</td></tr><tr><td>SLC17A 1-9</td><td>Vesicular glutamate transporter</td><td>VGLUT</td></tr><tr><td>SLC27A 1-6</td><td>Fatty acid transport proteins</td><td>FATP</td></tr><tr><td>SLC32A 1</td><td>Vesicular inhibitory aa transporter</td><td>VIAAT</td></tr><tr><td>SLC36A 1-4</td><td>H+-coupled aa transporter</td><td></td></tr><tr><td>SLC38A 1-11</td><td>System A &amp; N sodium-coupled neutral aa transporter</td><td>SNAT (A, N(m))</td></tr><tr><td>SLC43A 1-3</td><td>Sodium-independent system L-like aa transporter</td><td>LAT</td></tr></table>


aa, amino acid; BCAA, branched-chain amino acid. 



Glucose transporters shown in blue. 



Lipid transporters shown in green. 



Amino acid transporters shown in red. 



Note that amino acids are transported as groups according to their chemical characteristics (neutral, cationic etc.), and historically amino acid transporters were grouped into ‘systems’ according to these characteristics (Table 2.2). 



a Large family including glycine, proline, cationic, and neutral amino acid transporters. 


## 2.2.2.2 Amino acids

The concentrations of most amino acids are considerably higher inside cells than outside: this is illustrated in Table 2.1 for some amino acids in skeletal muscle. This implies the existence of active transporters to move amino acids into the cells up a concentration gradient. In fact, like glucose in the small intestine, amino acids are mostly actively transported by sodium-linked carriers. Again, therefore, energy is required to pump the sodium ions out and maintain their concentration gradient. There are many amino acid transporters, expressed in a tissue-specific manner. Each has a fairly broad specificity and transports a number of amino acids. They are described further in Table 2.2. 

## Table 2.1 Free amino acids in skeletal muscle.

Amino acids are found free (i.e. not as constituents of proteins) both in plasma and in the intracellular water of tissues. They may be present at considerably higher concentrations inside cells than out, reflecting the presence of active transport mechanisms for their entry into cells. The best data available are for skeletal muscle since small samples can be taken from human subjects with a special needle with a cutting edge, but data for liver are broadly similar. The sample (biopsy) is then frozen rapidly in liquid nitrogen to prevent further metabolism, and the amino acids are analysed. A correction is made for the amount of amino acid present in extracellular fluid (using the measurement of Cl− ions, which are present mainly in the extracellular fluid). Some typical results are given below: 

<table><tr><td>Amino acid</td><td>Plasma concentration (mmol l-1)</td><td>Intracellular concentration (mmol l-1)</td><td>Intracellular to extracellular concentration ratio</td></tr><tr><td>Glutamine</td><td>0.57</td><td>19.5</td><td>34:1</td></tr><tr><td>Glutamic acid</td><td>0.06</td><td>4.4</td><td>73:1</td></tr><tr><td>Alanine</td><td>0.33</td><td>2.3</td><td>7:1</td></tr><tr><td>Serine</td><td>0.12</td><td>0.98</td><td>7:1</td></tr><tr><td>Asparagine</td><td>0.05</td><td>0.47</td><td>10:1</td></tr></table>

One kilogram of skeletal muscle contains about 650 g of intracellular water. Skeletal muscle represents about 40% of the body weight. In the whole body, the intracellular pool of free amino acids in muscle will be about 80 g, of which glutamine, glutamic acid, and alanine contribute almost 80%. Based on Bergström, J., Fürst, P., Norée, L.-O., & Vinnars, E. (1974). J Appl Physiol, 36: 693–697. 


Table 2.2 Some amino acid transporters.


<table><tr><td>Transporter/family</td><td>Gene family</td><td><eq>Na^{+}</eq> dependence</td><td>Tissues</td><td>Amino acids</td></tr><tr><td>A</td><td>SLC38A</td><td>Yes</td><td>Widespread</td><td>Ala, Ser, Gln</td></tr><tr><td>ASC</td><td>SLC1A</td><td>Yes</td><td>Widespread</td><td>Ala, Ser, Cys</td></tr><tr><td><eq>B^{0}</eq></td><td>SLC6A</td><td>Yes</td><td>Kidney, intestine</td><td>Neutral amino acids</td></tr><tr><td>L</td><td>SLC7A</td><td>No</td><td>Widespread</td><td>BCAA, aromatics</td></tr><tr><td>T</td><td>SLC16A</td><td>No</td><td>Kidney, intestine, muscle</td><td>Aromatics</td></tr><tr><td><eq>N^{(m)}</eq></td><td>SLC38A</td><td>Yes</td><td>Liver,<eq>^{(m)}</eq> in muscle</td><td>Gln, Asn, His</td></tr></table>

BCAA, branched-chain amino acids; Aromatics, phenylalanine, tyrosine, tryptophan, histidine. 

Many different transporters exist (see also Box 2.3). The amino acid transporters are often referred to as systems (e.g. system A transporters), because they were discovered as functional activities that could transport more than one amino acid. These systems mostly comprise a number of individual, related transporters. There are also specific groups of transporters involved in moving amino acids across epithelial cells (i.e. for intestinal uptake and reabsorption in the kidney). Further detail on solute transporters can be found in Box 2.3. 

## 2.2.2.3 Fatty acids

Fatty acids reaching a tissue in the circulation cross the endothelial cell lining and enter cells (e.g. liver, skeletal muscle, cardiac muscle, adipose tissue) down a concentration gradient, which is generated by avid binding to specific fatty acid binding proteins (FABPs) within the cells. The gradient is maintained because the fatty acids are utilised for further metabolism within the cells. The first step in this process is always esterification to coenzyme A to form acyl-CoA thioesters. This step is called activation. It requires ATP and releases AMP and pyrophosphate, $\mathrm { P P _ { i } } .$ The release of ${ \mathrm { P P } } _ { \mathrm { i } } ,$ which is rapidly hydrolysed to $\mathrm { { P _ { i } , } }$ makes this step essentially irreversible, so ‘trapping’ the fatty acid within the cell. It has been estimated that in muscle the gradient is from (around) $5 0 0 \mu \mathrm { m o l } \mathrm { l } ^ { - 1 }$ in plasma to (around) 100  μmol $1 ^ { - 1 }$ (cardiac muscle) or 30 μmol $1 ^ { - 1 }$ (skeletal muscle) within the tissue. However, this is not an entirely accurate picture. Most of the non-esterified fatty acids in plasma are bound to albumin, and the concentration actually free in solution, and available to enter cells, is much lower, maybe around 5–10 nmol l−1 . Hence, there may also be a need for active transport mechanisms. 

Fatty acids cross cell membranes both by passive diffusion and by facilitated transport. The former involves a movement usually called ‘flipflop,’ in which the polar carboxyl group enters the polar face of the membrane, the hydrophobic fatty tail flips into the lipid bilayer, and then a reversal takes it out of the other side. The rate at which this could happen (based on physicochemical calculations and measurements in artificial membranes) seems just about sufficient to account for observed rates of fatty acid utilisation. However, as mentioned above, there are also specific fatty acid transport proteins in the cell membrane. It is probable that fatty acids enter cells by a combination of routes, partly passive diffusion, partly facilitated (some of which may be active). Some fatty acid transporters are listed in Table 2.3. There is increasing evidence that activation of fatty acids (the action of acyl-CoA synthase) is intimately linked with the action of the FATP proteins; in fact the FATP proteins and the very-long chain acyl-CoA synthases may be identical (although very-long chain fatty acids, in this case >22 carbons, are a small proportion of total fatty acids). Note that this would confer all the properties of active transport (since ATP would be used and would create the ‘drive’ to bring fatty acids into the cells even against an apparent concentration gradient). For most fatty acids, it is likely that FATP proteins work in conjunction with acyl-CoA synthase. 

In adipose tissue, fatty acids also need to leave the fat cell (adipocyte) during fat mobilisation. In this case the concentration gradient is reversed because lipases within the adipocyte liberate fatty acids at a high rate from stored triacylglycerol. 

Fatty acid transport across cell membranes is regulated on a short-term basis. Several of the fatty acid transporters listed in Table 2.3 (CD36/FAT, FATP1 and 4, fatty acid binding protein (plasma membrane) (FABPpm)) may be recruited to the cell membrane from an intracellular pool in skeletal muscle when fatty acid utilisation is high during exercise, in a similar manner to GLUT4 (Figure 2.2). Insulin can also bring about a similar translocation. FATP1 also seems to be subject to regulation by insulin-stimulated translocation in adipocytes, and therefore plays a role in fatty acid uptake in the fed state. 

## 2.2.2.4 Cholesterol

It has long been assumed that cholesterol, like fatty acids, can cross membranes by a flip-flop mechanism. Recent discoveries show this to be an oversimplification. The diet contains many plant- and fish-derived substances that are chemically very similar to cholesterol, some of which are termed sitosterols or phytosterols. The absorption of cholesterol from the small intestine is relatively efficient (around 50%), but the amount of the chemically-similar sitosterols that enters the plasma is very small. Thus, absorption must be very selective, and that immediately suggests a carrier mechanism. There is a rare inherited condition, sitosterolaemia, in which high levels of sitosterols are found in the plasma, and this results in atherosclerosis just as when cholesterol levels are high. Tracing the gene responsible led to the identification of two cholesterol transporters known as ABC-G5 and ABC-G8, where ABC refers to the presence in 


Table 2.3 Cell membrane fatty acid transporters.


<table><tr><td></td><td>Gene</td><td>Tissue distribution</td><td>Relative molecular mass</td><td>Comments</td></tr><tr><td>Fatty acid translocase (FAT)</td><td>CD36</td><td>White adipose tissue, myocardium, skeletal muscle, small intestine</td><td>88 kDa</td><td>Also known as CD36 and a member of the family of ‘scavenger receptors.’ Some people are deficient in CD36 and appear to have abnormalities of fat metabolism, especially in the heart.</td></tr><tr><td>Fatty acid transport protein (FATP)</td><td>SLC27A1 – 6</td><td>FATP1 (the best characterised) mainly skeletal muscle, adipose tissue, small intestine, brain; other members (especially FATP5) in liver</td><td>63 kDa</td><td>There is a family of at least six related proteins in humans, known as FATP1 to FATP6; some members have since been shown to have acyl-CoA synthase activity (see below) (but possibly only for very-long chain fatty acids, &gt;22 carbons).</td></tr><tr><td>Fatty acid binding protein (plasma membrane) (FABPpm)</td><td>GOT2</td><td>Widespread</td><td>43 kDa</td><td>The same protein appears to have fatty acid binding (and possibly transport) activity, and activity as a glutamic-oxaloacetic transaminase (hence gene name). Related to the family of fatty acid binding proteins but restricted to the plasma membrane; may cooperate with other proteins in fatty acid uptake.</td></tr><tr><td>Acyl-CoA synthase</td><td>ACSL1-6</td><td>Widespread</td><td>70–80 kDa (different family members)</td><td>It has been suggested that acyl-CoA synthase (which esterifies fatty acids with CoA) is intimately involved in the transport of fatty acids into cells. It is associated with membranes. Some members of FATP family (see above) have this enzymatic activity.</td></tr><tr><td>Caveolins and cavins, e.g. caveolin-1</td><td>CAV1</td><td>Widespread; high in adipose tissue, lung, placenta</td><td>22 kDa</td><td>Caveolins are involved in formation of caveolae, cell membrane compartments where the fatty acid transporters listed above tend to concentrate. Caveolin-1 itself binds, and may transport, long-chain fatty acids.</td></tr></table>


Further detail on solute transporters can be found in Box 2.3. 


the protein of a motif called an ATP-Binding Cassette. In addition, a related transporter, ABC-A1, was identified through a genetic disorder of lipid metabolism (to be discussed later, in Section 10.2.3.1 and Figure 10.5). All these proteins, ABC-A1, ABC-G5, and ABC-G8, are expressed in enterocytes (small intestinal absorptive cells). ABC-A1 is also expressed in other tissues, where it plays a crucial role in facilitating the movement of excess cholesterol from cells onto high-density lipoprotein (HDL) particles (discussed later, Figure 10.5). An unrelated protein was discovered through identification of the gene responsible for a rare disorder of lipid storage, Niemann-Pick disease (type C). This protein is called Niemann-Pick C1-like protein 1, NPC1L1. It also turns out to be a cholesterol transporter. The way in which these transporters interact to bring about specific absorption of cholesterol from the intestine will be covered in Chapter 4 (Section 4.3.3, Figure 4.9). 

## 2.2.2.5 Small polar molecules

Those small molecules involved in metabolism, which are charged at normal cellular conditions, cannot readily cross a lipid bilayer. This would include lactate and pyruvate, and the ketone bodies, acetoacetate and 3-hydroxybutyrate. These molecules move by facilitated diffusion, achieved with one of a family of proteins known as monocarboxylate transporters (gene family SLC16). Members of this family have 12 membranespanning domains. They are expressed in a tissue-specific manner, but little is known of their potential as regulators of metabolism. In some tissues it is clear that they are expressed in high amounts and are likely to allow equilibration of molecules across the cell membrane. 

## 2.2.2.6 Water and glycerol

As we saw in Chapter 1, water itself is a polar molecule. Water will not readily cross cell membranes by diffusion. In 1991 the first specific ‘water channel,’ or aquaporin, was discovered. There is a family of aquaporins, with somewhat different properties, expressed on a tissue-specific basis. These channels are abundant in cell membranes. It is not clear, however, that they play much of a role in energy metabolism. The activity of some aquaporins is regulated by translocation to the cell membrane, as described in Figure 2.2 for GLUT4, and this is especially important in the kidney where such movement regulates the concentration of the urine (hence it regulates an important energy-consuming function). Other closely related proteins (the aquaglyceroporins) are carriers for glycerol, a molecule with similar physicochemical properties to water. Again, they are expressed in a tissue-specific manner. The aquaglyceroporins are important in adipocyte function, since glycerol is released from the adipocyte during the process of fat mobilisation (Section 5.2.2.2), and in the liver, which removes glycerol from the blood for use as a substrate for glucose synthesis (Box 5.2). They are also important in maintaining the barrier function of the skin, showing that glycerol is an important component of skin function (it is a major component of most hand creams). 

## 2.3 Rapid changes in metabolic flux and how they are achieved

## 2.3.1 Rapid and longer-term changes in metabolic flux

A sprinter starting from the blocks, or a high jumper at take-off, has a very sudden need to supply energy for muscular contraction, and metabolic flux through the relevant pathways must change greatly within a fraction of a second. Even after eating a meal there are rapid changes in metabolic flux through certain pathways (as we shall see in later chapters). Glucose uptake into skeletal muscles increases, and the release of fatty acids stored in adipose tissue decreases, within less than one hour after eating a normal meal. (Even that reflects the relatively slow entry of glucose from the small intestine into the bloodstream: if glucose is injected directly into a vein, then these changes happen correspondingly more rapidly.) Rapid changes in metabolic flux such as these usually reflect changes in the activity of key enzymes or other proteins brought about by a number of mechanisms. An overview of these is given in Table 2.4 and examples will occur throughout the book. 

Other changes need to take place more gradually, perhaps over a period of hours, days, or longer, for instance in response to a change in diet or activity pattern, or even as a baby develops into a toddler or a young person into an adult. Such gradual changes usually involve changes in the amounts of enzymes (or other proteins) present. These mechanisms for regulating metabolic flux over longer periods are discussed in the next section. 

There is no absolute division between ‘rapid’ and ‘longer-term’ changes. Often enzymes that are 


Table 2.4 Common mechanisms for rapid alteration of cellular metabolic flux.


<table><tr><td></td><td>Examples</td><td>Comments</td></tr><tr><td>Covalent modification:phosphorylation ordephosphorylation of serine,threonine or tyrosine residues</td><td>Glycogen phosphorylase(activated by phosphorylation)(see Box 3.4 and Box 5.1).Glycogen synthase (activated bydephosphorylation) (see Box 5.1).Hormone-sensitive lipase(activated by phosphorylation) (seeBox 3.4 and Section 5.2.2.2).</td><td>Brought about by specificenzymes (kinases,phosphatases) that maythemselves be controlled inthe same way. Often involvedin hormone action – Chapter3. (De)phosphorylationbrings about a conformationchange – see Box 2.4.</td></tr><tr><td>Allosteric</td><td>Activation ofphosphofructokinase-1 byfructose 2,6-bisphosphate (seeBox 5.2).Inhibition of fructose-1,6-bisphosphatase by fructose2,6-bisphosphate (see Box 5.2).Inhibition of carnitine-palmitoyltransferase-1 by malonyl-CoA(see Figure 5.4).</td><td>Binding of a small moleculeat a site distinct from thecatalytic site alters proteinconformation and changesactivity (see Box 2.4). Thisis the typical mechanism for‘feed-forward’ and ‘productinhibition’ discussed in thetext.</td></tr><tr><td>Competitive or uncompetitiveinhibition</td><td>There are possibleexamples in: serinebiosynthesis – phosphoserinephosphatase is uncompetitivelyinhibited by its product,serine; and in ketone bodysynthesis – acetyl-CoA acetyltransferase is competitivelyinhibited by its product,acetoacetyl-CoA.</td><td>Inhibitor competes withnormal substrate for binding toenzyme active site. Commonfor xenobiotics (drugs) butapparently less so as anatural means of controllingflux. Uncompetitive inhibitorsbind the enzyme-substratecomplex and decrease <eq>V_{max}</eq>and <eq>K_{m}</eq>; non-competitiveinhibitors are similar butcan bind the enzyme in theabsence of substrate.</td></tr><tr><td>Interaction with another protein</td><td>Glucokinase regulatory protein(see Box 5.2).</td><td>Also a common mechanismin ‘signal chains’ for hormoneaction (see Chapter 3).</td></tr><tr><td>Translocation</td><td>GLUT4 moves from intracellularstore to cell membrane inresponse to insulin (see Section2.2.2.1 and Figure 2.2).Hormone-sensitive lipasetranslocates to lipid droplet inadipocyte on phosphorylation (seeSection 5.2.2.2 and Figure 5.10).</td><td></td></tr></table>

regulated in a certain way in the short term – for instance, activated by phosphorylation – are also increased in amount by increased gene transcription if the situation persists for longer. Nevertheless, the mechanisms are distinct. These various mechanisms for achieving changes in substrate flux are illustrated in Figure 2.3. 

Many means of achieving rapid changes in flux depend upon a conformational change in the enzyme concerned: this is discussed in Box 2.4. 

![image](/assets/images/human_metabolism_images/1aa8a1a31779842ebe1751647bc3262c.jpg)



Figure 2.3 Different methods for achieving changes in metabolic flux within a cell. A hypothetical metabolic pathway is shown. Enz 1, Enz 2, and so on are the enzymes converting substrate A to substrate B, B to C, and so on. For many pathways, important control points are often the first step, and also the first step after a branch point (marked *). Many metabolic pathways are subject to control by metabolites related to that pathway. The precursor metabolite may activate steps in the pathway (sometimes called feed-forward); intermediates in the pathway may regulate flux through the pathway; or the product(s) of the pathway may suppress metabolic flux (usually called product inhibition). These changes are usually brought about by allosteric regulation: see Box 2.4. Regulation of the amount of enzyme present mostly involves changes in gene expression, described in Section 2.4 and Figure 2.4. Regulation by hormones is described in Chapter 3 and in more detail in Chapter 6. See the text for a discussion of the significance of substrate cycling (as with enzymes 2A and 2B).


## Box 2.4 Protein conformation and metabolic regulation

All proteins, including enzymes, are synthesised initially as peptide chains. The sequence of amino acids is known as the primary structure. The final primary structure may consist of more than one peptide chain covalently linked together – see for instance the structure of insulin, Section 6.2.1.2, Figure 6.3. These peptide chains will then adopt various layers of additional conformation according to the nature of the amino acid residue side-chains. Some amino acid sequences will tend to produce regular structures such as α-helix and β-sheet: these are known as secondary structures, a term which refers to the relationship adjacent amino acids have with each other. Beyond that, the entire protein may fold into a 3-dimensional shape which will relate intimately to its function – the tertiary structure, a term which refers to the relationship which distant amino acids have with each other. 

Protein conformation is not rigid. It may be altered, and in the case of enzymes, this can underlie changes in enzyme activity (positively or negatively). Similarly, transporters may change their conformation when the molecule to be transported is bound, and this may lead to transport across a membrane, for instance. Here we will discuss two particular types of conformational change that are common to many aspects of metabolic regulation. 

## Allostery

The active site of most enzymes consists of a small number of amino acid residues, often widely separated in the primary structure but brought close to each other by the tertiary structure. Any change to this tertiary structure may greatly alter the relative positions of these critical amino acid residues. This may be brought about by another molecule binding to the enzyme at a specific (allosteric) site that is distinct from the active site. This is called allostery and brings about allosteric regulation of enzyme activity. The allosteric activator may bear no structural resemblance to the enzyme’s substrate; allostery comes from the Greek allos (αλλος), meaning ‘other,’ and stereos (στερες), referring to shape. An example is phosphofructokinase, an enzyme in the pathway of glycolysis (Section 1.3.2.1 and Box 5.2). This enzyme has many allosteric regulators. It is inhibited by high levels of ATP, so controlling flow through glycolysis as needed for energy generation. ATP binds to a so-called allosteric site, distinct from the active site, and alters the conformation of the active site (in this case, so it binds less substrate, fructose 6-phosphate). The alteration in conformation may be described as a transition between a ‘tense’ (T) state and a ‘relaxed’ (R) state, where the R state is the active state. 

Hormone receptors (described more in Chapter 6) also work by allostery. For instance, the insulin receptor sits in the cell membrane. Insulin, outside the cell, binds to the extracellular domain. This brings about a change in conformation which leads to the intracellular domain exhibiting tyrosine kinase activity and initiating the reactions that control metabolism within the cell (see below). 

## Covalent modification, especially reversible phosphorylation

The activity of many enzymes is regulated rapidly by phosphorylation of serine, threonine, and tyrosine residues (all of which have a hydroxyl (⎯OH) group on their ‘R’ group), and conversely by their dephosphorylation. In general, tyrosine phosphorylation is the mechanism involved in regulation of hormone signalling (see Boxes 3.3 and 3.4), whereas most ‘metabolic’ enzymes are regulated by serine or threonine phosphorylation. The residues involved are specific (and may be just one, or a small number, of all the tyrosine, serine or threonine residues in the enzyme). Phosphorylation, using ATP, is brought about by an enzyme known as a kinase, dephosphorylation by a phosphatase. These kinases and phosphatases may be quite specific, or they may have broad specificity. PKA is a kinase that is itself activated by allosteric regulation, by the binding of cyclic AMP (cAMP, described further in Box 3.3): in its active form, it phosphorylates a number of enzymes important in metabolism, including phosphorylase kinase (the enzyme in turn responsible for phosphorylation and activation of glycogen phosphorylase) and hormone-sensitive lipase (a key enzyme in fat mobilisation) – see Box 3.4 for descriptions of these. 

In general, phosphorylation of an enzyme brings about a ‘catabolic’ or fuel-mobilising reaction, whereas dephosphorylation inhibits fuel mobilisation and activates fuel storage pathways; there are good examples in the regulation of glycogen synthesis and degradation (Chapter 5, Box 5.1). 

## Other forms of covalent modification of proteins

Many proteins are modified after synthesis by the addition of chemical groups (posttranslational modification). In general this is not a means of rapid regulation of activity, but it may be essential for the normal activity of the protein. Many proteins that will be exported from the cell have carbohydrate and aminoglycan chains attached, either attached via asparagine residues (N-linked glycosylation) or via threonine residues (O-linked glycosylation). This occurs during their passage through the Golgi apparatus. It is a means of sorting out misfolded proteins and directing the protein towards the correct route. It is essential for the protein’s activity, but not a feature of rapid regulation. 

Besides phosphorylation, proteins, including enzymes, may also be modified by reversible acetylation, adenylation, ADP-ribosylation, uridylylation and methylation. Many of the covalent group donors (ATP, NAD, acetyl-CoA) are intimately related to energygenerating pathways and this potentially provides a link between metabolic status and the degree of enzyme activation. 

Similarly, some proteins have fatty acyl chains attached (acylation), often myristic acid (called myristoylation) or palmitic acid (palmitoylation). This strengthens the protein’s interaction with membranes, the hydrophobic acyl chain embedding in the membrane. It is not known whether it has rapid regulatory significance, although palmitoylation can be reversible. The hormone ghrelin, released from the stomach (see Section 6.2.5.5), is modified by octanoylation – addition of an 8-carbon fatty acyl chain. There is a small family of proteins undergoing this modification. Without it, ghrelin is inactive. 

The mechanisms whereby changes in flux through metabolic pathways occur are sensitive to the energy status of the cell  –  the cell ‘senses’ its energy levels and regulates the appropriate pathways accordingly. Some means whereby this is achieved are discussed in Box 2.5. 

## Box 2.5 Role of NAD in metabolic regulation

Energy is carried in the cell either as a ‘high energy phosphate’ bond, principally ATP (Box 1.6), or by electrons (hydride ions) carried by electron carriers in their reduced form, principally NADH (Figure 1.16; Box 1.5). We have seen how important ATP is in regulating metabolism: it acts as a direct, allosteric regulator of enzyme activity (as do its products ADP and AMP) but it also acts as a phosphate donor for covalent regulation by kinase enzymes (phosphorylation) – it ‘makes sense’ that the energy carrier itself acts to regulate the supply of energy by modulating the energy yielding (and storing) pathways. (If we continue this appraisal of ATP as a messenger, we can further consider that it also provides cyclic AMP (cAMP – see Box 3.3), which is a second messenger in many cellular processes, including many metabolic pathways.) Hence, the energy carrier ATP is also acting as a type of cellular energy sensor, but also as an energy signal to regulate metabolism. 

What of the other major energy carrier, nicotinamide adenine dinucleotide (NAD)? It appears that many of the features seen in ATP in its regulatory role are also seen in NAD: 

1. Both are energy carriers which are ideally placed to act as sensors of cellular energetic status: 

ATP: energy charge (or phosphorylation potential): [ATP] + ½ [ADP]/ [ATP] + [ADP] + [AMP] 

NAD: redox potential: [NADH]/[NAD+ ]. 

2. Both systems (NAD+ , NADH and ATP, ADP, AMP) are allosteric effectors (e.g. NAD/NADH and ATP/ADP both allosterically regulate pyruvate dehydrogenase kinase in order to regulate pyruvate dehydrogenase activity, but of course there are many examples of this type of activity). However a NAD-dependent kinase corresponding to AMP-dependent protein kinase (AMPK) has not been described to date. 

3. ATP participates in cell signalling by forming cAMP. With NAD a similar system appears to exist, the equivalent product being cyclic-ADP ribose (although the physiological role of this in signalling is less clear than cAMP). 

4. Both systems are involved in covalent regulation. As mentioned above, in the case of ATP this involves phosphorylation of target enzymes by kinases using ATP as the phosphate donor (neatly tying in the energetic status with the degree of covalent modification and hence regulation). The situation with NAD is more complex and currently under intensive investigation as it is being recognised as a major regulatory mechanism. 

NAD is a dinucleotide with two nitrogenous bases (adenine and nicotinamide (Nam)) each attached to a ribose sugar and a phosphate group. If nicotinamide is split off, the remaining molecule is termed ADP-ribose (and it can be readily seen from this the structural similarity between NAD and ATP – removal of the ribose would yield ADP). Recently, a group of enzymes termed the sirtuins (after Silent Information Regulator Two) have been found to split off ADP-ribose from NAD and use this to carry out two very different types of covalent modification (see Figure 2.5.1: Sir2 is sirtuin 2). Firstly, it uses ADP-ribose as an acceptor for acetyl groups in order to deacetylate proteins (acetylation is a major type of covalent modification – see Box 2.4; and, interestingly, the opposite process, protein acetylation, uses acetyl-CoA as the acetyl group donor, again involving energetic pathways – indeed, a third type of energy carrier – in cellular regulation). However, sirtuins also use the ADP-ribose as a donor to ADP-ribosylate other proteins. This is another, major yet completely different, covalent regulatory mechanism. Sirtuins have been found to be stimulated by calorie restriction, and also by an active ingredient in red wine (derived from grape skins), resveratrol. There is evidence that this stimulation may underpin some of the apparent health benefits of calorie restriction and red wine, including promoting longevity, but clearly further work is required to elucidate the mechanism. 

![image](/assets/images/human_metabolism_images/b35ba915899865c1ee14b7b57f3ff184.jpg)



Figure 2.5.1


5. ADP-ribose is also used to synthesise cyclic-ADP ribose (above), and is a substrate for an enzyme which poly-ADPribosylates proteins, poly-ADP ribose polymerase (PARP). The large amount of ADP-ribose (and nicotinamide) produced by these processes can potentially deplete cellular NAD levels, and a ‘salvage’ pathway for resynthesising NAD from the nicotinamide exists. This salvage pathway uses an enzyme 

called NAMPT (nicotinamide phosphoribosyl transferase) to synthesise nicotinamide mononucleotide (NMN) and then NAD. NAMPT has attracted much recent interest as it appears to be secreted by cells in the manner of a cytokine, and indeed was thought to be secreted by visceral adipocytes and influence glucose metabolism, although these reports are still not clear. However, it has been suggested that by influencing the NAD salvage pathway, NAMPT may exert a regulating influence over NAD-dependent processes (it has even been suggested that NAMPT is a master-regulator of ageing). 

## 2.3.2 Regulation of substrate delivery through the bloodstream

Another form of control that will be discussed in many places in this book is achieved through alteration of the flow of substrates through the bloodstream. For example, fatty acids are usually a preferred fuel (over glucose) for skeletal muscle. When glucose is present in increased concentrations in the circulation after a carbohydrate-rich meal, how do muscles reduce their fatty acid use so that glucose can be utilised instead? The answer lies in adipose tissue, responsible for releasing fatty acids into the circulation. Fatty acid release is very effectively switched off by insulin, so muscles no longer have the option of using fatty acids. This apparent cooperation between tissues is typical of metabolic regulation when viewed on a whole-body basis, and will be discussed further in Chapter 3. 

## 2.3.3 Substrate cycling

A mechanism that has much potential to underlie rapid changes in metabolic flux is so-called substrate cycling, sometimes known as futile cycling. The idea is that both forward and reverse reactions may be operating at the same time: see ‘Enz 2A’ and ‘Enz 2B’ on Figure 2.3. Suppose, for example, that flux through Enz 2A is 10 (arbitrary units) and flux through Enz 2B is 9 units. Then net flux along the pathway will be 1 unit (10 – 9 units). Now suppose that Enz 2B is inhibited by 50%, so flux through it is now 4.5 units. Net flux along the pathway is now 5.5 units, a 450% increase achieved with a relatively small (halving) of flux through one reaction. This is hypothetical. Possible examples of substrate cycling conferring metabolic control will be met in several places in this book. Note that the reactions do not need to occur in the same cell, or even tissue. Fatty acids are oxidised in the mitochondrion of many tissues to form acetyl-CoA. Acetyl-CoA can be used by a cytosolic pathway to make fatty acids (especially in liver and adipose tissue: to be discussed in Chapter 5). This sounds extremely wasteful, but in fact the occurrence of each pathway is tissue-specific and nutritional-state dependent  –  fatty acid oxidation occurs in the fasted state, fatty acid synthesis in the fed state, so avoiding undue waste of resources (further discussion in Section 7.5.1.1). 

## 2.4 Longer-term control of metabolic pathways

In the previous section we looked at the mechanisms that are used to regulate the flow of metabolites through various metabolic pathways, particularly when the regulation occurs ‘rapidly,’ that is, over a period of minutes or perhaps an hour or two. These mechanisms would apply, for instance, after eating a meal, when nutrients enter the bloodstream over a short period and metabolism needs to be adjusted accordingly. However, there are also mechanisms that operate over longer periods. Typically, these would respond to a change in ‘lifestyle’: a change in the energy or the macronutrient content of the diet, a change in usual exercise level, or maybe the impact of some genetic influence that becomes slowly manifest over a long period of time. 

These gradual changes involve increases or decreases in the amounts of enzymes and other proteins (transporters) expressed in cells. The processes leading from a gene to its protein product are known as gene expression. Changes in gene expression may reflect changes in the rate of protein synthesis or, less commonly, in the rate of protein degradation. An increase in the rate of protein synthesis can in turn reflect either an increased rate of transcription of messenger-RNA (mRNA) from DNA, or (less often) a lower rate of mRNA degradation. Transcription of mRNA is regulated by the binding of proteins known as transcription factors to stretches of DNA, normally outside the gene itself, that allow the transcriptional machinery to operate. These mechanisms for regulating mRNA availability are called transcriptional regulation. There may also be an increase in the rate at which proteins are synthesised from the mRNA template, by increasing the rate at which new protein chains are started (the process called initiation). This mechanism is known as translational control. The control of gene expression is a very general mechanism pervading much of metabolic regulation, and will be referred to many times in this book. Different stages at which the amount of any particular protein may be controlled are summarised in Figure 2.4. Beyond the amount of protein present, the activity of an enzyme or transcription factor may then be altered by post-translational control, using mechanisms such as phosphorylation (Table 2.4) or proteolytic cleavage (as for the sterol regulatory element binding proteins, SREBPs, discussed later in Section 2.4.2.3). 

![image](/assets/images/human_metabolism_images/025f15e8cfc4e5b4f26ed96282a242fc.jpg)



Figure 2.4 Different stages at which the amount of a protein present in a cell may be controlled (underlined). For many proteins the major control is at the level of transcription (mRNA synthesis from the DNA template). Not shown in this figure is a further layer of complexity added by alternative splicing of the mRNA after transcription. The initial, nuclear full-length mRNA molecule is a faithful reproduction of all the DNA sequence of the gene. This includes introns (junk DNA) and exons (DNA that codes for mRNA that will be exported from the nucleus). The introns are removed in the nucleus and the ends of the remaining mRNA ‘spliced’ together before export from the nucleus. The resulting mRNA may start with alternative exons, giving a range of possible transcripts from one gene.


Recent advances in cell biology and functional genetics have shown additional layers of regulation, which will not be covered in detail here. As noted previously (Section 2.2.1), specific sets of genes are expressed in different cell types: that is what makes a hepatocyte different from an adipocyte, for instance. These differences are epigenetic, due in part to covalent modifications of the histone proteins that wrap up the DNA in the chromosomes, which semi-permanently repress the expression of those genes affected. Alteration of the cytosine bases of the DNA by methylation may have similar effects. These alterations are carried through cell divisions and may only be reset at meiosis when new gametes are formed, so that an embryo can ‘start from scratch.’ Even after mRNA has been transcribed, there can be interference with its function by a number of RNA-based mechanisms. For instance, micro-RNAs, specific short RNA molecules, can bind to mRNAs. They may either target them for destruction, or suppress their ability to act as templates for translation into protein. Other short RNA molecules, which do not code for proteins and are therefore generally known as non-coding RNAs, also regulate gene transcription. The expression of these non-coding RNAs is itself regulated, adding additional layers to the complexity of metabolic regulation. 

## 2.4.1 Innate changes in metabolism with time

Many aspects of cell function, including metabolism, have a pattern of regular fluctuations that coincide with time of day. This is obvious if we think of a normal day with its pattern of waking, getting up, eating meals and then going to bed and sleeping, but the remarkable thing is that many of these fluctuations continue to occur if all those external cues are removed. This has led to the concept of an internal ‘clock’ controlling bodily functions. The fluctuations that occur over regular 24-hour periods are called circadian, from the Latin circa (about) and dies (day). The circadian rhythms naturally repeat every 24 hours, but not exactly so: normally they are reset every day by the outside influence of light. 

![image](/assets/images/human_metabolism_images/1859ba18d15c6b0a86a26e6e22ebf562.jpg)



Figure 2.5 Operation of the circadian clock at a cellular level. The proteins CLOCK (circadian locomotor output cycles kaput) and BMAL1 (brain and muscle aryl hydrocarbon receptor translocator-like protein 1) heterodimerise to form a transcription factor, which acts on E- (enhancer)-boxes to promote transcription. Amongst the products are the proteins Period (Per1 and Per2) and Cryptochrome (Cry1 and Cry2). Per and Cry proteins form a complex with other proteins, that inhibits the transcriptional activity of the CLOCK/BMAL1 complex. Thus an oscillation is set up. Transcription of other genes, for instance those coding for enzymes involved in metabolism, is regulated to the same period. This mechanism operates within many cells, but there is input from the hypothalamus (see text) to coordinate rhythms throughout the body.


The system that brings about these rhythms involves transcription (mRNA from DNA) and translation (mRNA to protein) and is sometimes referred to as a transcription-translation feedback loop or a transcription translation oscillating (TTO) loop. A small number of core clock genes is involved, leading to control of the expression of a very large number of ‘clock-controlled genes.’ Almost half the genes in the mouse genome oscillate with a circadian period in one or more organs of the body. The ‘master’ circadian clock is located in the suprachiasmatic nucleus of the hypothalamus (part of the brain: for more information, see Section 6.3.2.1). This nucleus (a group of nerve cells) receives direct input from the photoreceptors of the eye, so allowing the clock to be kept in time with the outside world – so-called photic circadian entrainment. However, the core clock genes are expressed, and a similar transcription-translation feedback loop operates, in most cells of the body: the hypothalamic master-clock synchronises these ‘peripheral’ clocks using nerve signals and hormones, in particular the hormone melatonin (an amino acid derivative) which signals through a family of G protein-coupled receptors (see Section 3.4 and Box 3.2 for more information). 

The working of the circadian clock mechanism at a cellular level is shown in Figure 2.5. 

## 2.4.2 Nutrients and control of gene expression

In terms of adaptation to changes of diet, it makes sense that some nutrients themselves (or metabolic products of these nutrients) can alter gene expression. Several systems by which this occurs have been identified. 

## 2.4.2.1 Carbohydrate responsive genes

The expression of some genes is increased in response to increases in carbohydrate availability. Some examples are given in Table 2.5. Of course, increased carbohydrate availability also leads to higher insulin concentrations (discussed further in Chapter 6), but it has been shown with cellular preparations that the expression of certain genes is increased by glucose without the need for additional insulin. It is now accepted that there are independent pathways for regulation of gene expression by insulin and glucose (Figure 2.6). The molecular mechanism by which glucose regulates gene expression involves a transcription factor known as the carbohydrate response element binding protein (ChREBP, Figure 2.6; sometimes called carbohydrate responsive element binding protein). The human gene for ChREBP is MLXIPL, for MLX-Interacting Protein-Like. ChREBP is regulated in opposite ways by glucose and by cyclic adenosine 3′,5′-monophosphate (cyclic AMP, or cAMP  –  see Box 3.3 for structure). Glucose availability leads to production of a number of metabolites that regulate ChREBP activity. These include glucose 6-phosphate, fructose 2,6-bisphosphate produced in glycolysis, and xylulose 5-phosphate produced via the pentose phosphate pathway (Section 5.1.1.2.3). These metabolites, perhaps acting in concert, activate a protein phosphatase, PP2A, which dephosphorylates ChREBP and allows it to enter the nucleus and bind to DNA, increasing the expression of the genes whose promoter regions contain the carbohydrate response element (ChRE). When glucose is lacking, glucagon, acting via adenylate cyclase, cAMP and cAMP-dependent protein kinase (protein kinase A, or PKA: see Chapter 3, Box 3.3 for definitions), leads to phosphorylation of ChREBP and exclusion from the nucleus. Insulin, glucose and the regulation of gene expression will be considered again in the next Chapter (Section 3.5.1). 


Table  2.5 Some genes whose expression is increased by glucose (at a cellular level) or by carbohydrate availability via ChREBP activity.


<table><tr><td>Gene</td><td>Comments</td></tr><tr><td>Liver isoform of pyruvate kinase</td><td>Glycolysis</td></tr><tr><td>Glucose-6-phosphate dehydrogenase</td><td>Feeds glucose into the pentose phosphate pathway</td></tr><tr><td>Acetyl-CoA carboxylase</td><td>Synthesis of fatty acids from cytosolic acetyl-CoA (see later, Box 5.4)</td></tr><tr><td>Fatty acid synthase</td><td>Synthesis of fatty acids from acetyl-CoA</td></tr><tr><td>Stearoyl-CoA desaturase</td><td>Desaturation of saturated fatty acids (part of the lipogenesis pathway)</td></tr><tr><td><eq>S_{14}</eq> (or Spot 14)</td><td>Lipogenesisa</td></tr><tr><td>SREBP-1c</td><td>Transcriptional regulation</td></tr><tr><td>Insulin</td><td>(In the pancreatic β-cell)</td></tr><tr><td>SGLT1</td><td>Increased by presence of glucose in the intestinal lumen</td></tr><tr><td>PDX1</td><td>Transcription factor in pancreatic β-cell increasing insulin gene expression</td></tr></table>


Note that the expression of several genes is increased by insulin and glucose acting in concert, and the definition of a ‘glucose-regulated’ gene is not always clear – see also Section 3.5.1. 



${ } ^ { a } { \sf S } _ { 1 4 }$ is believed to be involved in lipogenesis in liver and adipose tissue. 


![image](/assets/images/human_metabolism_images/ae791c2cd99698c0d32dddaaed02e383.jpg)



Figure 2.6 Glucose control of expression of lipogenic genes. Glucose increases gene expression via the carbohydrate response element binding protein (ChREBP) (or, in the pancreatic β-cell, by a transcription factor known as PDX1). A number of metabolites of glucose interact to promote ChREBP dephosphorylation, which allows ChREBP to enter the nucleus and interact with DNA. Glucagon (in the liver) antagonises the glucose effect via cyclic AMP and phosphorylation of ChREBP. Although lipogenic genes are shown here, other genes are regulated similarly (Table 2.5). Insulin signals via a different mechanism, involving increased SREBP-1c expression (for description of SREBP-1c see Section 2.4.2.3; and for further details of insulin’s action on gene expression, see Chapter 3, Section 3.5.1). There is considerable ‘cross-talk’ between the pathways: SREBP-1c expression is also increased by glucose; and SREBP-1c induces enzymes of glucose metabolism such as glucokinase.


In the pancreatic β-cell, expression of the insulin gene is regulated by glucose (discussed later, Section 6.2.1.2). Here the immediate transcription factor is known as PDX1 (pancreatic and duodenal homeobox 1), and is different from ChREBP identified in liver and other tissues. PDX1 is phosphorylated when glucose levels rise and moves from its location on the nuclear membrane, into the nucleus to interact with DNA. PDX1 expression is also up-regulated by glucose, giving longer-term control. 

The sodium-linked glucose transporter SGLT1 increases in activity in the small intestine when dietary carbohydrate is abundant. The mechanism seems to involve both increased gene expression and increased translation of mRNA into protein. SGLT1 is induced by glucose within the intestinal lumen but not by a rise in blood glucose concentration. Similarly, and uniquely among glucose transporters, the mRNA expression of the fructose transporter GLUT5 (Box 2.2) is increased rapidly by the presence of fructose in the intestinal lumen. 

The mechanism is unknown at present although metabolism of fructose in the enterocytes seems to be essential. 

## 2.4.2.2 Fatty acids and gene expression

Fatty acids and their derivatives regulate gene expression by binding to intracellular proteins that are members of the family of nuclear receptors. Nuclear receptors are involved in the action of many hormones and will be described in detail in the next chapter (Box 3.5). 

It was recognised as early as the 1960s that an apparently diverse group of xenobiotics (pesticides) cause the proliferation of the small, oxidative organelles called peroxisomes in rat liver. Now we know that these compounds bind to a nuclear receptor, known for obvious reasons as a peroxisome proliferator-activated receptor (PPAR). The endogenous ligands for PPARs (i.e. the substances that normally bind to and activate these receptors) are fatty acids, or compounds derived from fatty acids such as certain prostaglandins. PPARs are a way of regulating gene expression according to the availability of fatty acids. There are three major isoforms of PPAR, described in more detail in Table 2.6. The overall effect of increased fatty acid availability is that fatty acid oxidation is up-regulated in the liver through PPAR-α, while fatty acid storage as triacylglycerol in adipose tissue is also increased through PPAR-γ. PPAR-δ (also called PPAR-β) may increase fatty acid oxidation in muscle. 

Not all fatty acids are equally active in activating the PPARs. Polyunsaturated fatty acids are more potent than saturated fatty acids, and, among the former, the n-3 series are more potent than the n-6 series. This probably relates also to the marked effect of n-3 polyunsaturated fatty acids in lowering plasma triacylglycerol concentrations, discussed in a later chapter (Box 10.5). Fatty acids also interact with the SREBP system described in the next section. 

The PPAR system is a major target for pharmacological manipulation. Again, in the 1960s it was observed by chance that a new pesticide was causing illness among farmers, and on investigation they were found to have low serum cholesterol concentrations. This led to the discovery of clofibrate, the first drug reliably able to lower serum cholesterol levels. Clofibrate is a peroxisome proliferator: it is a ligand for PPAR-α. Clofibrate turned out to have some undesirable side effects, but a group of drugs was developed from it: the fibrates or fibric acid derivatives. These drugs play an important role in lowering elevated serum lipid concentrations. They are more potent in lowering elevated triacylglycerol concentrations than elevated cholesterol, as we might predict knowing the effects of PPAR-α activation. They also have beneficial effects on some proteins involved in lipid metabolism; this will be discussed in Chapter 10 (Section 10.4.3). 


Table 2.6 Peroxisome proliferator-activated receptors (PPARs): tissue distribution and effects of activation.


<table><tr><td>Receptor</td><td>Other names</td><td>Main tissue distribution</td><td>Genes whose expression is increased by PPAR activation</td><td>Genes whose expression is suppressed by PPAR activation</td></tr><tr><td>PPAR-α</td><td></td><td>Liver (main site)Also kidney, heart, muscle, brown adipose tissue</td><td>Apolipoprotein <eq>Al^a</eq>Apolipoprotein AIIEnzymes of peroxisomal fatty acid oxidationLiver FABPCPT-1Enzymes of mitochondrial fatty acid oxidation</td><td>Apolipoprotein CIII</td></tr><tr><td>PPAR-δ</td><td>PPAR-β, NUC 1, FAAR (fatty-acid activated receptor)</td><td>Widespread, especially skeletal muscle, adipose tissue, liver, intestine</td><td>Enzymes of mitochondrial fatty acid oxidation.</td><td>Not known</td></tr><tr><td><eq>PPAR-γ1^b</eq></td><td></td><td>Widespread at low levels</td><td></td><td></td></tr><tr><td>PPAR-γ2</td><td></td><td>Adipose tissue</td><td>Factors involved in adipocyte differentiationAdipose tissue FABP (also known as aP2)Lipoprotein lipaseFatty acid transport proteinAcyl-CoA synthaseGLUT4Phosphoenolpyruvate carboxykinaseAdiponectin (protein secreted by adipocytes)</td><td>Leptin</td></tr></table>


CPT-1, carnitine palmitoyltransferase-1 or carnitine acyltransferase-1 (see Figure 5.4); FABP, fatty acid binding protein. 



a The apolipoproteins and their functions are described in Chapter 10. These effects may be different in rodents. 



bThe isoforms PPAR-γ 1 and PPAR-γ 2 are produced from the same gene by use of different promoters. 


During the search for new agents acting like the fibrates, a group of drugs was discovered that has the effect of lowering blood glucose concentrations, apparently by improving the sensitivity of tissues to the actions of insulin. These drugs are now called the thiazolidinediones or ‘glitazones’ and they are in widespread use for the treatment of diabetes. After their discovery, it was found that they are ligands for PPAR-γ. They probably act by increasing the ability of adipose tissue to store excess fatty acids as triacylglycerol: thus, circulating fatty acid concentrations are reduced, and tissues such as skeletal muscle are able to utilise more glucose because of reduced substrate competition. Activation of PPAR-γ is critical in the pathway of differentiation of new adipocytes from adipocyte precursor cells in adipose tissue (preadipocytes). The thiazolidinediones may promote the formation of new, small adipocytes that can sequester excess fat and again protect other tissues (see Section 5.2.2.3 for the significance of this). 

More recently, drugs have been designed to activate PPAR-δ. Although the physiological role of PPAR-δ has not been clear, studies in which it has been over-expressed in muscle have shown that it can markedly increase the muscle’s oxidative capacity. Mice engineered to express high levels of PPAR-δ in muscle could run on a treadmill for several hours without stopping and became known as ‘marathon mice.’ Limited studies of the PPAR-δ agonists in monkeys and in men seem to show an ability to improve HDL-cholesterol concentrations (which would be good for heart disease risk: see Section 10.4.3), to improve insulin resistance, and, perhaps underlying these changes, generally to increase the ability to oxidise fatty acids. It is too early to say whether these agents will find a clinical use. 

The PPAR proteins, as noted above, belong to the family of nuclear receptors/transcription factors, along with the steroid- and thyroid-hormone receptors. (Just to be clear: all nuclear receptors are transcription factors, i.e. they regulate transcription of mRNA from DNA. But there are many transcription factors that are not nuclear receptors.) Essentially the PPAR protein, with its bound ligand, will interact with a specific segment of DNA in the promoter region of the gene to be activated. However, the situation is more complicated than that. Like all members of the nuclear receptor family, the PPAR-ligand complex is not in itself able to bind to DNA. It must form a dimer by joining with a similar pair. In the case of the PPARs, the PPAR-ligand complex binds, not to another PPAR, but to a closely-related receptor called the Retinoid X Receptor (RXR), which has itself bound its ligand, all-cis retinoic acid, a derivative of vitamin A. It is not clear whether this need to bind to RXR has any regulatory significance, but it would be easy to imagine that availability of the other ligand, all-cis retinoic acid, could equally well regulate transcriptional activity. In addition, the dimer so formed will interact with a number of different activator and repressor proteins that regulate the transcriptional activity of the complex. We may imagine that this complicated process gives very precise control of gene expression, perhaps different in different tissues according to the expression levels of these additional proteins. The system is shown in Figure 2.7. One particular member of the complex formed around PPAR-γ, known as a co-activator, is the PPAR-γ co-activator, PGC-1α. PGC-1α will be considered again in Section 2.4.2.5 below. 

## 2.4.2.3 Cholesterol and gene expression

One of the first systems to be fully understood, by which nutrients or cellular constituents regulate gene expression, was that for cholesterol. This will be discussed again in more detail in Chapter 10, but is covered here because the system is now recognised to have more general importance. All cells with nuclei can synthesise cholesterol from cytosolic acetyl-CoA (Box 5.4), and can also acquire it from the plasma through a specific cell-surface 

![image](/assets/images/human_metabolism_images/1e88aadc39db22cd1033e6018dc5d2dd.jpg)



Figure 2.7 The PPAR system. The ligand for the PPAR (a fatty acid, or a fatty acid derivative) (triangles) enters the nucleus and docks with the protein. (Alternatively docking may occur within the cytosol, followed by migration of the complex into the nucleus: this is not clear.) All-cis-retinoic acid (diamonds) also docks with a related receptor, the Retinoid X Receptor (RXR). The two receptors with their bound ligands form a heterodimer which interacts with a number of activator and suppressor proteins (red and green circles). The whole complex binds to a response element (the PPAR response element, PPRE) in the promoter region of the PPAR target genes and activates transcription.


receptor (the low-density lipoprotein receptor, or LDL receptor, described in detail in Chapter 10). Cells regulate their own cholesterol content by adjusting expression of the key enzymes of cholesterol synthesis, particularly the first committed step in cholesterol synthesis from cytosolic acetyl-CoA, 3-hydroxy-3-methylglutaryl-CoA reductase (HMG-CoA reductase; described later, Box 5.4). Expression of the LDL receptor is also regulated in parallel. These genes were considered to have a regulatory element responsive to sterols (i.e. to cholesterol or related compounds), a sterol regulatory element. Sterols themselves do not bind to DNA, so the protein doing this was called the sterol regulatory element binding protein (SREBP). SREBP is synthesised initially as a protein associated with the membrane of the endoplasmic reticulum (ER), but after proteolytic cleavage, the N-terminal portion can move to the nucleus and regulate gene expression. The system is illustrated and explained in Figure 2.8. Drugs that inhibit HMG-CoA reductase are known as the statins. They have a major role in treatment of elevated serum cholesterol concentrations, as will be explained further in Chapter 10 (Sections 10.4.2.1 and 10.4.2.2). Because they lower cellular cholesterol concentrations, they up-regulate LDL receptor expression through the SREBP system. 

There are two SREBP genes, producing SREBP-1 and SREBP-2. SREBP-2 regulates cholesterol homeostasis in the manner described above. This system has also been exploited pharmacologically, as described in Chapter 10 (Section 10.4.2.1). There are, in turn, two isoforms of SREBP-1, produced by alternative splicing of the mRNA. One in particular, SREBP-1c, seems to be intimately involved with insulin regulation of gene expression (see above), especially for genes involved in fatty acid metabolism. SREBP-1c is the main isoform expressed in liver and adipose tissue, in which fat storage (at the expense of oxidation) is likely to be an important pathway. Insulin not only increases transcription of SREBP-1c, but also increases its proteolytic cleavage. The mechanism is not clear, but this serves to separate the effects of the two SREBP systems. Proteins known as INSIGs (insulin-induced genes) may be involved. See Section 3.5.1 for further discussion. 

![image](/assets/images/human_metabolism_images/40da6815438a1bc2aeafda4e24ded40f.jpg)



Figure 2.8 The SREBP system. The full-length SREBP protein is located in the endoplasmic reticulum (ER, a system of membranous cavities within the cytoplasm). It is associated with the SREBP cleavage activating protein (SCAP), which ‘senses’ the level of cholesterol, or related sterols, within the membrane of the ER. When the cellular cholesterol content is low, the SCAP-SREBP complex migrates to the Golgi complex (not shown), where specific proteases cleave SREBP to release the N-terminal portion, ‘mature’ SREBP. Mature SREBP moves to the nucleus where it binds to sterol response elements in the promoter regions of many genes. If SREBP-2 is concerned (as shown in the figure), these are mainly genes concerned with cholesterol metabolism (LDL receptor, enzymes of cholesterol synthesis). SREBP-1 is regulated more by expression of the full-length protein (which is increased by insulin); its proteolytic cleavage is also stimulated by insulin independently of cholesterol. SREBP-1c increases the expression of genes concerned with fat storage (including acetyl-CoA carboxylase and fatty acid synthase).


It is now recognised that fatty acids can also affect the SREBP system. Polyunsaturated fatty acids (but not apparently saturated fatty acids) markedly down-regulate expression of SREBP-1c. This makes sense, because increased fat availability then down-regulates the expression of lipogenic enzymes. 

Derivatives of cholesterol, oxysterols, and bile acids, also act on nuclear receptors known as LXR and FXR. These will be further described in Box 4.2, and will be mentioned again when we discuss wholebody cholesterol homeostasis in Section 10.3.3. 

## 2.4.2.4 Amino acids and gene expression

If carbohydrates and lipids can regulate gene expression, it should not surprise us that amino acids can do the same. There are pathways that regulate amino acid metabolism in response to both deficiency and surplus of amino acids. One of the best understood, which potentially integrates amino acid signalling with other nutrient-related signals, is the mTOR pathway. Rapamycin (also called sirolimus) is a drug used in immunosuppression. mTOR is the protein identified as the mammalian Target Of Rapamycin (sometimes called mechanistic Target Of Rapamycin). mTOR is a member of a family of protein kinases related to phosphatidylinositol-3-kinase (see Box 3.3). It functions in one of two complexes called mTOR complex 1 (mTORC1) and mTOR complex 2 (mTORC2). mTOR is activated by amino acids (leucine, an essential amino acid (Section 7.4.2.1), is an important activator, as is arginine), by insulin and by other anabolic hormones such as IGF-1 (Section 6.2.2.1). Activation is brought about by alteration of the association of mTOR with other regulatory proteins. The protein targets of mTOR are factors involved in initiating the translation of mRNA into protein. Thus, increased availability of essential amino acids, together with anabolic signals such as insulin, increases protein synthesis. The mTOR pathway is also involved in the increased muscle protein synthesis that follows exercise training. 

## 2.4.2.5 Regulation of oxidative metabolism by gene expression

An important aspect of metabolic regulation and its adaptation to different circumstances is the use of oxygen to oxidise nutrients and, hence, generate ATP. There are two aspects relevant to this chapter. The first is a series of mechanisms that increase the ability of tissues to conduct oxidative metabolism. We noted previously that PPAR-α increases the expression of genes involved in fatty acid oxidation. PPAR-δ does the same, perhaps with a stronger effect in skeletal muscle. These adaptations will provide more substrate (acetyl-CoA) for oxidation. But the ability of a cell to oxidise acetyl-CoA may be limited by the mitochondrial capacity of that cell: either the number of mitochondria may be inadequate, or the capacity of each mitochondrion may be. Studies of the transcriptional co-activator PGC-1α (Section 2.4.2.2) have shown that this, and other members of the PGC family, are ‘master regulators’ of mitochondrial capacity. In studies in which PGC-1α expression has been experimentally up-regulated, the number of mitochondria in the cell concerned increases, and the expression of oxidative enzymes in those mitochondria will also increase. If PGC-1α expression is increased in skeletal muscle, the muscle cells take on more oxidative characteristics (akin to the oxidative, type 1 muscle fibres that will be described in more detail in Section 5.3.2). PGC-1α expression has also been increased experimentally in fat cells (adipocytes). This tends to transform the phenotype of the adipocyte, from a fat-storing cell to a fat-burning cell, akin to transforming white adipose tissue into brown adipose tissue (these terms will be described in Section 5.2.1). 

The other aspect of regulation of oxidative capacity concerns the availability of oxygen itself. Oxygen is just as important for the body as are the fuels it will oxidise. It is therefore not surprising that the availability of oxygen can alter gene expression. Chronic reduction in oxygen availability (as would occur at high altitude, for example) leads to upregulation of the expression of many genes relating to oxygen transport and energy metabolism. These include the glycoprotein hormone erythropoietin produced in the kidney, which stimulates erythrocyte (red blood cell) production. The glucose transporters GLUT1 and GLUT3 and enzymes of glycolysis are also up-regulated (phosphofructokinase, aldolase, and lactate dehydrogenase – particular isoforms are involved in each case). The process of angiogenesis, formation of new blood vessels, is also stimulated, so that regions of tissue that are not receiving enough oxygen become better perfused. The molecular mechanisms by which this is achieved are outside the scope of this book, but there is an important transcription factor that is activated when oxygen availability is low, known as hypoxiainducible factor-1 or HIF-1. 

## Supplementary resources

Supplementary resources related to this chapter, including further reading and multiple choice questions, can be found on the companion website at www.wiley.com/go/frayn. 

![END](/assets/config_images/end.jpg)
