---
title: 人类代谢-C6-双重通信系统
date: 2026-06-01 00:00:00 +0800
last_modified_at: 2026-06-01 00:01:00 +0800
categories: [科研, 代谢] # 最多两层
tags: [科研, 代谢, book]
# toc: false # 关闭目录
math: true
mermaid: true # diagram generation
---



## Chapter 6


## Communication systems


核心逻辑：**如果说前两章阐明了单个细胞和局部组织如何进行“闭门造车”式的代谢，那么本章则上升到了宏观调控。人体通过两条并行的生化总线——“蜗牛快递”式的血液激素网络（内分泌系统）和“光纤电缆”式的电信号/神经递质网络（神经系统），将全身数百亿细胞交织成一个高度一体化的信息生态圈。**


## 模块一：通信系统的“生化双引擎”——内分泌与神经系统

材料首先对人体的两套主干通信线路进行了物理特性的精妙对垒：

```
[激素系统] (血液总线) ➔ 浓度极低 (pmol/l) ➔ 全身弥散 ➔ 速度较慢 ➔ 负责“维持宏观秩序”
[神经系统] (电缆总线) ➔ 局部释放 (突触间隙) ➔ 精准靶向 ➔ 速度极快 (毫秒级) ➔ 负责“应对急性应激”

```

* **激素系统（内分泌）：** 类似于“广播投递”。激素由特定腺体释放入血，全身体循环稀释。它们在血浆中的浓度极其微量（如胰岛素仅为 $\text{pmol/l}$ 级别，比葡萄糖低一亿倍，见 Box 3.1）。它主要通过细胞内的级联放大效应，掌管**饱食、饥饿、长期饮食和 lifestyle 改变的代谢格局**。
* **神经系统：** 类似于“点对点光纤”。神经元（Neurones）依靠高能耗维持的**膜静息电位**（内负外正 $-70\text{ mV}$，由 $Na^+-K^+-ATPase$ 泵死守），在受到刺激时开启电压门控钠通道，引发动作电位（Action Potential）如电波般沿轴突狂飙（见 Box 6.1）。
* **连接的枢纽（突触 Synapse）：** 当电波抵达轴突末梢，电压门控钙通道大开，$Ca^{2+}$ 涌入触发囊泡胞吐，将**神经递质（Neurotransmitters）**倾泻入极其狭窄的**突触间隙（Synaptic Cleft）**（见 Box 6.2）。它不经过全身体循环，直接咬合靶细胞膜受体，实现毫秒级的短路指挥（如短跑发令枪响瞬间的肌肉收缩与燃料动员）。

---

## 模块二：内分泌核心——胰岛“双子星”与葡萄糖感应回路

胰腺是一个典型的“两栖器官”，其 98% 的体积在干外分泌（分泌消化酶），而散落其中的胰岛（Islets of Langerhans）则是内分泌的皇冠（图 6.2）。

### 1. 胰岛 $\beta$ 细胞的“血糖传感器”与电生化耦合（图 6.4）

$\beta$ 细胞（占胰岛体积的 60%）分泌**胰岛素**（由 A、B 两条肽链通过三个二硫键锁定的肽类激素，分泌时切除无功能的 C-肽，见图 6.3）。它是人体**唯一的合成代谢（Anabolic）总司令**。其感知血糖并释放胰岛素的微观过程堪称生化奇迹：

1. **进餐后：** 血糖升高，葡萄糖通过高容量运输蛋白（人类主要是 **GLUT1/GLUT3**，大鼠为 GLUT2）无阻碍地涌入 $\beta$ 细胞。
2. **能量锁钥匙：** 进入细胞的葡萄糖被葡萄糖激酶（GK，HK IV）活化并进行糖酵解，细胞内 **$ATP/ADP$ 比例暴涨**。
3. **大门关闭：** 暴涨的 $ATP$ 直接去咬合细胞膜上的 **$ATP$敏感性钾通道（$K^+_{ATP}$，由 Kir6.2 和 SUR1 两亚基构成）**，将其强行关闭！*（注：SUR1 即磺酰脲类受体，临床一线降糖药磺酰脲类如格列齐特，就是强行关闭这个受体来逼迫胰岛素分泌，见图 6.4）。*
4. **钙流如潮：** 正常外流的 $K^+$ 被堵死，导致细胞膜电位发生**去极化（Depolarisation）**。这瞬间激活了隔壁的**电压敏感性钙通道（$Ca^{2+}$ 通道）**。
5. **胞吐轰炸：** $Ca^{2+}$ 顺着浓度差疯狂灌入细胞质，直接驱动满载结晶胰岛素的密密麻麻的囊泡奔向细胞膜，发生大张旗鼓的胞吐释放（见图 6.5 的剂量效应曲线）。
6. **肠道外挂（肠促胰素 Incretins）：** 如图 6.13 所示，口服葡萄糖引发的胰岛素海啸远超静脉注射。这是因为小肠上皮在接到食物后，会提前释放 **GLP-1** 和 **GIP**。它们通过 GPCR 提前锁死 $\beta$ 细胞，将葡萄糖引发的胰岛素分泌成倍放大。

### 2. 胰岛 $\alpha$ 细胞与反向调控

$\alpha$ 细胞分泌 **胰高血糖素（Glucagon，29氨基酸）**。它的使命与胰岛素完全相反——拼命拉高血糖。当血糖下跌时，胰高血糖素大肆分泌，通过肝脏表面的 **GCGR（GPCR受体）** 启动 cAMP-PKA 分瀑布，下达肝糖原大解体和糖异生的总动员令。

---

## 模块三：神经内分泌总司令部——下丘脑-垂体轴与甲状腺长效调制

人体的长期代谢速率和生存大战略，由大脑底部的下丘脑-垂体轴（Hypothalamic-Pituitary Axis）实施半军事化统御。

### 1. 神经内分泌的终极集成器：下丘脑（Hypothalamus）

下丘脑（图 6.16）是全身生化指标的监控大厅：

* 它本身塞满了葡萄糖感受器、渗透压感受器（监控脱水与否）、温度感受器。
* 它同时读取外周脂肪细胞寄来的瘦素（Leptin）报告和胰岛素报告，以此评估全人类的“总资产”，进而通过操纵神经元来遥控食欲、饱腹感（图 6.12）和自主神经输出。

### 2. 垂体（Pituitary Gland）的令旗分发（图 6.6）

下丘脑通过垂体柄向下控御腺垂体（前叶）和神经垂体（后叶）：

* **抗利尿激素（ADH / 血管加压素）：** 由后叶释放。急性失血应激时，ADH 一方面死死锁住肾脏不准排尿（控水），一方面剧烈收缩血管（维持血压），甚至直接通过 Gq 蛋白引爆肝脏 $Ca^{2+}$ 信号，强行震碎肝糖原释放血糖。**“哪怕把仓库拆了，也必须维持血压和血糖支撑大脑逃跑！”**
* **促肾上腺皮质激素（ACTH）：** 由前叶的 POMC 巨型前体切出。它在清晨大肆释放，顺着血液去唤醒肾上腺皮质。
* **促甲状腺激素（TSH）：** 奔向甲状腺（图 6.7），命令其大量抓取血液中的碘，将其缝合在酪氨酸骨架上，合成**甲状腺素（$T_4$/$T_3$）**（图 6.8）。

### 3. 代谢大幕的底色调制：甲状腺素（$T_3$/$T_4$）

* 甲状腺素不负责分钟级的火警扑救，它扮演的是“生化节律的底色调制师”。它在体内拥有巨大的缓冲库（足足支撑三个月的释放量）。
* 它的活性形式 $T_3$ 结合全身细胞的核受体（TR-RXR 异二聚体），全面操控基因转录。
* **生理功能：** 它规定了人体的**基础代谢率（BMR）**，调高全身对交感神经 catecholemines 的别构敏感度。它通过直接上调肌肉细胞内的 **UCP3（解偶联蛋白3）** 和激活棕色脂肪，让线粒体处于轻微的“漏电产热”状态。甲状腺功能亢进（甲亢）者形消骨立、心跳狂飙，正是由于全身线粒体被强行推向了解偶联和燃料空转。

---

## 模块四：生存与危机的大本营——肾腺（Adrenal Glands）的双重变奏

肾上腺（图 6.9）分为两个来源截然不同的解剖层面，它们在应激（Stress）状态下奏响了“交响乐”的高潮：

```
[肾上腺髓质] (外周神经衍生) ➔ 释放 肾上腺素 (真激素) ➔ 绑定 $\alpha$/$\beta$ 肾上腺素能受体 ➔ 毫秒级闪电动员
[肾上腺皮质] (上皮细胞衍生) ➔ 释放 皮质醇 (糖皮质激素) ➔ 绑定核受体 GR ➔ 数小时长效续航

```

### 1. 肾上腺髓质与肾上腺素（Adrenaline）：闪电战

髓质本质上是一个高度特化、直接受内脏神经指挥的交感神经节。它不分泌递质进突触，而是直接将 **肾上腺素（Adrenaline）** 喷射进血液。

* **受体大阅兵（Table 6.1）：** 肾上腺素疯狂激活全身的肾上腺素能受体家族：
* **$\beta_1$ 受体（心肌）：** 引爆 cAMP，让心脏跳动力量与频率成倍飙升， cardiac output 疯狂输出。
* **$\beta_2$ 受体（骨骼肌血管、支气管）：** 强力舒张骨骼肌血管，大开肺部支气管，确保大量血液和氧气畅通无阻地灌注进战斗肌肉。
* **$\beta_2$/$\beta_1$ 受体（脂肪、肝脏）：** 如图 6.11 实验所示，利用 $\beta$-阻断剂（普萘洛尔）可以极大压制运动时的脂肪动员。肾上腺素通过 $\beta$ 受体疯狂激活 PKA，全面轰炸 HSL 和糖原磷酸化酶，将游离脂肪酸（NEFA）和血糖推向血浆巅峰。
* **$\alpha_1$ 受体（内脏血管）：** 剧烈收缩皮肤和胃肠道血管。在生死搏杀时，胃肠蠕动和皮肤供血被无情牺牲，血液被强行分流到大脑和骨骼肌。
* **$\alpha_2$ 受体（别构刹车）：** 脂肪细胞上也长有 $\alpha_2$ 受体，通过 Gi 蛋白压制 cAMP。在平时静息时，$\alpha_2$ 的刹车效应配合胰岛素，让脂肪稳稳锁在库里。



### 2. 肾上腺皮质与皮质醇（Cortisol）：持久战

皮质释放脂溶性的类固醇激素 —— **皮质醇（糖皮质激素）**。

* **拆东墙补西墙：** 皮质醇结合细胞核内的 **GR 受体**。它不追求几秒内的爆发，而是追求数小时至数天的**持久抗战续航**。
* **生化后果：** 它大刀阔斧地斩断外周骨骼肌对胰岛素的响应（关闭肌肉的糖摄取），疯狂拆解肌肉 contractile 蛋白，转化为氨基酸外排；同时命令肝脏开足马力进行**糖异生**。它把全身榨干出来的资源，精纯地转化为血糖，去死死捍卫高压危机下大脑的刚性供能。
*  permissive 效应（Permissive Effect）： 皮质醇更是一位隐形推手。没有它的“准许（Presence）”，肾上腺素的很多糖原砸碎通路根本无法激活。它不直接拔高流量，但它是通路运转不可或缺的合法钥匙。

---

## 模块五：外周器官的内分泌跨界——脂肪、肌肉与肠道信号

现代代谢学粉碎了传统内分泌腺的边界，发现外周三大代谢主力本身就是极其庞大的内分泌器官。

### 1. 脂肪组织的“ adipokines 军团”与瘦素（Leptin）

白色脂肪组织（WAT）是全身最庞大的政治芯片，分泌大量的 **脂肪因子（Adipokines）**：

* **瘦素（Leptin，图 6.12）：** 脂肪库越充盈，脂肪细胞就分泌越多的瘦素。瘦素穿透血脑屏障，咬合下丘脑长型受体（OB-Rb），下达“资产已满，缩减食欲，加大交感神经支出去烧能”的总命令。如果瘦素基因突变（如 ob/ob 小鼠），大脑便陷入长期处于大荒年的幻觉，导致疯狂暴食演变为超级巨婴。而人类肥胖往往是由于受体不敏感导致的“瘦素抵抗”。
* **脂联素（Adiponectin）：** 与瘦素相反，越瘦、脂肪细胞越小，分泌越多。它结合外周 AMPK 仪表盘，强力**提高全身对胰岛素的别构敏感度**，抗炎且保护胰岛。

### 2. 肾脏的血压-能量联动（RAAS系统）

肾脏不仅分泌红细胞生成素（EPO）管造血，更在血压偏低时释放**肾素（Renin）**：

* 肾素剪切肝脏来源的血管紧张素原产生血管紧张素 I，随后在肺部微血管被 **ACE（血管紧张素转换酶）** 剃头，生成终极血管强心剂 —— **血管紧张素 II**。
* 血管紧张素 II 逼迫皮质释放醛固酮（Aldosterone）去吸纳盐水，强行拔高血压。现代发现，拦截该通路的 ACE 抑制剂（ACEI）和 ARB 类药物不仅降压，更能直接提升外周骨骼肌的线粒体耐力运动寿命，深度干预能量代谢。

### 3. 肌肉因子的发声：Myokines

骨骼肌在运动收缩时，也会像腺体一样向外泼洒**肌肉因子（Myokines）**：

* **IL-6（白介素-6）：** 运动肌纤维释放的 IL-6 充当了宏观协调员，它跨界通知肝脏赶快吐糖、脂肪赶快解体释放 NEFA 供前线肌肉冲锋。
* **鸢尾素（Irisin）：** 由运动经 PGC-1$\alpha$ 调控剪切外排。它顺着血流冲向全身的白色脂肪库，揪住白脂肪细胞强行进行“脂肪棕色化（Browning）”改造，逼迫它们长出线粒体和 UCP1，就地空转产热，成为了运动减肥的分子桥梁。

---

### 总结

第六章完成了**人体从“局部的化学反应”向“全身的宏观通信”的惊艳跨越**。

* 当你在**饱食（Fed）**状态下，小肠的 **GLP-1/GIP** 联合高血糖，通过 Kir6.2 极化回路引爆 $\beta$ 细胞的 $Ca^{2+}$ 涌入，开启**胰岛素**的绝对霸权，命令下丘脑 FoxO1 闭嘴，全面转入长效的安抚与合成囤积。
* 当你在**奔跑、恐惧或遭遇重创（Stress）**时，下丘脑拉响警报，交感神经电缆在突触释放**去甲肾上腺素**，并逼迫髓质向血液泼洒**肾腺素**，通过 $\beta$ 级联和 $\alpha_1$ 分流，瞬间停掉内脏物流，毫秒级震碎糖原与脂肪供前线战斗；同时，下丘脑-垂体轴派遣 **ACTH、TSH、ADH** 以及皮质的**皮质醇**全面封锁外周糖消费，拆解肌肉、长效糖异生，甚至调高线粒体 **UCP3** 进行解偶联调整。

这些通信网络的相互交织、别构 Permissive 与多级 Cascade 放大，共同构筑了人类在复杂多变的生存逆境下，牢不可破的宏观动态平衡。


## Key learning points

•	 Communication between tissues and organs is achieved through hormones travelling through the bloodstream (first covered in Chapter 3), and through the activity of the nervous system. 

•	 The Islets of Langerhans are groups of endocrine cells in the pancreas that secrete insulin and glucagon, peptide hormones that have major effects regulating metabolism. 

•	 The pituitary gland, attached to the hypothalamus (part of the brain), is divided into two parts. It secretes a number of peptide hormones that regulate diverse physiological processes, including the secretion of other hormones elsewhere in the body. 

•	 The thyroid gland produces a hormone that is an iodinated derivate of the amino acid tyrosine. This acts on many different tissues to regulate the rate of metabolism. 

The adrenal glands, situated above each kidney, are each divided into a core, the medulla, and an outer layer, the cortex. The adrenal medulla secretes adrenaline (US: epinephrine), synthesised from the amino acid tyrosine, which acts on cell-surface G protein-coupled receptors (GPCRs) to regulate metabolism, blood flow, and other physiological processes. The adrenal cortex secretes steroid hormones, mainly cortisol, regulating glucose and other facets of metabolism, and aldosterone, regulating salt and water balance. 

•	 Other organs that are better recognised for their metabolic roles also release peptide hormones, notably the gastro-intestinal tract, the heart, the kidneys, adipose tissue, and, perhaps, skeletal muscle. 

•	 The nervous system, including the brain, has widespread effects on metabolism. These may be direct and indirect, mediated through changes in blood flow through tissues, and through effects on the secretion of hormones such as insulin. 

•	 There are several distinct branches of the nervous system. The autonomic nervous system includes the sympathetic nervous system, which mainly acts on metabolism to mobilise stored fuels, and the parasympathetic nervous system, whose effects on metabolism generally oppose those of the sympathetic and might be considered anabolic. 

The somatic nervous system connects the brain to the skeletal muscles and brings about muscle contraction. The afferent nervous system consists of nerves bringing signals from peripheral tissues back to the brain. The enteric nervous system is the complex nervous system of the gut and regulates intestinal function. 

The actions of nerves are brought about by release of chemicals known as neurotransmitters, which act on specific receptors in target tissues. The junction between a nerve cell and a target tissue (which may be another nerve) is called a synapse. 

Acetylcholine is the neurotransmitter of the parasympathetic and somatic nervous systems, and also of the parts of the sympathetic system near to the spinal cord. 

Noradrenaline (US: norepinephrine) is the neurotransmitter of peripheral parts of the sympathetic nervous system. It is closely related to the hormone adrenaline (US: epinephrine). Noradrenaline and adrenaline both act via GPCRs called adrenoceptors, of which there are two major classes, α and β. 

•	 Activation of the sympathetic nervous system brings about a number of metabolic changes including liver glycogen breakdown and adipose tissue lipolysis. 

## 6.1 Communication systems

In Chapter 3 we looked at means by which the regulation of metabolism is integrated between different tissues. As discussed there, hormones play an important role in this integration, both in short-term changes in metabolic flux – for instance, after eating a meal, the situation described extensively in the next chapter (Chapter 7), and in longer-term changes such as adaptation to a new diet or a new level of physical activity. The nervous system also plays a role, and this is particularly apparent in situations of acute change that might be called ‘stress,’ including exercise and situations in which the body is subjected to insults of various kinds. The aim of this chapter is to give more detailed information on these routes of communication. The endocrine glands (that produce hormones) are not in themselves major consumers of energy relative to other tissues in the body; but clearly their products have important effects in regulating energy supply and storage in the body. 

## 6.2 Hormones important in metabolic regulation

Here the major hormone-producing glands, and some exocrine tissues relevant to energy metabolism will be considered. The location of the glands to be discussed is shown in Figure 6.1. 

![image](/assets/images/human_metabolism_images/a5d4f878a6d9ebd36f8e18f6934f3e67.jpg)



Figure 6.1 The location of endocrine glands involved in energy metabolism. The thymus is shown but is primarily an organ where cells of the immune system are produced and mature.


## 6.2.1 The pancreas

## 6.2.1.1 General description of the pancreas

The pancreas is a fish-shaped organ lying under the liver (Figure 6.1). It has a distinct head and a narrow tail, and the head end is wrapped around the small intestine. The pancreas is a complex organ since it contains both exocrine and endocrine tissues. The exocrine function of the pancreas is the liberation of digestive juices into the small intestine; the endocrine function consists of the production and secretion of hormones into the bloodstream, most importantly insulin and glucagon. 

The vast majority of cells in the pancreas are exocrine. These cells produce an alkaline digestive juice containing a number of enzymes, particularly amylase, pancreatic lipase, and the proteases trypsin and chymotrypsin. This juice is collected into small ducts which merge to form one main pancreatic duct. This is joined by the common bile duct just before it enters the duodenum; thus, bile salts and pancreatic enzymes are liberated together into the small intestine. The digestive function of the pancreas, and its regulation, were discussed in Chapter 4 (Table 4.2). 

Scattered among the exocrine tissue are little groups of cells, appearing like islands under the microscope. They were first described by a German medical student, Paul Langerhans, in 1869 and are known as the Islets of Langerhans (Figure 6.2). These are the endocrine cells. There are around one million islets in the adult pancreas, although they constitute only 1–2% of the total mass of the pancreas. Within the islets there are three types of endocrine cell: the α-cells or A cells, which secrete glucagon; the β-cells or B cells, which secrete insulin; and the δ-cells or D cells which secrete somatostatin. The β-cells occupy about 60% of the volume of the islet. Somatostatin in the pancreas probably has a local regulatory role, affecting the secretion of insulin and glucagon, but this is not entirely clear, and it will not be considered further here. Each islet is supplied with blood by a branch of the pancreatic artery, and venous blood leaves the islet in tiny veins (venules) which merge to form the pancreatic and pancreaticoduodenal veins. As discussed in Section 5.1.1, they discharge their contents into the hepatic portal vein, so the liver is in a unique position as regards its exposure to the pancreatic hormones. 

![image](/assets/images/human_metabolism_images/ff529095016773ee909028a980446263.jpg)



Figure 6.2 Islets of Langerhans in the pancreas. The pancreatic tissue has been immunostained to show the presence of insulin (and hence the islets). Source: courtesy of Dr. Anne Clark.


## 6.2.1.2 Insulin

Insulin is a peptide hormone. It consists of two peptide chains, the A and B chains, linked to each other by disulphide bonds; the A chain contains 21 amino acids and the B chain 30 amino acids. It is synthesised within the β-cells as a single polypeptide chain (proinsulin) and the connecting peptide or C-peptide is removed by proteolytic action before secretion (Figure 6.3). 

The rate of secretion of insulin into the plasma varies according to the metabolic or nutritional state. That is how it achieves its signalling function. The most important regulator of the rate of insulin secretion is the concentration of glucose in the plasma. In rodents, the β-cell is similar to the hepatocyte in that it expresses the GLUT2 transporter and the hexokinase IV isoform (glucokinase). As in the liver (Section 5.1.1.2.1), these give the β-cell the ability to act as a ‘glucose sensor.’ As the external (plasma) glucose concentration rises, so glucose flows into the cell and is phosphorylated, and then enters the glycolytic pathway. (In humans a combination of GLUT1 and GLUT3 expression achieves the same end.) This leads to generation of ATP, which regulates events at the cell membrane (Figure 6.4). Insulin, which is synthesised within the cell and stored in secretory granules, is released by exocytosis of these granules  –  the granule membrane fuses with the cell membrane and its contents are discharged into the extracellular space. The synthesis of new insulin is also stimulated (via the transcription factor pancreatic and duodenal homeobox 1, PDX1 – see Section 2.4.2.1), and if the stimulus (elevated glucose concentration) persists, insulin secretion will be maintained by increased synthesis. 

![image](/assets/images/human_metabolism_images/bccd5feb6369e6c4eb617e8fe95a7736.jpg)



Figure 6.3 Synthesis of insulin. Insulin is first synthesised as one long polypeptide, preproinsulin. The N-terminal portion is a ‘signal sequence’ that directs preproinsulin into the secretory vesicles. It is then removed (arrows show sites of proteolytic action). Three disulphide bonds are formed between cysteine residues. (These will hold the mature protein in a particular folded structure.) Further proteolytic cleavage releases the connecting peptide, or C-peptide, to produce mature insulin. Insulin and C-peptide are secreted in equimolar amounts from the β-cell. Some proinsulin is also secreted into the plasma.


The response of the β-cells to the surrounding glucose concentration may be studied by isolating pancreatic islets and incubating them in medium containing different concentrations of glucose. The characteristic sigmoid dose–response curve for insulin secretion rate against glucose concentration is shown in Figure 6.5. Insulin secretion is not much increased until the glucose concentration rises above 5 mmol l−1 , which (by no coincidence) is the normal concentration of glucose in plasma. In other words, an elevation of the concentration of glucose in the plasma above its normal level will result in increased secretion of insulin. In the period following a meal, insulin secretion increases more than would be expected solely on the basis of increased plasma glucose concentration. This reflects the action of so-called incretin hormones, or incretins, released from the small intestine in response to meal ingestion. These incretin hormones act through GPCRs expressed in the β-cell to amplify glucose-stimulated insulin secretion. See Section 6.2.5.5 below for more details. 

Glucose is not the only stimulus to insulin secretion. Insulin secretion is also responsive to most amino acids (alanine, arginine, and branched-chain amino acids especially), so that after a meal containing protein there is a stimulus for net protein synthesis. Ketone bodies also (somewhat) stimulate insulin secretion that is stimulated by glucose: this could be seen as a mechanism for restraining ketone body concentrations, since increased insulin secretion will inhibit fatty acid release from adipose tissue and ketogenesis in the liver. 

Fatty acids are essential for normal glucosestimulated insulin secretion; an increase in the fatty acid concentration for a period of one or two hours will potentiate insulin secretion in response to glucose. Two mechanisms are involved. First, fatty acids can signal through a G-protein coupled receptor, GPR40 (see Table  3.1). In addition, there is an effect that depends upon metabolism of the fatty acid: a fatty acid derivative, perhaps acyl-CoA, in some way regulates the insulin secretory pathway. However, if elevated fatty acid concentrations are maintained for more than a few hours, the opposite is seen: there is an impairment of insulin secretion. This is associated with an accumulation of triacylglycerol within the β-cell. 

Insulin secretion is also modulated by the nervous system, in ways that will be discussed in more detail later in this Chapter (Section 6.3.3.4 and Table 6.3). 

![image](/assets/images/human_metabolism_images/2111cb40cc3eb97373610b6de01b4bbc.jpg)



Figure 6.4 Glucose stimulation of insulin secretion in the pancreatic β-cell. Glucose enters the cell via the transporter GLUT2 (but see below) and is phosphorylated by glucokinase (GK) (hexokinase IV). These steps are similar to glucose utilisation in the liver and allow the β-cell to ‘sense’ the plasma glucose concentration. Generation of ATP from glucose utilisation closes ATP-sensitive $\mathsf { K } ^ { + }$ channels in the cell membrane, stopping the outward flow of $\mathsf { K } ^ { + }$ ions that normally maintains the resting membrane potential (see Box 6.1, for full description of this). This leads to membrane depolarisation and opening of voltage-sensitive $\mathsf { C a } ^ { 2 + }$ channels. Insulin is present in multiple secretory vesicles in the cell, as a crystalline complex in the centre of the vesicle. An inward flux of $\mathsf { C a } ^ { 2 + }$ ions causes exocytosis of the insulin-containing secretory vesicles, and hence insulin secretion. Glucose also stimulates synthesis of new insulin (Section 2.4.2.1). Although this scenario is true in rodent islets, in human β-cells GLUT1 and GLUT3 give the human β-cell sufficient glucose transport capacity. The ATP-sensitive $\mathsf { K } ^ { + }$ channel has two subunits. One is the $\mathsf { K } ^ { + }$ channel itself. This belongs to the family of inwardly-rectifying $\mathsf { K } ^ { + }$ channels (Kir, family 6 no. 2, hence Kir6.2). The other sub-unit modulates the activity of the channel and is the ‘receptor’ for ATP (strictly, the complex $\mathsf { M g } ^ { 2 + } { \mathsf { - A T P } } )$ ). But it is also the target for drugs used to treat type 2 diabetes, the sulphonylureas (see later, Table 12.3). They bind, and cause channel closure, just as ATP does. Hence, this has become known as the sulphonylurea receptor, SUR. Again, there is a family of related proteins, and the one expressed in the β-cell is known as SUR1.


Insulin circulates free in the bloodstream; it is not bound to a carrier protein. It affects tissues by binding to specific insulin receptors, proteins consisting of four subunits (two α- and two β-chains), embedded in cell membranes (see Box 3.3). Signal chains linking the binding of insulin to its receptor with an intracellular change in metabolism were covered in Chapter 3 (Box 3.4). 

Insulin is removed from the circulation after binding to the cell surface insulin receptors. These, with their bound insulin, become internalised (i.e. taken up into the cell) and eventually the insulin is degraded by proteolysis. The process of internalisation may have some role in bringing about insulin’s actions, but this is not clear. It is also not clear whether some insulin is removed from the bloodstream by processes that do not result directly in metabolic effects. However, what is clear is that about 70% of the insulin reaching the liver is removed in its ‘first passage.’ This means that the liver is exposed to much higher concentrations of insulin than other tissues or organs. It also means that swings in insulin concentration are to some extent ‘damped down’ by the time the insulin reaches the general circulation. This emphasises the special relation between endocrine pancreas and liver. 

![image](/assets/images/human_metabolism_images/57dd8e4078885a4d0f2999d917d2ce3d.jpg)



Figure 6.5 Dose–response curve for the effects of glucose concentration on the secretion of insulin from isolated human islets of Langerhans, studied in vitro. Insulin secretion is stimulated as the glucose concentration rises above about 5 mmol l−1 (a typical concentration of glucose in the plasma). Source: with kind permission from Springer Science + Business Media, Harrison, D. E., Christie, M. R., & Gray, D. W. R. (1985) Diabetologia 28: 99–103. © Springer-Verlag 1985.


Insulin is often thought of as ‘the hormone’ that lowers blood glucose concentration, but in fact its metabolic effects are widespread. They will be widely considered throughout this book, but may be summarised by the word ‘anabolic.’ Insulin stimulates the synthesis of energy stores (glycogen and lipids) and of protein, and suppresses the breakdown of those stores (again, glycogen, lipids, and also protein). Lack of insulin is characterised by a severe catabolic state (considered further in Chapter 12). 

## 6.2.1.3 Glucagon

Glucagon is a single polypeptide chain of 29 amino acids. Like insulin, it is synthesised initially as a larger protein (a prohormone) called proglucagon. Proteolytic cleavage gives rise to glucagon. (The large proglucagon molecule can be cleaved to release different peptides in the endocrine cells of the small intestine; Section 6.2.5.5.) In contrast to insulin, glucagon’s major action is to elevate the blood glucose concentration. In fact, it was first discovered as a contaminant of preparations of insulin made from animal pancreases, which caused some batches to have the opposite of the desired blood glucose-lowering effect. 

Its secretion from the pancreatic α-cells, like that of insulin from the β-cells, responds to both glucose and amino acids. However, unlike insulin, glucagon secretion is suppressed rather than stimulated by a rise in glucose concentration (although it is stimulated by amino acids). Thus, a rise in the plasma glucose concentration will lead to an increased ratio of insulin to glucagon secretion, and a fall in the plasma glucose concentration will lead to an increased ratio of glucagon to insulin. Again, some glucagon is removed on its first passage through the liver, although rather less than for insulin (animal experiments suggest around 5–10%). Nevertheless, glucagon probably has no important metabolic effects in any tissue other than the liver. 

Glucagon produces its effects on intracellular metabolic pathways by binding to a GPCR, the glucagon receptor (gene GCGR). The receptor is coupled to adenylate cyclase, and intracellular effects of glucagon are mediated via cAMP (see Boxes 3.3 and 3.4). 

## 6.2.2 The pituitary gland

The pituitary gland, about the size of a pea, is situated under the brain (Figure 6.6), attached through a little stalk to the area of the brain known as the hypothalamus (see Section 6.3.2.1). The pituitary gland is also known as the hypophysis, or ‘growth underneath’; surgical removal of the pituitary gland is called hypophysectomy. The hypothalamus, which itself lies under the thalamus, is the seat of integration of incoming signals from nerves with specialised ‘sensing’ functions and outgoing nervous activity, particularly in the sympathetic nervous system. It will be discussed in more detail in Section 6.3.2.1. The location of the pituitary gland in close proximity to the hypothalamus reflects their close functional relationship as described below. 

![image](/assets/images/human_metabolism_images/6819c2e24ac57e97c4f584d339c42cbb.jpg)



Figure 6.6 Pituitary hormones and their target organs.


The pituitary gland has two major parts, or lobes: the anterior pituitary  –  also called the adenohypophysis  –  and the posterior pituitary, or neurohypophysis. The adenohypophysis contains cells which manufacture and secrete hormones. Regulation of the synthesis and secretion of its hormones is controlled, however, by other signals (local hormones) coming down a system of blood vessels in the stalk from the hypothalamus. The neurohypophysis is composed mainly of nerve cells that have their cell bodies in the hypothalamus. The hormones which it releases are synthesised in the hypothalamus, transported along axons and stored temporarily before being secreted in response to nervous stimuli from the hypothalamus. Thus, the hypothalamus controls both nervous signals and hormonal signals to the rest of the body. 

The hormones produced by the pituitary gland and their target organs are shown in Figure 6.6. 

## 6.2.2.1 Hormones of the anterior pituitary (adenohypophysis)

The posterior pituitary secretes at least six distinct peptide and glycoprotein hormones. Several act on other hormone-producing organs to influence the secretion of further hormones; they are known as trophic (or tropic) hormones. Of these, follicle-stimulating hormone (FSH) and luteinising hormone (LH) (known together as gonadotrophins) have functions in the reproductive system that will not be considered further. All the anterior pituitary hormones discussed below apart from prolactin and growth hormone act through GPCRs. 

Adrenocorticotrophic hormone (ACTH) sometimes called corticotrophin – is a peptide hormone (of 39 amino acids) which acts on the adrenal cortex to stimulate release of glucocorticoids, particularly cortisol. ACTH is (like insulin) synthesised as a prohormone, but in this case a very large one called pro-opiomelanocortin (POMC). POMC is cleaved proteolytically to generate several biologically active peptides including β-endorphin and met-enkephalin (known generally as endorphins; they are natural ligands of the receptors for cocaine, and involved in feelings of well-being, e.g. in response to exercise); α-, β- and γ-melanocyte-stimulating hormones (acting on melanocytes to influence pigmentation); and ACTH. (The melanocyte-stimulating hormones, also called melanocortins, may also have a role in appetite regulation; see Box 11.1.) 

ACTH is released in response to stress. It also has an important circadian rhythm (24- hour cycle); it is at its highest, as is cortisol secretion, in the morning at about the time of waking. There is feedback control of ACTH secretion: high levels of cortisol suppress ACTH secretion, by two mechanisms. Fast-feedback inhibition acts over minutes, which implies an effect independent of gene expression and protein synthesis, presumably though a membrane receptor; delayed feedback inhibition reflects effects on gene expression mediated by the nuclear receptor glucocorticoid receptor (GR). 

Thyroid-stimulating hormone (TSH)  –  sometimes called thyrotrophin  –  acts on the thyroid gland to stimulate the production of thyroid hormones and to stimulate growth of the gland (discussed further in Section 6.2.3). Again, there is a feedback system, so that in thyroid deficiency, for example, TSH levels in blood are high; this is usually a clearer diagnostic test than direct measurement of thyroid hormone levels themselves. 

Two more hormones secreted by the anterior pituitary act on other tissues that are not endocrine: prolactin and growth hormone. Prolactin stimulates milk production in the mammary gland and will not be considered further. 

Growth hormone is a peptide hormone (of 190 amino acids in humans), sometimes called somatotrophin because of its major role in regulating growth and development (somato referring to the body). It does not do this directly. Growth hormone stimulates the production in the liver of other peptide hormones known as the insulin-like growth factors, IGF-1 and IGF-2, formerly known as the somatomedins since they mediate the effects of somatotrophin. As their name implies, the insulin-like growth factors have structural similarities with insulin. They exert stimulatory effects on growth, while growth hormone has no direct effect. Even in adults, however, growth hormone is secreted. This occurs mainly overnight, in discrete bursts during sleep. It has some direct metabolic functions, although their importance in adults is not fully understood. The most important is probably a stimulation of fat mobilisation. This is not a rapid effect (unlike the effects of adrenaline or noradrenaline acting through the cAMP system – see Box 3.4). After a single injection of growth hormone, there is a stimulation of lipolysis after two to three hours. Growth hormone also has an effect on hepatic glucose production, involving stimulation of both gluconeogenesis and glycogenolysis. Again, this is probably not an effect of short-term importance. Adults who have had their pituitary gland removed surgically (usually because of a tumour) are usually not given growth hormone replacement, as it is expensive, and has not until recently been thought necessary. Recently, a number of trials of growth hormone replacement have shown that such treatment results in a loss of body fat and an increase in lean body mass, including muscle, reflecting a combination of the lipolytic and anabolic (growth promoting) effects. It may also result in a feeling of well-being, which is thought to reflect in part increased availability of fuels for physical work  –  that is, non-esterified fatty acids and glucose in the plasma. 

## 6.2.2.2 Hormones of the posterior pituitary (neurohypophysis)

The posterior pituitary secretes two structurally similar 9-amino acid peptide hormones, oxytocin (which causes the uterus to contract, and stimulates milk flow from the breast – discussed later, Section 8.3.3) and vasopressin, also called antidiuretic hormone. The last name (ADH) suggests an obvious function in regulating urine production (more specifically, in regulating urine concentration), but the name vasopressin shows that this hormone also has a potent effect in constricting certain blood vessels. It may also, under certain conditions (particularly stress states), have a role in metabolic regulation: vasopressin can stimulate glycogen breakdown in the liver. This is brought about by a change in the cytosolic $\mathrm { C a } ^ { 2 + }$ concentration rather than through an increase in cAMP (the GPCR concerned, AVPR1A, links to the Gq system – see Box 3.2). An interesting relationship between the different effects of vasopressin may be seen. We have already seen that glycogen is stored with about three times its own weight of water: the liver glycogen store of about 100  g is accompanied by 300 g water. Mobilisation of glycogen therefore liberates water into the circulation. In a severe stress state brought about by loss of blood, for example, vasopressin might have multiple actions: further loss of water through the kidney is prevented by its antidiuretic action; extra water is mobilised along with glycogen; fuel (glucose) is provided for the organism to help deal with the stress (e.g. to provide energy to run away from an aggressor); and the vasoconstrictor action helps to maintain blood pressure despite the loss of blood. 

## 6.2.3 The thyroid gland

The thyroid gland weighs about 25 g and is made up of two lobes joined by a bridge, situated on either side of the trachea (windpipe) in the throat (Figure 6.7). It has a rich blood supply. It is responsible for secretion of the thyroid hormones, which are iodinated amino acid derivatives. They are formed from tyrosine residues within the protein thyroglobulin, and iodine, which is taken up avidly by the gland from the blood (Figure 6.8). There are two thyroid hormones, known as thyroxine or $T _ { 4 }$ (with four iodine atoms per molecule) and triiodothyronine or $T _ { 3 }$ (with three iodine atoms). Both are secreted by the gland and present in blood. $\mathrm { T } _ { 3 } ,$ however, is the active hormone. 3The enzyme necessary to convert $\mathrm { T _ { 4 } }$ to $\mathrm { T } _ { 3 } ,$ , 5-deiodinase type 2, is expressed in hypothalamus, white and brown adipose tissue, and skeletal muscle. $\mathrm { T } _ { 3 }$ acts via a nuclear receptor (Box 3.5), the thyroid hormone receptor (TR), which must heterodimerise with the Retinoid X Receptor (RXR) to affect transcription (see Section 2.4.2.2 and Box 3.5 for a description of RXR). 

![image](/assets/images/human_metabolism_images/a3068b35383f45af81321838ccb96e8c.jpg)



Figure 6.7 The anatomy of the thyroid gland.


Synthesis and secretion of the thyroid hormones are regulated by the pituitary-derived TSH (Section 6.2.2.1) acting via a GPCR linked to cAMP production. TSH also increases thyroid size. In thyroid deficiency due, for instance, to lack of iodine in the diet, thyroid hormone levels in the blood are low. As discussed in Section 6.2.2.1, this leads to an increase in TSH secretion in order to stimulate more thyroid hormone production. It also leads to enlargement of the thyroid gland, sometimes to a massive growth on the neck known as a goitre; hence the apparent paradox of an enlarged gland and a deficient hormone. 

Many of the hormones which regulate metabolism do so in a very rapid manner; their secretion is regulated on a minute-to-minute basis and their effects on metabolic pathways are similarly rapid, or sometimes somewhat slower if effects on protein synthesis are involved. The thyroid hormones, however, seem to set the general level of metabolism in a longterm way. In parallel with this, the thyroid gland is unusual in storing a large amount of hormone – enough for around three months’ secretion. 

![image](/assets/images/human_metabolism_images/ee363debe8947364437ddd5a50eecb2d.jpg)



Figure 6.8 Biosynthesis of the thyroid hormones. Thyroxine $( \mathsf { T } _ { 4 } )$ and triiodothyronine $( \top _ { 3 } )$ are synthesised in the thyroid gland from tyrosine residues in the protein thyroglobulin. The conversion of ${ \sf T } _ { 4 }$ to ${ \sf T } _ { 3 } ,$ the active hormone, occurs mainly in peripheral tissues.


Some specific effects of thyroid hormones on metabolism will be covered in later chapters, particularly their effect on muscle protein metabolism (Section 7.4.3). For the most part, however, the thyroid hormones play a ‘modulating’ role, affecting the level of response to other hormones. In particular, they regulate the sensitivity of metabolic processes to catecholamines (adrenaline and noradrenaline); thus, an excess of thyroid hormones has many similarities to an excess of adrenaline or noradrenaline. An excess of thyroid hormones is characterised by an increase in the overall metabolic rate; a deficiency is characterised by a depression of metabolic rate. The major mechanism for increased metabolic rate in response to thyroid hormones appears to be uncoupling of mitochondrial respiration (see Sections 1.3.1.5 and 5.2.3) with an increase in brown adipose tissue thermogenic activity and upregulation of uncoupling protein 3 (UCP3) expression in skeletal muscle. 

## 6.2.4 The adrenal glands

The two adrenal glands sit like cocked hats over each kidney (Figure 6.9) (hence their name  – additions to the renal organ, or kidney). Each gland has an inner core and an outer layer of cells, the adrenal medulla and adrenal cortex respectively. The cortex (outer layer) makes up about nine-tenths of the bulk of the gland; its cells under the microscope are rich in lipid. The medulla stains darkly for microscopy with chromic salts, showing the presence of so-called chromaffin cells, characterised by the presence of catecholamines (such as adrenaline and noradrenaline). 

![image](/assets/images/human_metabolism_images/73b08b30b95a732871d0ba932411098b.jpg)



Figure 6.9 The anatomy of the adrenal glands.


## 6.2.4.1 The adrenal cortex: cortisol secretion

The adrenal cortex secretes a number of steroid hormones, which are synthesised from cholesterol. Some of these affect mainly mineral metabolism (salt and water balance) and are known collectively as the mineralocorticoids; some affect intermediary metabolism (glucose, fatty acid, and amino acid metabolism) and are known as the glucocorticoids. In humans, the most important mineralocorticoid is aldosterone; the major glucocorticoid is cortisol.1 

1 Cortisol is also known as hydrocortisone. The latter name is more commonly used when referring to a medicinal product but chemically they are identical. In rodents the principal glucocorticoid is the related compound, corticosterone. 

As discussed above (Section 6.2.2.1), the synthesis and secretion of cortisol are regulated by ACTH from the anterior pituitary. Cortisol has metabolic effects on a number of tissues. They are both short term and longer term. Even the shortterm effects are for the most part mediated by changes in protein synthesis and, therefore, take a matter of hours rather than minutes. As we saw in Section 3.5.2, they are brought about by binding of cortisol to a nuclear receptor, the GR, although there may be even more rapid effects brought about by cell-surface receptors. The metabolic effects of cortisol include: a stimulation of fat mobilisation in adipose tissue, by increased activity of the enzyme hormone-sensitive lipase (this probably involves synthesis of additional enzyme protein); a stimulation of gluconeogenesis (again via synthesis of key enzymes; see Box 5.2); inhibition of insulin-stimulated glucose uptake by muscle (by interfering with insulin signalling); and an increase in the breakdown of muscle protein (Section 7.4.3). 

These effects of cortisol are often difficult to demonstrate in isolated tissues. Many of cortisol’s effects are more permissive than direct. A permissive effect means that a process cannot occur (or activation by another hormone cannot occur) in the absence of the ‘permitting agent’ – in this case cortisol – but the actual level of the permitting agent is not important. Thus, in people or animals whose adrenal cortex has been removed, some effects of adrenaline, for instance, do not occur (particularly stimulation of glycogen breakdown). Responsiveness to adrenaline can be reinstated by giving a glucocorticoid hormone such as cortisol, but the level achieved is not important – just its presence. 

## 6.2.4.2 The adrenal medulla, adrenaline secretion, and adrenaline action

The adrenal medulla develops as part of the nervous system. It is supplied with nerves that are part of the sympathetic nervous system. (They are preganglionic fibres whose neurotransmitter is acetylcholine; this will be discussed in detail in Section 6.3.2.3.) Its secretory activity is controlled directly by the brain through these nerves, and not by substances in the blood. It secretes the hormone adrenaline (named after the adrenal gland; in American literature this hormone is called epinephrine). The related compound noradrenaline (US: norepinephrine) has similar effects, although noradrenaline is almost entirely liberated as a neurotransmitter from sympathetic nerve terminals and is, therefore, not a true hormone, whereas adrenaline is a hormone in every sense. They are both referred to as catecholamines because they are amine derivatives of the catechol nucleus. Their structures and the route of synthesis are shown in Figure 6.10. 

Adrenaline and noradrenaline act on adrenergic receptors (or adrenoceptors), GPCRs (see Box 3.2) found in the plasma membranes of most tissues. There are different classes of adrenoceptor, first recognised because of the different potencies of adrenaline-like substances in bringing about various effects in specific tissues. Broadly, they may be divided into the α- and β-receptor families, which are themselves subdivided into ${ \mathfrak { X } } _ { 1 } , \ { \mathfrak { X } } _ { 2 }$ and $\beta _ { 1 - 3 }$ subtypes. The subtypes of adrenergic receptors are summarised in Table 6.1. 

Binding of adrenaline and noradrenaline to adrenergic receptors brings about a variety of effects. From the point of view of energy metabolism, there may be grouped into: direct effects on metabolic pathways, circulatory effects, and effects on the secretion of other hormones. The last two may well have indirect effects on metabolism. We will discuss them later in connection with the nervous system (Section 6.3.3). 

β-Adrenergic receptors are linked, via Gs proteins, to adenylate cyclase, producing cAMP (see Box 3.2). Consequent activation of the cAMPdependent protein kinase (protein kinase $A ;$ see Box  3.3) may lead (directly or through other protein kinases) to phosphorylation of a key regulatory enzyme: glycogen phosphorylase and hormone-sensitive lipase are two examples (see Box 3.4). Thus, catecholamines acting through β-adrenergic receptors lead to breakdown of stored fuels, glycogen, and triacylglycerol. 

α-Adrenergic receptors may produce similar or opposite effects, depending upon the tissue. $\mathfrak { X } _ { 1 } { } ^ { - }$ Receptors are linked via Gq to the second messenger system that involves hydrolysis of phosphatidylinositol $( 4 ^ { \prime } , 5 ^ { \prime } )$ )-bisphosphate (see Box  3.3). This will lead to release of $\mathrm { C a } ^ { 2 + }$ from intracellular stores into the cytoplasm. This is involved in an alternative route for the activation of glycogen breakdown by adrenaline: an increased cytosolic $\mathrm { C a } ^ { 2 + }$ concentration will directly activate phosphorylase kinase (see Figure 3.4.2 in Box 3.4, and also Figure 8.2). α -Receptors are linked to adenylate cyclase through inhibitory Gi proteins, and thus adrenaline binding to such receptors will reduce the production of cAMP and oppose effects caused by its binding to β-receptors. α-Receptors (especially $\mathbf { \boldsymbol { \mathfrak { a } } } _ { 1 } )$ also mediate the constriction of blood vessels and this has some repercussions on metabolism in stress states. 

The complexities of adrenergic regulation of metabolism are illustrated by lipolysis in adipocytes. Human fat cells express $\mathfrak { X } _ { 2 } { } ^ { - }$ and $\beta _ { 1 } \AA ^ { - }$ and $\beta _ { 2 } .$ -adrenergic receptors. (In rodents, lipolysis is stimulated mainly by the $\beta _ { 3 } { \mathrm { - r e c e p t o r . } }$ In humans the $\beta _ { 3 } { \mathrm { - r e c e p t o r } }$ is expressed in brown adipose tissue where it stimulates thermogenesis  –  see Section 5.2.3. It is also expressed in the bladder.) There is usually a balance between stimulatory and inhibitory effects, and in normal sedentary daily life regulation of lipolysis by insulin (decreasing cAMP and hence reducing lipolysis, as shown in Figure 3.4.3, Box 3.4) predominates. However, in response to any kind of stress, including exercise, there is activation of the β receptors so that lipolysis is stimulated. Blockade of the β receptors with the β-antagonist propranolol reduces exerciseinduced lipolysis (Figure 6.11). (The component of exercise-induced lipolysis that cannot be blocked by propranolol represents stimulation by atrial natriuretic peptide, ANP; Section 6.2.5.2.) 

![image](/assets/images/human_metabolism_images/fcc94e6fe9239442bed884b5d61bdf25.jpg)



Figure 6.10 Biosynthesis of the catecholamines. Noradrenaline is a neurotransmitter, released from sympathetic nerve terminals, whereas adrenaline is a true hormone, released into the bloodstream from the adrenal medulla.



Table 6.1 Adrenergic receptors and their effects.


<table><tr><td>Receptor type</td><td>Second messenger system</td><td>Metabolic effects</td><td>Circulatory effects</td></tr><tr><td><eq>\beta</eq></td><td>Adenylate cyclase/cAMP</td><td>Glycogenolysis; lipolysis</td><td>Increased heart rate and force; dilation of blood vessels</td></tr><tr><td><eq>\alpha_{1}</eq></td><td>Phospholipase C/intracellular <eq>Ca^{2+}</eq></td><td>Glycogenolysis</td><td>Constriction of blood vessels</td></tr><tr><td><eq>\alpha_{2}</eq></td><td>Inhibition of adenylate cyclase</td><td>Inhibition of lipolysis</td><td>Constriction of blood vesselsa</td></tr></table>


Note that the β-adrenergic receptors have not been subdivided here: see text, Section 6.2.4.2. 



a Peripheral (post-ganglionic) α receptors. 


![image](/assets/images/human_metabolism_images/ca07b50d1f1104beaec2359aef72693a.jpg)



Figure 6.11 Propranolol (a β-adrenergic blocker) inhibits lipolysis in response to exercise. The figure shows changes in the concentration of glycerol (released in fat mobilisation) in the interstitial fluid in adipose tissue, measured with a small probe. During exercise (0–30 minutes) the glycerol concentration rises, indicating lipolysis. When propranolol is introduced (via the probe) the rise is largely inhibited (see text for an explanation of the component of lipolysis that is not inhibited by propranolol). In separate experiments, when phentolamine (an α-adrenergic blocker) was introduced, glycerol release was not affected. Source: based on Arner, P., Kriegholm, E., Engfeldt, P., & Bolinder, J. (1990) J. Clin. Invest. 85: 893–898. Copyright 1990 by American Society for Clinical Investigation. Reproduced with permission of American Society for Clinical Investigation.


Overall, the net effects of adrenaline and noradrenaline will depend upon the relative abundance of the different types of adrenergic receptor in a tissue, as well as on the concentrations of other hormones. To put it into perspective, if adrenaline is injected or infused (given as a slow injection, over perhaps an hour) into human volunteers to raise the level in the blood to the upper limit of levels seen in normal everyday life, the major changes noted are an increase in heart rate and a rise in the concentrations of glucose and non-esterified fatty acids in the blood; thus, the net metabolic effect of catecholamines appears to be mobilisation of the stores of glycogen and triacylglycerol. There is also an increase in oxygen consumption, reflecting a general increase in metabolism. If very high levels are infused, then somewhat different changes may be observed, with restriction of blood flow in certain tissues and some inhibition of metabolic processes. 

## 6.2.5 ‘Metabolic tissues’ that secrete hormones

In recent years the idea of specific endocrine organs has been challenged. Several organs that we might think of as ‘metabolic’ (or as targets for conventional hormone action) are now known to secrete hormones themselves. Actually, that is not a surprise: we saw in Chapter 4 how enteroendocrine cells in the gastrointestinal tract secrete hormones, some of them among the first hormones to be discovered. The discovery in 1994 of leptin secreted from adipose tissue (Section 6.2.5.1) was another landmark in this field of investigation. 

## 6.2.5.1 Adipose tissue

White adipose tissue is now recognised as an important endocrine organ, as well as a tissue involved in fat storage and mobilisation. Several decades ago it was recognised that adipose tissue could produce certain steroid hormones, including oestrogens (estrogens in American literature) (female sex hormones). This is because cells within adipose tissue (probably mainly cells other than the adipocytes) express the enzymes to interconvert steroid hormones. Oestrogens (such as oestradiol, US: estradiol) can be produced from androgens (such as androstenedione) that are produced by the adrenal cortex (Section 6.2.4.1). This has important ramifications. In obesity, when there is an excess of adipose tissue, more oestrogens may be produced. That has some beneficial effects: obese postmenopausal women (whose ovaries no longer produce oestrogens) are somewhat protected from osteoporosis, compared with lean women, because of this. On the other hand, persisting high oestrogen concentrations in obese women increase the risk of certain cancers. The hormone cortisol is also produced from the inactive precursor cortisone. That may have untoward effects in obese men, adding to a metabolic ‘stress’ state. 

The first recognition that a true hormone could be synthesised in, and secreted from, white adipose tissue came in 1994 with the identification by Jeff Friedman and colleagues at Rockefeller University (New York) of a peptide hormone, now called leptin (from the Greek λϵρτόζ (leptos), thin), secreted by adipocytes. Friedman was chasing the gene mutation underlying the so-called ob/ ob mouse, which becomes naturally very obese. 

The larger an adipocyte, the more leptin it produces and secretes, and the more adipocytes that are present in the body, the more leptin is produced. Leptin signals through receptors in the hypothalamus to restrict energy intake (i.e. to reduce appetite). In small animals it also signals to increase energy expenditure through activation of the sympathetic nervous system. The system is illustrated in Figure 6.12. (More details of appetite regulation by leptin and other signals will be given later, in Box 11.1.) Leptin can be produced in bacteria by recombinant DNA techniques. When this recombinant leptin is injected into ob/ob mice, they reduce their food intake, their energy expenditure increases, and they become lean. Leptin is also an important signal to the reproductive system. The ob/ob mouse is infertile but becomes fertile when treated with leptin. Low levels of leptin, implying low fat stores, signal to the reproductive system that the body does not have adequate energy reserves to embark upon child-bearing and rearing. (Note that although the ob/ob mouse is fat, the brain and reproductive organs see no leptin, so ‘think’ they are part of a very thin animal.) 

The leptin system undoubtedly operates in humans (see Chapter 11). In humans, low levels of leptin are a powerful signal to the brain to increase appetite. This is a defence against starvation. But high levels, as seen in many obese people, do not necessarily switch off appetite very effectively, a phenomenon that has been called leptin resistance. We will return to the role of leptin in body weight regulation in Chapter 11. 

Leptin is a single-chain polypeptide hormone (16 kDa, 167 amino acids in humans). There are various isoforms of the leptin receptor, but one, known as OB-Rb (gene LEPR) or the long-form leptin receptor, is the active form with an extracellular hormone-binding region and an intracellular 

![image](/assets/images/human_metabolism_images/1e4e3b14f5a7c39c0648942fdbff4cf8.jpg)



Figure 6.12 The leptin system and regulation of fat stores. Leptin is produced in, and secreted from, adipose tissue according to the extent of the fat stores. Leptin signals to the brain (hypothalamus) to (i) reduce energy intake, and (ii) increase energy expenditure (the latter has only been shown convincingly in small animals). When fat stores are depleted, low leptin levels signal to the brain to (i) increase energy intake, and (ii) reduce energy expenditure. The system was discovered in the spontaneously obese ob/ob mouse, which has a defective leptin gene. Therefore, the brain of the ob/ob mouse ‘thinks’ that it is connected to a small fat mass and increases energy intake, while in fact the fat mass expands and expands.


signalling domain. Other, short-form, leptin receptors may be involved with leptin transport. For instance, leptin must cross the blood–brain barrier to act on the long-form receptors expressed in the hypothalamus, and short-form receptors expressed in the choroid plexus (part of the blood– brain barrier) may facilitate this. 

Along with leptin, which is certainly a true hormone, we now recognise adipose tissue to produce a number of other proteins, many of which are relevant to energy metabolism. One, of course, is lipoprotein lipase (see Section 5.2.2.1 and Figure 5.9). Others include apolipoprotein E and cholesteryl ester transfer protein (both relevant to lipid metabolism: see Chapter 10), a number of cytokines (peptides that signal between cells and play a role in inflammatory responses), proteins involved with blood clotting, and a number of components of the complement pathway involved in immunological defences. These are often now generally called adipokines. One particular adipokine is the 30  kDa protein adiponectin. The regulation of adiponectin secretion is the opposite of that of leptin: smaller adipocytes secrete more adiponectin. Plasma adiponectin concentrations are therefore approximately inversely related to central (abdominal) fat mass. Adiponectin has many ‘beneficial’ effects on metabolism, some at least mediated by activation of the enzyme AMP-kinase (AMPK, see Box 3.3). These include sensitising tissues to insulin, anti-inflammatory effects and increased survival of pancreatic β-cells. 

## 6.2.5.2 Heart

Some cells in the upper chambers of the heart, the atria, have long been known to contain granules that, under the electron microscope, look like hormone secretory granules. In 1980, it was shown that they are indeed granules of the hormone now called ANP (sometimes called atrial natriuretic factor), a peptide with 28 amino acids. Natriuretic means that this hormone travels from the atria of the heart to the kidney, where it stimulates the loss of sodium in the urine (natriuresis). Excretion of sodium is associated also with excretion of water, so this is a means of reducing the amount of fluid in the circulation. When blood volume is increased, or blood pressure rises, the atria sense this as ‘overload’; secretion of ANP then leads to a compensatory loss of volume, with a reduction in pressure. The system is the counterpart to the action of aldosterone (Sections 6.2.4.1 and 6.2.5.3), which causes sodium (and fluid) retention and tends to raise blood pressure. 

In 1988, a related peptide was discovered, secreted from the brain. This was called brain natriuretic peptide (BNP), although we now know that BNP in the circulation mostly arises, like ANP, from the atria of the heart. BNP is derived from a different gene from ANP and has 32 amino acids. A raised level of BNP is an extremely sensitive marker of the condition of heart failure, in which chronic overload of the heart leads to dilated chambers and inefficient pumping. 

ANP and BNP both act via a GPCR, natriuretic peptide-A receptor (NPR-A). A related receptor, NPR-B, is the target for a related peptide, CNP. A third receptor, NPR-C, is thought to be the means by which the natriuretic peptides are cleared from the circulation. NPR-A activates the enzyme guanylate cyclase, which generates cyclic GMP (cGMP) (see Box 3.3). The relevance of this system to metabolism has only recently been discovered. Human adipocytes express NPR-A, and it was shown in the year 2000 that ANP is a potent stimulator of adipocyte lipolysis (see Figure 5.8). This system operates in parallel with β-adrenergic activation of lipolysis. It is particularly relevant during exercise, when ‘stress’ on the heart leads to release of ANP, and this increases fat mobilisation to meet metabolic demands. The system does not operate in rodents. 

Neprilysin is a renal peptidase that degrades ANP. Pharmacological inhibition of this enzyme prolongs the life (and hence increases the plasma concentration) of ANP, and this is useful in the treatment of heart failure when used in combination with an angiotensin receptor blocker (ARB) (see Section 6.2.5.3). 

## 6.2.5.3 Kidney

The kidney secretes an enzyme into the circulation, renin, that in turn produces a hormone. This is the start of the renin-angiotensin system (RAS), sometimes called the renin-angiotensin-aldosterone system (RAAS). Secretion of renin is stimulated by a low blood pressure in the capillaries of the kidney. Renin is a peptidase and acts on a circulating peptide, angiotensinogen. The ‘-ogen’ ending will be familiar from the peptidases secreted into the gastrointestinal tract (see Table 4.2): it denotes an inactive precursor which becomes active after proteolytic cleavage. In this case, renin cleaves the 11-amino acid peptide angiotensinogen (which is secreted from the liver and is always present in the circulation) by removing the C-terminal valine. The 10-amino acid peptide thus produced is angiotensin I. This is further cleaved by an enzyme known as angiotensin-converting enzyme (ACE), which is present in capillaries, especially in the lung. The two C-terminal amino acids are removed, to produce the active peptide angiotensin II. The whole process of angiotensin II generation is regulated by the initial release of renin from the kidney. 

Angiotensin II is a hormone and acts on cell-surface GPCRs, $\mathrm { A T } _ { 1 } ,$ and AT . AT mediates most of the cardiovascular effects. Its main effects are: the release of the mineralocorticoid aldosterone from the adrenal cortex (Section 6.2.4.1), facilitation of heart contraction, activation of the sympathetic nervous system via the brain (Section 6.3.2.2), and constriction of blood vessels. Aldosterone in turn leads to retention of salt (and fluid) by the kidney. All those tend to raise blood pressure, so this system is part of the homeostatic regulation of the cardiovascular system. 

Because of its role in regulation of blood pressure, the RAS has been targeted by the pharmaceutical industry to lower elevated blood pressure. Drugs that block the action of ACE (ACE inhibitors) prevent the formation of the active angiotensin II. They have been in use since the 1970s. More recently, drugs that block the AT receptors for angiotensin II have been introduced, the angiotensin receptor blockers or ‘ARBs.’ Only in 2007, a new drug was introduced, aliskiren, that inhibits the action of renin, so preventing initiation of the cascade. 

The outline of the RAS was discovered in 1898. In recent years it has become apparent that RAS components are expressed in many tissues, leading to the operation of ‘tissue RASs.’ These tissue RASs amplify the actions of circulating angiotensin II and regulate local cell proliferation, blood flow, and inflammation. Such systems have been identified in kidney, blood vessels, heart, brain, adipose tissue, and recently the gastrointestinal tract. There is strong evidence that the RAS, or at least ACE, is involved in energy metabolism in a more direct way. Mice made deficient in ACE have increased energy expenditure and remain leaner than wild-type controls, even with the same food intake. In addition, there is very consistent evidence that genetic variation in ACE is related to endurance exercise capacity, and the ability to benefit from physical training. 

In addition, the kidneys secrete one ‘genuine’ hormone, erythropoietin, a glycoprotein hormone that stimulates erythrocyte (red blood cell) production. The stimulus for this is a decrease in oxygen concentration, sensed by the hypoxia-sensing system, described earlier in Section 2.4.2.5. The kidneys are also the site of formation of 1,25-dihydroxycholecalciferol (also known as calcitriol), the active form of Vitamin D, which is a true hormone. It signals via a nuclear receptor, the Vitamin D receptor, and regulates calcium and phosphate homeostasis as well as other aspects of development. 

## 6.2.5.4 Skeletal muscle

Following the discovery of the wide range of peptides secreted from adipose tissue, researchers have investigated whether anything similar might occur in skeletal muscle. The earliest documented phenomenon is that, during exercise, skeletal muscle cells secrete the cytokine interleukin-6 (IL-6). IL-6 signals to the immune system and is part of the cascade of events that lead to an inflammatory response. This could simply be a reflection of damage to the muscle fibres that occurs during strenuous exercise (so initiating repair mechanisms), but some exercise physiologists believe that IL-6 is part of a system for coordinating metabolic responses. There is evidence that IL-6 released during exercise increases hepatic glucose production, and even that it signals to adipose tissue to increase lipolysis. Other proteins secreted by skeletal muscle have been identified and are now known as myokines. They include other interleukins related mainly to inflammation, which may act in autocrine (acting back on the same cell), paracrine (acting within the tissue), or hormone-like fashion. Myostatin is an inhibitor of muscle growth, acting in an autocrine fashion, and will be discussed again in Section 9.4.2. Irisin is a 112-amino acid peptide, derived from fibronectin type III domain-containing protein 5 (FNDC5), and secreted from skeletal muscle and adipose tissue. Expression of the FNDC5 gene is stimulated by the transcriptional co-activator PGC-1α (Section 2.4.2.5). Irisin is secreted after exercise and leads to increased energy expenditure via induction of ‘browning’ of white adipose tissue (Section 5.2.3.1), together with improvements in glucose metabolism and sensitivity to insulin. However, although that story seems convincing in mice, there is still uncertainty about its importance in humans. 

## 6.2.5.5 The gastrointestinal tract

We have already seen that the intestinal tract, including the stomach, is the source of several hormones that regulate intestinal motility and secretions involved in digestion (Chapter 4). 

The stomach is the site of secretion of the peptide hormone ghrelin. Ghrelin was first named when it was believed to act as growth hormone-releasing peptide. Now we know that its major role is to act on the hypothalamus to regulate appetite. Ghrelin is released when the stomach is empty, and signals to increase appetite. It is synthesised as a pre-pro-hormone, preproghrelin, and modified by proteolysis to a 28-amino acid peptide. However, it is not active until modified by the addition of an 8-carbon octanoic acid residue to one of its serine residues by the enzyme ghrelin-O-acyltransferase (GOAT). (For description of protein acylation see Box 2.4.) Ghrelin acts through a GPCR, the growth hormone secretagogue receptor (GHSR). 

The small and large intestines are also the source of hormones that affect metabolism in the rest of the body through an indirect route, effects on insulin secretion. Glucose, given either orally or intravenously (directly into the bloodstream), stimulates insulin secretion. It was observed in the 1960s that if the amounts of glucose were chosen so that the same ‘excursion’ in plasma glucose concentrations were achieved, then considerably more insulin was secreted following oral than intravenous glucose. It appeared that hormones secreted from the gut in response to glucose ingestion amplified the effect of glucose on the pancreatic β-cell. These hormones have become known as incretins (Figure 6.13). 

There are two important incretins in humans. One is glucagon-like peptide-1 (GLP-1). This is secreted from the enteroendocrine L-cells scattered among the epithelial cells of the intestinal wall. Like several other hormones we have met in this chapter, 

![image](/assets/images/human_metabolism_images/279695209076203605737cc68fd6d6a2.jpg)


![image](/assets/images/human_metabolism_images/05282741464c1d874b646f8474bd1861.jpg)



Figure 6.13 The idea of ‘incretins’ (gut-derived hormones that augment insulin secretion).


Volunteers received either an infusion of glucose directly into their duodenum or an equal infusion into a vein. The plasma glucose concentration (top panel) rose considerably more with the intravenous infusion. But the response of plasma insulin (lower panel) was greater with the duodenal glucose infusion, despite the lower plasma glucose concentration. Therefore, some factor associated with glucose in the small intestine must augment glucose-stimulated insulin secretion. As discussed in the text, the major incretins are glucagon-like peptide-1 and gastric inhibitory polypeptide (GIP) (which was studied in this paper). Source: adapted from McCullough, A. J., Miller, L. J., Service, F. J., & Go, V. L. W. (1983) J. Clin. Endocr. Metab. 56:234–241 with permission, Copyright 1983, The Endocrine Society. 

GLP-1 is a fragment of a larger prohormone, actually proglucagon, the precursor of pancreatic glucagon (Section 6.2.1.3). Cleavage of proglucagon in the enteroendocrine cells gives rise to two active products, known as GLP-1 and GLP-2. They get their name because they are similar in sequence to (pancreatic) glucagon, although not identical (approximately 50% amino acid identity). GLP-1 has a number of actions that include inhibition of gastrointestinal motility, but in addition it has a specific effect on the pancreatic β-cell, ‘amplifying’ glucose-stimulated insulin secretion. The other important incretin in humans is gastric inhibitory polypeptide (GIP) (also known as glucose-dependent insulinotrophic polypeptide) (Section 4.2.3.3). Both act via GPCRs expressed in the β-cell. 

## 6.3 The nervous system and metabolism

Hormones are signals that travel between tissues in the bloodstream: they could be considered analogous to posting letters (‘snail mail’). However, all complex animals have another system of communication, the nervous system, which might be considered more analogous to ‘email.’ Although the nervous system is not often considered in discussions of metabolic regulation, in fact it plays a very pervasive role, especially under conditions of rapid change or ‘stress.’ 

## 6.3.1 Outline of the nervous system as it relates to metabolism

## 6.3.1.1 The nerve cell

Nerve cells, also known as neurones, have a number of distinctive properties. They may be very long and thin (spinal cord to toe length, for instance). They are very long-lived (in many cases the lifetime of an individual) but cannot divide by mitosis; hence, if a nerve cell is destroyed, it cannot be replaced by cell division. They have a very high rate of metabolism, requiring glucose and oxygen to support this, and if deprived of oxygen for more than a few minutes will die. 

All nerve cells have a cell body, an enlarged part in which are found the nucleus and all the biosynthetic apparatus of the cell (including rough endoplasmic reticulum), from which extend various projections. The dendrites are multiply-branched extensions from the cell body, involved in receiving information from the environment and other nerve cells. The axon is a long, slender, usually unbranched projection, extending from the cell body to the point where the nerve cell will exert its effects. At the distal end (far end) the axon may branch, extending several ‘feet’ to the target tissue or organ (Figure 6.14). 

At the end of each ‘foot’ of the axon, contact is made with another neurone or with another type of cell through the structure known as a synapse. The synapse is formed by a swelling on the end of the axon facing, across a small space known as the synaptic cleft, a specialised receptor area on the cell which will receive the signal. There are two sorts of synapses. Electrical synapses occur between two neurones; ion channels effectively connect the cytoplasm of the two cells, and the electrical signal being transmitted along one continues almost without interruption along the next. However, more relevant from the point of view of regulation of metabolism are the chemical synapses. At a chemical synapse, vesicles containing a neurotransmitter substance are stored within the swelling at 

![image](/assets/images/human_metabolism_images/2e4c7e9e380e361c35d142210507c48c.jpg)



Figure 6.14 Basic structure of a nerve cell (neurone).


## Box 6.1 The membrane potential and nerve impulses

An axon is a prolongation of a cell (Figure 6.14). As in all cells, the cytoplasmic K⁺ concentration (about 150 mmol L⁻¹) is considerably greater than that outside (in the interstitial fluid and plasma – about 5 mmol L⁻¹). The nerve cell membrane is selectively permeable to K⁺ ions, which therefore diffuse out (through specific K⁺ channels) down their concentration gradient. They take with them positive charge – leaving the interior of the cell with a negative charge relative to the outside. This is known as the resting membrane potential. It can be measured with a voltmeter in a large nerve and is about −70 mV. (The negative sign is conventional, implying that the inside is negatively charged with respect to the outside.) Na⁺ ions have the opposite distribution: they are present at higher concentration outside (about 150 mmol L⁻¹) than inside (about 15 mmol L⁻¹). However, the membrane is less permeable to Na⁺ ions than to K⁺ ions, so the potential difference is maintained. In addition, nerve cell membranes contain the Na⁺-K⁺-ATPase, which pumps out three Na⁺ ions in exchange for two K⁺ ions from outside (and uses ATP for this). This further maintains the resting membrane potential (since there is a net outward movement of positive charge). This is illustrated in the top panel of Figure 6.14.

The above is true for most cells. However, nerve cells and skeletal muscle cells have the characteristic of excitable membranes (Figure 6.1.1, lower panel). They possess proteins in the membrane that are voltage-gated sodium channels: they have pores which can be opened to allow ${ \mathsf { N a } } ^ { + }$ ions to pass through, but these pores are normally closed by the negative membrane potential. An action potential is started by depolarisation of the membrane (i.e. the negative membrane potential is lost) in a specific area. This allows the opening of voltage-gated sodium channels in adjacent parts of the membrane, so that $\mathsf { N a } ^ { + }$ ions can flow in (down their concentration gradient), thus depolarising yet more of the membrane. Thus, this depolarisation spreads like a wave (the nerve impulse) along the length of the axon. It passes any one point very rapidly; as sodium ions flow in and the local membrane potential falls to zero (or becomes positive) the entry of further sodium ions is restricted. In addition, voltage-gated potassium channels open a short time after the voltage-gated sodium channels, allowing $\mathsf { K } ^ { + }$ ions to leak out again. The normal resting membrane potential is therefore re-established after about 2 ms. 

![image](/assets/images/human_metabolism_images/6a38832c71b6966759b042ac2791b68d.jpg)



Passage of an action potential


![image](/assets/images/human_metabolism_images/a1a0e2ad0b8d68e7570fac9a1476f8a0.jpg)



Figure 6.1.1


![image](/assets/images/human_metabolism_images/2322c3de43d1ec3efe6775e08268907f.jpg)



Acetylcholine


![image](/assets/images/human_metabolism_images/206605217649d3368d691662d82b87c6.jpg)



Noradrenaline



(US: norepinephrine)



Figure 6.15 The structures of two important neurotransmitters, acetylcholine, and noradrenaline. Acetylcholine is a neurotransmitter in the parasympathetic nervous system, parts of the sympathetic nervous system and in the somatic nervous system responsible for activating muscle contraction. Noradrenaline is a neurotransmitter in the peripheral parts of the sympathetic nervous system. The route of synthesis of noradrenaline was given in Figure 6.10.


the end of the axon. There are a great many neurotransmitters used by different neurones, but of particular relevance to us will be acetylcholine and noradrenaline (Figure 6.15). When an electrical impulse arrives, the neurotransmitter substance is released into the synaptic cleft and acts on receptors on the target cell. The nature of a nerve impulse, and the events occurring at a synapse, are discussed in Boxes 6.1 and 6.2. 

A synapse may be with another neurone. Alternatively, it may be with a muscle cell, in which case it is called a neuromuscular junction, or with an endocrine cell, in which case it is sometimes known as a neuroglandular junction. The neuromuscular junction is a specialised structure, activation of which leads to muscle contraction. It will be considered in more detail later (Section 6.3.2.2). 

When we speak of a nerve in the anatomical sense, that refers to a specialised structure containing a number of axons and associated supporting cells, together with fine blood vessels. 

## Box 6.2 Synaptic transmission

A synapse is where an axon makes contact with another cell. When an action potential (Box 6.1) reaches the synaptic terminal (or axonal terminal), it leads to opening of voltage-gated calcium channels, which allow extracellular $\mathsf { C a } ^ { 2 + }$ ions to enter the cell; these lead (as in other secretory cells) to exocytosis of the secretory vesicles containing the neurotransmitter. Exocytosis involves the granules – each of which is surrounded by a phospholipid membrane – fusing with the synaptic membrane and discharging their contents into the space outside, the synaptic cleft (Figure 6.2.1). 

The neurotransmitter molecules can then diffuse across the narrow gap of the synaptic cleft and bind to specific receptors on the target cell membrane. Events then depend upon the nature of the target cell. It may be another neurone, in which case binding of the neurotransmitter will open ion channels and begin the passage of an action potential along the new neurone. If it is a skeletal muscle cell, the result will be increased permeability to ${ \mathsf { N a } } ^ { + }$ ions, depolarisation spreading across the membrane and the opening of $\mathsf { \bar { C } a } ^ { 2 + }$ channels which allow $\mathsf { C a } ^ { 2 + }$ ions to enter the intracellular space; it is these $\mathsf { C a } ^ { 2 + }$ ions which trigger muscle contraction. On the other hand, the target cell may not be another excitable cell. If the neurotransmitter is noradrenaline, the target cell may have β-adrenergic receptors; binding of noradrenaline to these will activate (through the G-protein system) adenylate cyclase and raise the cellular level of cAMP. 

(Continued) 


Box 6.2 Synaptic transmission (continued)


![image](/assets/images/human_metabolism_images/874505f828b913b1a535272dca977584.jpg)



Figure 6.2.1


## 6.3.1.2 Layout of the nervous system

There are a great many neurones in the body, performing a wide variety of functions, although the nervous system as a whole is highly integrated, and also interacts with many other bodily systems. However, the nervous system can be subdivided in certain ways according to the general function of different groups of neurones. 

The term central nervous system (CNS) refers to the brain and spinal cord. The peripheral nervous system refers to other parts of the nervous system, mainly nerves running to and from the spinal cord (spinal nerves) and to and from the brain (cranial nerves). This is a structural definition. There is also a functional classification: 

(1) The autonomic nervous system, nerves carrying impulses from the CNS to other organs and tissues. This part of the nervous system cannot be controlled voluntarily – it seems to be autonomous, hence its name. (It is sometimes referred to as the involuntary nervous system.) It controls functions such as heart rate, some aspects of digestive function, and some aspects of hormone secretion and of metabolism. The autonomic nervous system can be subdivided into: 

the sympathetic nervous system, which acts as though ‘sympathetic’ to the body’s needs; it speeds up the heart when we are excited or exercising, for instance. This is generally counteracted by: 

the parasympathetic nervous system, which appears in many ways to counter the sympathetic system; for instance, it slows the heart. 

(2) The somatic nervous system comprises the nerves that run from the CNS to the skeletal muscles, causing them to contract. It is sometimes called the voluntary nervous system, since we can activate specific parts of it voluntarily (e.g. lift a hand to scratch our nose). 

(3) The afferent nervous system refers to those nerves which bring signals from tissues and organs back to the CNS. This includes, for instance, signals from pain receptors, chemoreceptors monitoring the pH of the blood, and receptors monitoring the presence of digestion products in the intestinal tract; we have met some examples of these under the consideration of digestion (Chapter 4). 

(4) A fourth component of the nervous system, the enteric nervous system, regulates gastrointestinal function. This is closely connected with both the sympathetic and the parasympathetic nervous systems, but also functions to some extent autonomously, with local ‘circuits’ so that one part of the intestinal tract can regulate the function of another without the involvement of the CNS. It is highly complex and will not be considered further here. 

## 6.3.2 Physiology of the nervous system

The operation of the nervous system is highly integrated; there are interconnections between neurones so that one affects the functioning of another (in either an excitatory or inhibitory way), local ‘feedback loops’ and other interactions. In a simple way we can look on it as follows. For the most part nervous signals travel either towards the brain (afferent signals) or outwards from the brain (efferent signals). The brain is the great integrating centre. It receives signals from receptors all over the body: mechanical  –  pressure, stretch, and so on; chemical  –  pH, presence of food in the intestine, and so on; ‘noxious’  –  pain, damage; special senses  –  vision, hearing, smell, and so on. It then collates and integrates them and sends out signals via the autonomic and somatic branches of the nervous system to regulate bodily function appropriately. The nature of the afferent (incoming) nervous system is largely outside the scope of this book, although we have seen some examples, and will see more, of its relevance to metabolic regulation. 

## 6.3.2.1 The brain

The brain is composed of a great many cell types, organised in a highly structured manner. It has a high rate of blood flow, and therefore nutrient supply (Section 5.6). Among the many cell types found in the brain, neurones themselves are outnumbered approximately nine times by glial cells (from the Greek γλία for glue). These glial cells perform many functions of mechanical support and electrical ‘insulation,’ protection against infection, and repair of damage. The most abundant type, the astrocytes (so-called because of their star shape, with multiple radiating projections), probably act as intermediaries between the capillaries and the neurones, regulating the supply of nutrients and also the extracellular ionic environment. In recent years it has been realised that glial cells can themselves transmit signals, in the form of calcium waves that pass between glial cells and can also communicate with neurones. It is not yet understood what part glial cells may play in information processing within the CNS. 

The brain contains both complete neurones and the cell bodies of neurones that extend into the spinal cord and beyond. It is organised into several relatively discrete structural parts (Figure 6.16). The two cerebral hemispheres are the most prominent part. In fact, they are roughly quarter spheres, together making up about one hemisphere, but the terminology is unlikely to change. The outer layer, a few millimetres thick, contains many cell bodies and is referred to as grey matter because of its appearance when fixed with alcohol for microscopy. It forms the cerebral cortex and is responsible for many higher functions: receipt of information from the special senses and motor control (control of muscles). The cerebral cortex, although only 2–4  mm thick, occupies a large proportion of brain volume (around 40%) because of the many convolutions of the brain surface and, hence, large surface area. Underlying the cortex is the cerebral white matter (again from its appearance when fixed with alcohol), largely composed of myelinated fibres grouped into large bundles, responsible for transmission within the brain. Among the white matter are found a number of local regions of grey matter, known as nuclei, where there are further groups of cell bodies. These nuclei have names and their functions are becoming clear, but more detailed description is beyond the scope of this book. Within the cerebral hemispheres is the central core of the brain, the diencephalon, a structure itself composed of three parts  –  the thalamus, underneath which is the hypothalamus with the epithalamus behind. 

![image](/assets/images/human_metabolism_images/e3cf8e858830d5fac3ea14242cc6773e.jpg)



Figure 6.16 The human brain and its main components.


## 6.3.2.1.1 The hypothalamus

The hypothalamus is the region of the brain of most interest with respect to metabolic regulation. It is an integrating centre: it receives information and also sends it out. It receives information from other brain areas but, in addition, the hypothalamus itself contains important sensors. It monitors the concentration of glucose in the blood and initiates appropriate responses to maintain this close to a constant level of around 4–5 mmol l−1 . (This includes both autonomic responses, e.g. initiation of glycogen breakdown in response to a fall in blood glucose concentration, and regulation of dietary intake by control of appetite.) The hypothalamus also senses fluid balance by monitoring the osmolarity of the blood and initiates appropriate measures to maintain an optimal level (both via regulation of thirst and control of water excretion by the kidneys). It has a temperature-sensitive region, monitoring the temperature of blood flowing through it and responding as appropriate to maintain the required body temperature. This includes elevation of the body temperature during infection. The hypothalamus also receives information about how much fat is stored in the body, via leptin secreted from adipocytes and insulin from the pancreas. At least in rodent models, it has also been shown that insulin acts on the hypothalamus to regulate nerve signals to the liver, which in turn modulate hepatic glucose production. Note that glucose metabolism in the brain as a whole is not insulin sensitive, but clearly insulin can reach certain regions and affect metabolism locally. 

The hypothalamus controls drives such as thirst and appetite by signalling to other brain areas. It regulates other bodily functions in two main ways. It is responsible for most of the output of the sympathetic nervous system. Signals from the hypothalamus are transmitted via other brain centres to the sympathetic tracts within the spinal cord, and thus to tissues and organs within the body. It also regulates the secretion of hormones by the pituitary gland. Connections between the hypothalamus and pituitary were discussed in Section 6.2.2. Thus, the hypothalamus is a very important part of the brain in terms of the role of the nervous system in metabolic regulation. The term neuroendocrine system is often used to describe the combination of nervous and hormonal systems of regulation, and the hypothalamus is at the centre of this combination. 

## 6.3.2.1.2 The cerebellum and brainstem

Other parts of the brain act as further regulatory centres and as ‘relay stations’. The cerebellum has important functions in coordinating movement; disorders of cerebellar function can lead to uncoordinated movements, trembling, and so on. The brainstem is the connection between higher centres of the brain and the spinal cord. It is analogous to a primitive brain and regulates very basic functions such as heart rate, breathing, and blood pressure in a ‘pre-programmed,’ automatic manner. Thus, if the spinal cord is severed from the brainstem, these vital functions cease. On the other hand, if the brainstem remains intact after severe injury to other parts of the brain, the victim can enter a state of primitive existence in which consciousness is absent, but life can be maintained so long as food is provided – the state sometimes called ‘vegetative existence.’ 

## 6.3.2.2 The autonomic nervous system

## 6.3.2.2.1 The sympathetic nervous system

The nerves of the sympathetic nervous system are carried in the spinal cord in discrete bundles known as the sympathetic trunks. There are synapses between neurones arranged ‘in series’ (one follows another), and the cell bodies of the neurones which eventually emerge from the spine are located in the thoracic and lumbar regions of the spine (the back of the chest and the lower back). Their axons emerge from between vertebrae and reach out towards other parts of the body. At this stage the sympathetic nerves mostly make chemical synapses with other cells, using the neurotransmitter acetylcholine (Figure 6.15). Only one branch of the sympathetic nervous system reaches its target tissue directly: that controlling the adrenal medulla (discussed in Section 6.2.4.2). Thus, the nerves regulating the adrenal medulla liberate acetylcholine to cause it, in turn, to release the hormone adrenaline into the blood. However, most branches of the sympathetic nervous system emerge from the spinal cord and then meet groups of cell bodies, located near the spine, called sympathetic ganglia (each one is called a ganglion). The ganglia are relay stations. The terminals of the sympathetic nerves synapse with new neurones. The fibres emerging from the spinal cord, the preganglionic fibres, liberate acetylcholine, and this excites the new fibres to transmit impulses. However, the neurotransmitter used by these new fibres, the postganglionic fibres, is not (for the most part) acetylcholine but noradrenaline (Figure  6.15). Noradrenaline is regarded as the characteristic neurotransmitter of the sympathetic nervous system, although you will see that this only applies to transmission of signals to the target tissues. As we already know, noradrenaline can interact with receptors on other tissues, and these receptors are broadly classified as α- or β-adrenergic receptors (Section 6.2.4.2). 

There are some exceptions to this rule. For instance, the sympathetic nervous system controls sweat secretion via cholinergic fibres (i.e. using acetylcholine as their transmitter). In addition, the sympathetic nervous system has cholinergic fibres that innervate the blood vessels in skeletal muscle to cause relaxation of the vessels. The significance of this will be considered in more detail later (Section 8.2.5). But most aspects of metabolism that it controls involve adrenergic impulses (i.e. liberation of noradrenaline). 

## 6.3.2.2.2 The parasympathetic nervous system

The parasympathetic nerves do not, for the most part, run in the spinal cord. Those fibres regulating functions in the head and face – for example, salivary secretion, contraction of the pupils of the eyes  –  are cranial nerves. The most important branch of the parasympathetic nervous system from the point of view of metabolic regulation is a large nerve called the vagus nerve (see Section 4.2.2.3). The vagus is also a cranial nerve; that is, it emerges directly from the brain and a branch runs down the neck close to the carotid artery. It divides and its branches run to various organs, particularly the heart and stomach, other parts of the digestive tract, and the pancreas. (We saw the importance of parasympathetic regulation of the production of saliva and gastric secretions in Chapter 4.) 

The neurotransmitter of the parasympathetic nervous system is acetylcholine. Thus, blockers of cholinergic transmission block its effects. One of the classic blockers is the substance atropine found in the deadly nightshade plant, Atropa belladonna. We saw in Chapter 4 that the parasympathetic nervous system stimulates the flow of saliva, and one of the effects of low doses of atropine is a dry mouth. The parasympathetic nerves usually contract the muscles controlling the size of the pupil of the eye; when this action is inhibited, the pupil dilates and becomes unresponsive to light. Eye drops containing extracts of deadly nightshade were used by the Greeks and Romans to produce ‘beautiful ladies’ – hence the name belladonna for the plant. Larger doses of atropine block the normal restraining effect of the parasympathetic system on the heart rate; hence the heart speeds up (in overdose it is a poison – hence ‘deadly’ nightshade: Atropos was the Greek fate who cut the thread of life). 

## 6.3.2.2.3 The somatic nervous system

The nerves of the somatic nervous system (except those supplying the muscles of the head, neck, and face) run down the spinal cord and emerge again between the vertebrae. They do not form further synapses but run directly to the muscles that they stimulate. Their neurotransmitter is acetylcholine. The nerve terminals meet the muscle cells at the specialised structures known as neuromuscular junctions (Figure 6.17). Here, acetylcholine is released when the nerve is activated. The flattened, branching end of the axon is known as the endplate; it makes contact with a receptive area on the muscle cell membrane (the sarcolemma) called the sole-plate. We will look in more detail at the effects of activation of the motor neurones supplying skeletal muscle in Section 8.2.5. 

![image](/assets/images/human_metabolism_images/3e698ccbf93a25e7fb59d8a0500fec56.jpg)



Figure 6.17 The neuromuscular junction.


## 6.3.2.3 Neurotransmitters and receptors

There are many neurotransmitters, including amino acids and derivatives, amines, peptides, and acetylcholine. Much of the diversity of transmitters occurs within the CNS and also within the enteric nervous system. With regard to metabolic regulation, we will be considering mainly adrenergic and cholinergic transmission. 

## 6.3.2.3.1 Adrenergic transmission

The pathway for synthesis of noradrenaline and adrenaline was shown in Figure 6.10. Dopamine (the biosynthetic precursor of noradrenaline) is also a neurotransmitter in the CNS. The sympathetic nerve terminals release noradrenaline, although a small amount of dopamine (present in the secretory vesicles) is co-secreted. The adrenal medulla is, in effect, a modification of a postganglionic neurone – it is, as we have seen, stimulated by a (cholinergic) preganglionic fibre and has evolved to secrete the hormone adrenaline into the bloodstream rather than noradrenaline into a synaptic cleft. Note from Figure 6.10 that adrenaline is one biosynthetic step beyond noradrenaline. 

Adrenaline and noradrenaline, which are similar in structure, act through the same adrenoceptors, in a molecular sense (Section 6.2.4.2). The two sub-families of adrenergic receptors, α and β, and the subdivisions of these receptors, were discussed in connection with adrenaline action in Section 6.2.4.2 and Table 6.1. However, some receptors (for instance, those on the receiving side of a synaptic cleft) will only ‘see’ noradrenaline, whereas others more exposed to the circulation will respond to adrenaline carried in the blood. After noradrenaline has been liberated into the synaptic cleft, it is rapidly taken up again, both back into the synaptic terminal (for recycling) and into other tissues. A proportion ‘escapes’ re-uptake and enters the extracellular fluid, and thence the plasma. The concentration of noradrenaline in the plasma is, in fact, usually higher than that of adrenaline, although it is only there through this ‘spillover’ effect. The concentration of noradrenaline in plasma gives an indication of the overall activity of the sympathetic nervous system in the body. 

## 6.3.2.3.2 Cholinergic transmission

Acetylcholine (Figure 6.15) is synthesised from acetyl-CoA and choline. After its release from cholinergic nerve endings, acetylcholine is rapidly degraded (into choline and acetate) by the enzyme acetylcholinesterase, which is present on the postsynaptic membrane. The choline is taken up again by the nerve terminal for synthesis of more acetylcholine. A large group of pesticides, the organophosphorus esters, act by binding to the enzyme acetylcholinesterase, thus causing excessive accumulation of acetylcholine. They are, of course, toxic to humans by exactly the same mechanism and lead to muscle paralysis, with death eventually from respiratory paralysis. The effects can be reversed to some extent with atropine. 

Recognition that there are two main types of cholinergic receptors was one of the early triumphs of experimental pharmacology. Dale in 1914 showed that there were some actions of acetylcholine which could be mimicked by administration of muscarine, the active component of the poisonous mushroom Amanita muscaria; these effects were abolished by small doses of atropine. They correspond roughly to the effects of the parasympathetic nervous system. Other effects of acetylcholine were still apparent after blockade with muscarine, and these were similar to the effects of nicotine (the active component of tobacco). The effects produced by nicotine included stimulation of the contraction of skeletal muscle and the release of adrenaline from the adrenal medulla. We now recognise that these effects are mediated through two specific types of acetylcholine receptor, the muscarinic receptor and the nicotinic receptor. Both nicotinic and muscarinic receptors have since been further subdivided on the basis of cloning of homologous receptor proteins. Cholinergic synapses within the CNS are nicotinic; outside the CNS they are mostly muscarinic at target organs, unless they are preganglionic fibres. 

The function of the two types of receptor, together with noradrenaline, in the central and peripheral nervous systems is illustrated in Figure 6.18. 

## 6.3.3 Major effects of adrenergic stimulation

## 6.3.3.1 Stimuli for activation of the sympathetic nervous system and adrenal medulla

The sympathetic nervous system affects many bodily functions. It would be a very inefficient means of control if the whole system had to be activated at once, and this is not so: particular branches of the sympathetic nervous system are activated specifically under different conditions. This could make a complete description of sympathetic activation very complex, but for the most part it is still reasonable to think of the general effects of the whole system. Not only does the whole of the sympathetic nervous system tend to respond as one, but also the secretion of adrenaline from the adrenal medulla (which is effectively another extension of the sympathetic nervous system) tends to occur under the same conditions. This makes some generalisations possible. 

The activity of the sympathetic nervous system is constantly changing, and is changing in specific branches, regulating physiological functions such as heart rate and blood pressure; but overall (as reflected by the concentration of noradrenaline in the plasma) it is relatively constant during normal daily life. The secretion of adrenaline, similarly, is relatively constant during everyday life. The stimuli for activation of the sympathetic nervous system are generally those of ‘stress’ in the most general sense. This was first clearly described by the American physiologist Walter B. Cannon, whose book Bodily changes in pain, hunger, fear, and rage, published in 1915, summarised the role of adrenaline and of the sympathetic nervous system in stress states. When the body is under stress, the adrenal medulla springs into action and there is a more general activation of the sympathetic nervous system. 

For instance, the effects of the sympathetic nervous system on the circulatory system (heart and blood vessels) are brought into play by a fall in blood pressure. This may happen quite often. Consider the hydrostatic pressure of a column of blood about 2 m high. Then contemplate the fact that when you get out of bed and stand up, the pressure of blood available to perfuse your brain is going to drop rapidly and dramatically. This is an immediate stimulus to the sympathetic nervous system to maintain blood pressure, which it does, as we shall see in more detail below, by effects on both the heart and the blood vessels. You may be familiar with a feeling of faintness on standing up too quickly, particularly on a hot day when blood volume may be depleted by sweating. The brain receives the information that blood pressure is beginning to fall from receptors in the great vessels, collates this in the hypothalamus and causes the appropriate responses to be set in motion. 

![image](/assets/images/human_metabolism_images/eafdab518e70db1cf20e1ee6812dbb50.jpg)



Figure 6.18 Types of neurotransmission in the central and peripheral nervous systems. ACh, acetylcholine: cholinergic transmission; nic, nicotinic receptor; musc, muscarinic receptor; NA, noradrenaline.


Another type of stress is that of exercise. Even gentle exercise (running for the bus, for instance) requires both circulatory and metabolic adjustments. More substrate needs to be made available for energy production, and blood flow and oxygen delivery need to be increased. The only component over which we have voluntary control is the decision to cause our muscles to contract in a particular way. The necessary adjustments that follow are looked after by the sympathetic nervous system, triggered by changes in the circulation. For example, diversion of the blood to the muscles, brought about by local metabolic changes, will tend to cause a fall in blood pressure; the sympathetic nervous system will counteract this. Similarly, increasing acidity of the blood, caused by lactic acid production, will trigger an increased depth of breathing via chemoreceptors and activation of the sympathetic nervous system. 

A more severe stress, commonly studied in laboratories (because it is a reproducible test, unlike, for instance, trying to frighten someone), is a rapid lowering of the concentration of glucose in the blood to produce the state of hypoglycaemia. Experimentally this is brought about by an injection of insulin. Outside the laboratory it can occur in certain metabolic diseases in which gluconeogenesis or glycogenolysis are impaired, or in people with diabetes who have injected too much insulin. Glucose receptors in the hypothalamus relay the information and there is activation both of the sympathetic nervous system generally and of adrenaline secretion from the adrenal medulla (Figure 6.19). We will see shortly how these responses act to restore a normal glucose concentration. 

Note that we emphasise a rapid lowering of glucose concentration. The slow, gentle fall that occurs during early starvation (e.g. fasting overnight) is probably not a stimulus for the sympathetic nervous system. The direct role of the sympathetic nervous system and of adrenaline in metabolic regulation is most important in acute stress situations rather than normal everyday fluctuations. On the other hand, it was stated above that the sympathetic nervous system is active continuously, maintaining bodily functions such as blood pressure. These specific actions of the sympathetic nervous system do, of course, also affect metabolism indirectly: if blood flow to the brain is reduced, it cannot metabolise at a normal rate. 

![image](/assets/images/human_metabolism_images/4423152b5f2901572543771fd3f631b4.jpg)



Figure 6.19 Plasma glucagon, adrenaline, and noradrenaline concentrations in response to rapid lowering of the blood glucose concentration (by injection of insulin). Source: based on Gerich, J., Davis, J., Lorenzi, M., Rizza, R., Bohannon, N., Karam, J., et al. (1979) Am. J. Physiol. 236: E380–E5. Copyright 1979 by American Physiological Society. Reproduced with permission of American Physiological Society.


More dramatic stress states, such as physical injury or severe infection, are very potent stimuli for activation of the sympathetic nervous system and of adrenaline secretion from the adrenal medulla (Table 6.2). The stimuli reaching the brain are multiple. The special senses may alert the brain to danger (you may see a bus about to hit you, for example). Loss of blood reduces the circulating blood volume; this is sensed through pressure receptors and is a particularly potent stimulus for adrenaline secretion. Lack of blood volume leads to impaired oxygen delivery and, hence, anaerobic glycolysis; the resulting acidity in the blood is detected by chemoreceptors and relayed to the brain. There are also afferent (incoming) impulses arriving in the nerves responding to pain, tissue damage, and so on. All these afferent signals are integrated in the hypothalamus, and appropriate activation of the sympathetic nervous system and adrenal medulla is set in train from there. It is probably in such extreme situations that the sympathetic nervous system and adrenal medulla play their most vital roles. 

It should now be appreciated that the sympathetic nervous system can influence metabolism in both direct and indirect ways. The indirect ways include changes in the circulatory system and effects on hormone secretion, which we will consider below. 

## 6.3.3.2 Metabolic effects of adrenergic activation

Metabolic effects of catecholamines were largely covered earlier (Section 6.2.4.2). As noted there, they consist largely of a drive to mobilise stored fuels, glycogen and triacylglycerol. 

It is often difficult to determine to what extent these responses are brought about by adrenaline in the plasma, released from the adrenal medulla, or by noradrenaline released from sympathetic nerves. For instance, activation of liver glycogen breakdown is rapid when the blood glucose concentration falls as in Figure  6.19. This leads to rapid restoration of the glucose concentration provided there is adequate glycogen stored in the liver. The liver is supplied with sympathetic nerves, and there is much experimental evidence that these can activate glycogenolysis directly, although adrenaline from the adrenal medulla is also released under such conditions and will certainly play a role. People whose adrenals have been removed can respond fairly normally to glucose deprivation, implying that at least in that situation the sympathetic nerves to the liver can play a role. 


Table 6.2 Plasma catecholamine concentrations in different situations.


<table><tr><td></td><td>Noradrenaline</td><td>Adrenaline</td></tr><tr><td>Controls – cannula</td><td>0.6</td><td>0.3</td></tr><tr><td>Blood donation</td><td>1.2</td><td>0.2</td></tr><tr><td>Controls – venepuncture</td><td>2.1</td><td>0.4</td></tr><tr><td>Minor/moderate injuries</td><td>3.4</td><td>1.0</td></tr><tr><td>Acute MI</td><td>7.5</td><td>1.6</td></tr><tr><td>Exercise to exhaustion</td><td>17.1</td><td>2.8</td></tr><tr><td>Severe injuries</td><td>13.3</td><td>13.4</td></tr></table>


Mean values in nmol l−1 are shown. Blood was taken from healthy controls either through a cannula inserted some time previously, or by direct venepuncture with syringe and needle (so causing a little ‘stress’). ‘Blood donation’ represents samples taken from healthy volunteers immediately after donating 500 ml blood. Samples from injured patients and patients with myocardial infarction (MI) were taken in an Accident and Emergency Department within a few hours of the injury being sustained, or of the heart attack. ‘Severe’ injuries would involve more than one major fracture. (In some individual patients, adrenaline concentrations of >100 nmol l−1 were measured.) Samples from exercising volunteers were taken on the point of exhaustion on a bicycle ergometer. Data taken from Frayn, K. N. (1987) Biochem. Soc. Trans. 15: 1030–1032. 


Activation of lipolysis can be brought about purely by mental stress. Stimulation of lipolysis is an important feature of the response to physical stresses, such as surgical operations or injury. Again, it is not certain to what extent the direct innervation of adipose tissue is involved, or whether circulating adrenaline plays the major role. But, as with glycogenolysis, people without adrenals can raise their plasma non-esterified fatty acid concentration in response to lack of glucose, so the sympathetic nerves must play a role in that situation. (ANP/BNP will also play a role as described in Section 6.2.5.2.) Not only is the rate of lipolysis regulated by the nervous system, but so too is the rate of blood flow through adipose tissue. Sympathetic activation of adipose tissue, acting via vascular β-adrenoreceptors, seems to be the major effect increasing its blood flow in the period soon after a meal (Section 7.6). If the sympathetic activation is intense, however, then vasoconstriction may occur through activation of vascular α-receptors. This can have indirect effects on the release of non-esterified fatty acids. 

## 6.3.3.3 Circulatory effects of adrenergic activation

Activation of $\beta _ { 1 }$ receptors in the heart increases both the force of contraction and the rate of beating; thus, the rate of delivery of blood to the rest of the body (the cardiac output) is increased. This is probably an effect of noradrenaline released from sympathetic nerve endings rather than of adrenaline, except at very high adrenaline concentrations (e.g. in severe stress). 

In the blood vessels, the resistance of particular blood vessels (i.e. the diameter of the lumen) is regulated by smooth muscle in the walls. These smooth muscles are regulated by the sympathetic nervous system. For the most part, this is achieved through ${ \bf \alpha } _ { 1 }$ and ${ \mathfrak { X } } _ { 2 }$ receptors, which bring about contraction of the muscle and vasoconstriction (narrowing of the vessels). This has two effects. In the body as a whole, blood pressure will be increased since the heart is pumping blood through narrower channels. In specific organs and tissues, this is a means of selectively increasing or decreasing blood flow under different conditions. In fact, in most tissues there is continuous vasomotor tone; the sympathetic fibres are active continuously, under the influence of the medulla oblongata in the brainstem (the very primitive part of the brain); variations in flow are brought about by relaxation of this tone, or further constriction. 

In skeletal muscle, it was mentioned earlier that the smooth muscle of the blood vessels is innervated by cholinergic sympathetic fibres. Activation of these fibres leads to vasodilatation (opening up of the vessels with a consequent increase in blood flow). This is certainly true in some animals although its significance in humans is doubtful. It will be discussed again in connection with the increased skeletal muscle blood flow that is seen during exercise (Section 8.2.5). 

## 6.3.3.4 Effects of the autonomic nervous system on hormone secretion

The pancreatic islets have both α- and β-adrenergic receptors and are innervated by sympathetic nerves. They also receive fibres of the parasympathetic nervous system. These nerves regulate the secretion of both insulin and glucagon, as summarised in Table 6.3. These influences on pancreatic hormone secretion probably operate at the level of ‘fine tuning’ in normal daily life and it is not easy to demonstrate their role. In rodents, there is undoubtedly a normal adrenergic restraint on insulin secretion, since the plasma insulin concentration rises if the adrenal medullas are removed. In humans, the effects of adrenergic blocking drugs in the whole body are very difficult to interpret because they cause such widespread changes in both circulation and metabolism. The effects of the parasympathetic innervation of the pancreatic islets are undoubtedly important. They mediate the ‘cephalic phase’ of insulin secretion in response to the sight or smell of food, mentioned in Chapter 4 (Section 4.2.1). Also, in patients whose vagus nerve is cut at surgery to reduce gastric acid secretion (a former treatment for gastric ulcers), insulin secretion in response to a glucose drink is impaired, as is glucagon secretion in response to hypoglycaemia. 


Table  6.3 Adrenergic and parasympathetic effects on hormone secretion from the endocrine pancreas.


<table><tr><td>Input</td><td>Insulin secretion</td><td>Glucagon secretion</td></tr><tr><td>α-adrenergic</td><td>Suppresses (dominant effect)</td><td>Suppresses</td></tr><tr><td>β-adrenergic</td><td>Increases (only seen if α-effects blocked)</td><td>Increases</td></tr><tr><td>Parasympathetic</td><td>Increases</td><td>Increases</td></tr></table>

However, the effects of the nervous system (particularly adrenergic influences) on pancreatic hormone secretion become of great importance in ‘stress’ situations, such as strenuous exercise or physical injury. In these situations, there is β-adrenergically-mediated stimulation of glucagon secretion and α-adrenergic suppression of insulin secretion. These mechanisms reinforce the mobilisation of fuel stores (glycogen and triacylglycerol) and, in the case of physical injury, reinforce the resultant hyperglycaemia (elevation of the blood glucose concentration). During strenuous exercise, glucose utilisation by exercising muscle is increased greatly by insulin-independent mechanisms, so these effects may be seen as a means of maximising the availability of energyproviding substrates to the muscles without compromising glucose utilisation. (Metabolism during exercise will be covered in Chapter 8.) 

## Supplementary resources

Supplementary resources related to this chapter, including further reading and multiple choice questions, can be found on the companion website at www.wiley.com/go/frayn. 

![END](/assets/config_images/end.jpg)
