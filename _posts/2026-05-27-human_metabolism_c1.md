---
title: 人类代谢-C1-底层原则
date: 2026-05-27 00:00:00 +0800
last_modified_at: 2026-05-27 00:01:00 +0800
categories: [科研, 代谢] # 最多两层
tags: [科研, 代谢, book]
# toc: false # 关闭目录
math: true
mermaid: true # diagram generation
---


## Chapter 1

## The underlying principles of human metabolism

## 模块一：全景透视——为什么人体需要“代谢调节”？

材料在引言中提出了一个核心问题：**我们不是持续不断在吃，但身体的能量消耗却一刻不停，这期间究竟发生了什么？**

为了解释这种“摄入”与“消耗”的时间错位，书中引入了两个精妙的物理模型：

### 1. 两个物理模型的启示

* **水车模型（无缓存系统）：** 水车发电完全依赖于水库（池塘）源源不断的水流。水流一停，水车立即停止转动。这对应着没有能量储存能力的生物，极度脆弱。
* **汽车模型（有缓存与控制系统）：** 汽车的能量摄入是**间歇性**的（只在加油站加油时发生，瞬间输入极高），而能量输出则是**连续或波动**的（行驶、加速或怠速）。汽车之所以能长途跋涉，不仅是因为它有一个**燃料箱（储存装置）**，更因为有一个控制机制（油门和发动机管理系统）来调节燃料流。

### 2. 人体的能量供需图谱

人体的能量供需曲线与汽车如出一辙：

* **能量摄入：** 集中在一天中三次短暂的用餐时间，呈间歇性的高脉冲。
* **能量消耗：** 基础代谢（呼吸、心脏泵血、细胞离子泵维持、物质合成与降解）是**24小时无休**的；运动或疾病（如感染导致体温升高）则会带来额外的能量爆发。

> **专家视点（代谢调节的本质）：** > 代谢调节在分子层面主要通过**调节酶的活性**来实现。它的终极生理生理目的，就是让我们在面对剧烈的摄入波动（饱食、饥饿）和支出波动（静息、剧烈运动、疾病）时，通过自主神经和内分泌系统（如胰岛素、胰高血糖素）的完美协调，维持体内环境的**稳态（Homeostasis）**。

---

## 模块二：生物化学基石——极性、渗透压与氧化还原

材料强调，如果不理解分子的理化性质，就无法理解身体处理营养素的战略选择。

### 1. 极性（Polarity）与疏水/亲水

极性是指电荷在分子表面的分布状态。

* **亲水（Hydrophilic/极性）：** 如水分子（$H_2O$）、糖类、大部分氨基酸和有机酸（乳酸、丙酮酸）。它们携带局部或完全的电荷，能与极性的水分子形成氢 bond 或完美融合，易于在血液中自由运输，但**无法自由穿透主要由脂质组成的细胞膜**。
* **疏水（Hydrophobic/非极性）：** 如脂肪（甘油三酯）、长链烷烃。电荷分布均匀，不与水融合。
* **两亲性（Amphipathic）：** 如磷脂和长链游离脂肪酸。它们既有极性的“头”，又有非极性的“尾”。这种特性使它们能构筑细胞膜的双分子层（Lipid Bilayer）结构。

### 2. 渗透压（Osmosis）与燃料储存战略

当细胞膜两侧溶液浓度不相等时，水分子会自发向浓度高的一侧流动。

* **细胞膨胀与裂解：** 如果细胞内积聚了大量小分子糖（如葡萄糖），会产生极高的渗透压，导致水分疯狂涌入，使细胞吸水胀破。
* **身体的破局战略：** 为了规避渗透压灾难，细胞演化出了**聚合技术**。将数以万计的葡萄糖小分子脱水缩合成一株巨大的糖原（Macroglycogen）大分子。对细胞而言，这算作“一个粒子”，渗透压几乎降为零。

### 3. 氧化还原（Redox）——能量的本质是电子

代谢能量的释放，本质上是一场高度受控的、极其温和的“化学燃烧”。

$$C_6H_12O_6 + 6O_2 \rightarrow 6CO_2 + 6H_2O + \text{能量}$$

* **电子即能量：** 营养素中富含的 $C-H$ 键就是高能电子的载体。**分子的还原程度越高（$C-H$ 键越密集），其蕴含的能量就越大。**
* **脂肪 vs 碳水：** 脂肪（甘油三酯）几乎全由饱满的 $-CH_2-$ 链组成，处于极度还原态；而碳水化合物（葡萄糖）本身已含有大量 $O$ 原子，处于部分氧化态。因此，**每克脂肪蕴含的能量（约 37 kJ/g）远高于碳水化合物和蛋白质（约 17 kJ/g）**。
* **阶梯式释放：** 如果电子直接一步传递给氧气，能量会以爆炸性的热量释放，细胞会被烧毁。因此，细胞设置了一条漫长的“接力赛”——**电子传递链（ETC）**，利用 $NAD^+$、$FAD$ 等电子载体接收氢负离子（$H^-$，即带高能电子的氢原子），呈阶梯状递减释放能量，最终用于合成 $ATP$。

---

## 模块三：三大宏量营养素的代谢战略大比拼

| 特征/营养素 | 碳水化合物 (糖类) | 脂质 (脂肪) | 蛋白质 (氨基酸) |
| --- | --- | --- | --- |
| **基础单元 (单体)** | 单糖（葡萄糖、果糖、半乳糖） | 游离脂肪酸（NEFA）+ 甘油 | 氨基酸（含特征性的 $N$ 原子） |
| **大分子储存形式** | **糖原 (Glycogen)**（高度分支，挂靠在糖原蛋白骨架上） | **甘油三酯 (Triacylglycerol)**（极非极性，以无水脂滴形式存在） | **无专用储备形式**（所有蛋白质皆有其生理功能） |
| **能量密度** | 约 17 $\text{kJ/g}$ | **约 37 $\text{kJ/g}$ (极高)** | 约 17 $\text{kJ/g}$ |
| **含水情况** | **高水合性**：1g糖原绑定3g水。 | **无水储存**：排斥水，极其紧凑。 | 高水合性：1g蛋白质绑定3g水。 |
| **动员与利用速度** | 快，可无氧酵解产生 $ATP$。 | 较慢，必须依赖氧气和线粒体。 | 慢，属于应急、拆家式的动员。 |
| **代谢灵活性** | **极高**：可转为脂质，可提供三羧酸循环的关键中间体（补充反应）。 | **低**：脂肪酸**绝不能**逆向转变为碳水化合物。 | **高**：多数氨基酸可转为葡萄糖（糖异生）。 |

### 关键生理权衡（Trade-offs）

1. **为什么不全存糖原？** 看看书中的插图 1.10：1.05公斤的生土豆（富含水合碳水化合物）和仅仅90克的橄榄油（纯脂肪）释放的能量完全相同。如果人类全靠糖原储存能量，我们的体重将难以承受，丧失移动能力。
2. **为什么还要存糖原？** 脂肪虽高效，但动员慢且无法无氧发电。红细胞（没有线粒体）和大脑（脂肪酸无法穿透血脑屏障）有着对葡萄糖的刚性依赖。因此，身体必须保留局部糖原储备（如肝糖原约100g）。

---

## 模块四：细胞内的代谢路线图与终极枢纽

这是整篇材料最硬核的逻辑网：**无论是糖、脂还是氨基酸，它们catabolism（分解代谢）的终极路径都是汇流到同一种燃料——乙酰辅酶A（Acetyl-CoA），随后进入线粒体烧掉。**

### 1. 糖代谢的核心通路

* **第一步：锁定（磷酸化）。** 葡萄糖经 GLUT 运输蛋白进细胞后，立即被**己糖激酶/葡萄糖激酶**消耗一个 $ATP$ 转化为 **6-磷酸葡萄糖（G6-P）**。带电荷的 G6-P 无法再逃出细胞，正式站在了代谢的十字路口。
* **第二步： glycolysis（糖酵解）。** 在细胞质中，G6-P 经由一系列酶切最终分裂为 **丙酮酸（3碳）**。在此期间无需氧气，净产 2 $ATP$ 和 2 $NADH$。
* *无氧/无线粒体时*：为了让 $NAD^+$ 循环利用，丙酮酸被迫被乳酸脱氢酶还原为**乳酸**（酵母则转化为乙醇和 $CO_2$）。
* *有氧时*：丙酮酸跨膜进入线粒体。


* **第三步：不可逆的命运之门（PDH）。** 丙酮酸经**丙酮酸脱氢酶（PDH）**彻底脱去一个碳，生成**乙酰辅酶A（2碳）**。**【敲黑板】PDH 是强烈的单向不可逆反应。这意味着：碳水化合物可以转化为脂肪，但脂肪绝无法逆向转化为糖！**
* **糖异生（Gluconeogenesis）：** 饥饿状态下，肝脏逆转糖酵解过程（通过特异性的果糖-1,6-双磷酸酶等绕过不可逆节点），将乳酸、氨基酸骨架或甘油重新“拼”回葡萄糖，释放到血液中救命。

### 2. 脂代谢的核心通路

* **脂肪动员：** 储存在脂肪细胞中的甘油三酯被**细胞内脂肪酶**水解，释放出游离脂肪酸（NEFA）和甘油。NEFA 挂靠在白蛋白上运往全身。
* **活化与跨膜（肉碱穿梭）：** 进入靶细胞的脂肪酸被活化为脂肪酰辅酶A。然而，长链的脂肪酰辅酶A无法穿过选择性极高的**线粒体内膜（IMM）**。它必须把自己的酰基转移给“肉碱”，通过肉碱棕榈酰转移酶-1（CPT-1）和穿梭机制才能进入线粒体内部。
* **$\beta$-氧化（$\beta$-Oxidation）：** 在线粒体基质中，脂肪酸的 $\beta$-碳位不断遭到氧化、水解切断，像剪纸一样每轮剪下 2 个碳，生成一堆**乙酰辅酶A**，同时产生海量的 $NADH$ 和 $FADH_2$。

### 3. 三羧酸循环（TCA Cycle）与电子传递链（ETC）——终极发电厂

* **TCA循环（线粒体基质）：** 2碳的乙酰辅酶A与4碳的草酰乙酸结合，生成6碳的柠檬酸。经过一轮循环，脱下两分子 $CO_2$（2碳全部烧掉），重新生成4碳草酰乙酸。**每一轮循环输出：3 $NADH$ + 1 $FADH_2$ + 1 $GTP/ATP$（底物水平磷酸化）。**
* **草酰乙酸的悖论与补充反应（Anaplerosis）：** 代谢物经常被抽走去干别的（如合成氨基酸）。如果循环中间体变少，即使有再多脂肪来源的乙酰辅酶A，TCA循环也会因缺乏草酰乙酸而停摆（这叫草酰乙酸枯竭）。**乙酰辅酶A本身无法净生成草酰乙酸（因为进2碳出2碳）。能补充TCA中间体的，只有来自碳水化合物或部分氨基酸的3碳/4碳前体（如丙酮酸直接羧化为草酰乙酸）。** 这就是古老谚语 **“脂肪必须在碳水化合物的火焰中燃烧”** 的真正底层含义！
* **氧化磷酸化（IMM）：** ETC 复合物（Complex I-IV）利用 $NADH/FADH_2$ 释放的高能电子进行接力还原，顺便把质子（$H^+$）泵出线粒体内膜，人为制造出跨膜**电化学梯度**。质子最终只能像水流穿过大坝一样，迫通过 **$ATP$合成酶（Complex V）** 回流，驱动 $ADP$ 磷酸化为 $ATP$（化学渗透学说）。

---

## 模块五：蛋白质代谢与致命的“氮”废物清理战略

蛋白质从不作为纯粹的能量储备。动员蛋白质意味着“拆除身体的承重墙”（如消耗肌肉的肌动蛋白和肌球蛋白）。

### 1. 蛋白质的氨基转换与汇流

氨基酸拥有一个独特的 $\alpha$-氨基（$-NH_3^+$）。如果不把这个含氮基团摘掉，其碳骨架（2-氧代酸/$\alpha$-酮酸）就无法进入代谢池燃烧。

* **转氨基作用（Transamination）：** 这是一个平衡反应。转氨酶（ALT/AST）充当搬运工，把各种氨基酸的氨基，全部卸载到通用接收员 **2-氧代戊二酸（即 $\alpha$-酮戊二酸）** 上，使其变成 **谷氨酸（Glutamate）**。通过这种方式，全军散落的氮元素被集中到了谷氨酸一人身上。
* **氧化脱氨基作用（Oxidative Deamination）：** 也是全书最奇特、受高度别构调节的单向/双向兼顾酶——**谷氨酸脱氢酶（GDH）**。
* 在**分解代谢（缺能）**时：它利用 $NAD^+$，将谷氨酸身上的氨基彻底剥离，释放出**剧毒的游离氨（$NH_3$/$NH_4^+$）**，并重新生成2-氧代戊二酸返回三羧酸循环。
* 在合成代谢（多能）时：它利用 $NADPH$ 逆向操作，进行还原氨化生成氨基酸。



### 2. 鸟氨酸循环（Urea Cycle）——排毒艺术

释放出来的游离氨（$NH_3$）极具神经毒性，身体绝不允许其在血液中堆积。

* **肝脏的救火行动：** 肝脏线粒体中的 **氨基甲酰磷酸合成酶** 立即捕获氨，联合由 AST 转酶从谷氨酸处引渡过来的另一个氮原子，在**鸟氨酸循环**中把它们打包成高水溶性、无毒、含氮量高、极省水的 **尿素 $\text{[CO(NH}_2)_2\text{]}$**，通过肾脏随尿液排出。
* **外周的安全快递：** 肌肉等外周组织如果产生了氨，不能直接排入血，必须先由谷氨酰胺合成酶将其固定在谷氨酰胺（Glutamine）上，以无毒的形式通过血液“邮寄”到肝脏（做成尿素）或肾脏（直接以铵根缓冲剂排入尿液，不损失碳）。

### 3. 碳骨架的最后归宿：生糖 vs 生酮

脱去氨基后的碳骨架（2-氧代酸）表现出了不同的命运：

* **生糖氨基酸（Glucogenic）：** 其骨架能转化为丙酮酸、草酰乙酸等 $\ge 3$ 个碳的中间体。它们可以在饥饿时通过糖异生**净生成葡萄糖**，构成了人体的“虚拟碳水化合物水库”。
* **生酮氨基酸（Ketogenic）：** 其骨架只能降解为乙酰辅酶A或乙酰乙酰辅酶A（2碳）。因为 PDH 反应单向不可逆，它们**绝不可能变成葡萄糖**，只能直接在线粒体里烧掉，或者在肝脏中转化为**酮体**（乙酰乙酸、$\beta$-羟基丁酸）。

> **总结：** 大脑在长期饥饿中不能用脂肪酸，肝脏便将脂肪酸 $\beta$-氧化产出的过剩乙酰辅酶A，转化为水溶性、非两亲性、能通过血脑屏障的**酮体**送给大脑当燃料。这种神奇的“糖类替代战略”，配合生糖氨基酸的糖异生，才是人类能度过漫长荒年与饥饿的进化终极底牌。

## Key learning points

•	 We eat food. We expend energy doing exercise, sleeping, just being. What happens to the food between it entering our mouths and its being used for energy? That’s what metabolism (at least, so far as this book is concerned) is all about. 

•	 In order to cover the periods when we are not eating, we need to store metabolic fuels. We store fuel as fat (triacylglycerol) and as carbohydrate (glycogen). Fat provides considerably more energy per gram stored. Proteins are not stored specifically as energy reserves but they may be utilised as such under certain conditions. We must regulate both the storage and mobilisation of energy to match intake to expenditure. That is what we will refer to as metabolic regulation. 

Molecules involved in metabolism differ in an important property: polarity. Polar molecules (those with some degree of electrical charge) mix with water (which is also polar); non-polar molecules, which include most lipids (fatty substances), usually don’t mix with water. This has profound implications for the way they are handled in the body. They also differ in the amount of energy they contain, affecting their efficiency as fuels. 

•	 Some molecules have both polar and non-polar aspects: they are said to be amphipathic. They can form a bridge between polar and non-polar regions. Amphipathic phospholipid molecules can group together to form membranes, such as cell membranes. 

•	 Energy is derived from metabolic substrates derived from food-stuffs principally by oxidation, a chemical process involving electron transfer from electron donor (reducing agent) to electron acceptor (oxidising agent), the final electron acceptor being oxygen. 

•	 The different organs in the body have their own characteristic patterns of metabolism. Substrates flow between them in the bloodstream (circulation). Larger blood vessels divide into fine vessels (capillaries) within the tissues, so that the distances that molecules have to diffuse to or from the cells are relatively small (more detail in Chapter 3). 

The different classes of metabolic substrates have characteristic chemical properties; by utilising all three types of metabolic substrates derived from the three major food energy groups (carbohydrates, fats, and proteins) energy storage (anabolism) and release (catabolism) in many physiological conditions is achieved. 

General features of metabolism include synthesis and breakdown of substrates, and complete breakdown to release energy by oxidation. The tricarboxylic acid cycle (TCA cycle) is the central cellular mechanism for substrate oxidation to ${ \sf H } _ { 2 } { \sf O }$ and ${ \mathsf { C O } } _ { 2 }$ , with consumption of $\mathsf { O } _ { 2 } .$ . It operates within mitochondria. 

Carbohydrate metabolism centres around the sugar glucose. Carbohydrate metabolic pathways include conversion to glycogen and its reverse, glucose breakdown and oxidation, glucose conversion to lipid, and synthesis of glucose (gluconeogenesis). 

Lipid metabolism for energy centres on the interconversion of fatty acids and triacylglycerol. Triacylglycerol synthesis involves esterification of fatty acids with glycerol; triacylglycerol breakdown (lipolysis) involves liberation of fatty acids and glycerol from stored triacylglycerol. The oxidation of fatty acids occurs through a pathway known as β-oxidation. 

Amino acid metabolism involves incorporation of amino acids into protein, and its reverse (protein synthesis and breakdown), and further metabolism of the amino acids, either to convert them to other substrates (e.g. lipids) or final oxidation. The nitrogen component of amino acids is disposed of by conversion to urea in the liver. 

## 1.1 Metabolism in perspective

To many students, metabolism sounds a dull subject. It involves learning pathways with intermediates with difficult names and even more difficult formulae. Metabolic regulation may sound even worse. It involves not just remembering the pathways, but remembering what the enzymes are called, what affects them and how. This book is not simply a repetition of the molecular details of metabolic pathways. Rather, it is an attempt to put metabolism and metabolic regulation together into a physiological context, to help the reader to see the relevance of these subjects. Once their relevance to everyday life becomes apparent, then the details will become easier, and more interesting, to grasp. 

This book is written from a human perspective because, as humans, it is natural for us to find our own metabolism interesting – and very important for understanding human health and disease. Nevertheless, many aspects of metabolism and its regulation that are discussed are common to other mammals. Some mammals, such as ruminants, have rather specialised patterns of digestion and absorption of energy; such aspects will not be covered in this book. 

Metabolism might be defined as the biochemical reactions involved in converting foodstuffs into fuel. (There are other aspects, but we will concentrate on this one.) As we shall shortly see, that is not a constant process: ‘flow’ through the metabolic pathways needs to change with time. An important aspect of these pathways is therefore the ability to direct metabolic products into storage, then retrieve them from storage as appropriate. In this chapter we shall give an overview of the major pathways involved in carbohydrate, lipid, and protein metabolism. In later chapters we shall see that these pathways operate within specific tissues – or sometimes between tissues – and not all cells carry out the same set of metabolic reactions. We intend to give enough detail of metabolic pathways that a student will be able to understand them, but inevitably a more detailed biochemistry textbook will provide more. We shall concentrate upon understanding how these pathways operate in human terms, and how they are regulated. 

Now we have mentioned metabolic regulation, so we should ask: why is it necessary? An analogy here is with mechanical devices, which require an input of energy, and convert this energy to a different and more useful form. The waterwheel is a simple example. This device takes the potential energy of water in a reservoir  –  the mill-pond – and converts it into mechanical energy which can be used for turning machinery, for instance, to grind corn. As long as the water flows, its energy is extracted, and useful work is done. If the water stops, the wheel stops. A motor vehicle has a different pattern of energy intake and energy output (Figure 1.1). Energy is taken in very spasmodically – only when the driver stops at a filling station. Energy is converted into useful work (acceleration and motion) with an entirely different pattern. A long journey might be undertaken without any energy intake. Clearly, the difference from the waterwheel lies in the presence of a storage device – the fuel tank. But the fuel tank alone is not sufficient: there must also be a control mechanism to regulate the flow of energy from the store to the useful-work-producing device (i.e. the engine). In this case, the regulator is in part a human brain deciding when to move, and in part a mechanical system controlling the flow of fuel. 

What does this have to do with metabolism? The human body is also a device for taking in energy (chemical energy, in the form of food) and converting it to other forms. Most obviously, this is in the form of physical work, such as lifting heavy objects. However, it can also be in more subtle forms, such as producing and nurturing offspring. Any activity requires energy. Again, this is most obvious if we think about performing mechanical work: lifting a heavy object from the floor onto a shelf requires conversion of chemical energy (ultimately derived from food) into potential energy of the object. But even maintaining life involves work: the work of breathing, of pumping blood around the vascular system, of chewing food and digesting it. At a cellular level, there is constant work performed in the pumping of ions across membranes, and the synthesis and breakdown of the chemical constituents of cells. 

![image](/assets/images/human_metabolism_images/9648174c02ddf5bb532cc5b35b336c42.jpg)



Figure 1.1 Rates of energy intake and output for a motor vehicle. The rate of intake (top panel) is zero except for periods in a filling station, when it is suddenly very high. (Notice that the scales are different for intake and output.) The rate of output is zero while the car is parked with the engine off; it increases as the car is driven to the filling station, and is relatively high during a journey. When totalled up over a long period, the areas under the two curves must be equal (energy intake = energy output) – except for any difference in the amounts of fuel in the tank before and after.


What is your pattern of energy intake in relation to energy output? For most of us, the majority of energy intake occurs in three relatively short periods during each 24  hours, whereas energy expenditure is largely continuous (the resting metabolism) with occasional extra bursts of external work (Figure 1.2). It is clear that we, like the motor vehicle, must have some way of storing food energy and releasing it when required. As with the motor vehicle, the human brain may also be at the beginning of the regulatory mechanism, although it is not the conscious part of the brain: we do not have to think when we need to release some energy from our fat stores, for instance. 

Some of the important regulatory systems that will be covered in this book lie outside the brain, in organs which secrete hormones, particularly the pancreas. But whatever the internal means for achieving this regulation, we manage to store our excess food energy and to release it just as we need. 

This applies to the normal 24-hour period in which we eat meals and go about our daily life. But the body also has to cope with less well-organised situations. In many parts of the world, there are times when food is not that easily available, and yet people are able to continue relatively normal lives. Clearly, the body’s regulatory mechanisms must recognise that food is not coming in and allow an appropriate rate of release of energy from the internal stores. In other situations, the need for energy may be suddenly increased. Strenuous physical exercise may increase the total rate of metabolism in the body to 20 times its resting level. Something must recognise the fact that there is a sudden need to release energy at a high rate from the body’s stores. During severe illness, such as infections, the rate of metabolism may also be increased; this is manifested in part by the rise in body temperature. Often the sufferer will not feel like eating normally. Once again, the body must have a way of recognising the situation, and regulating the necessary release of stored energy. 

![image](/assets/images/human_metabolism_images/5b403678b2c898de6306e89f1764545e.jpg)



Figure 1.2 Rates of energy intake and output for a person during a typical day. The rate of energy intake (top panel) is zero except when eating or drinking, when it may be very high. The rate of energy output (heat + physical work) (lower panel) is at its lowest during sleep; it increases on waking and even more during physical activity. As with the car, the pattern of energy intake may not resemble that of energy expenditure, but over a long period the areas under the curves will balance – except for any difference in the amounts of energy stored (mainly as body fat) before and after. Source: data for energy expenditure are for a person measured in a calorimetry chamber and were kindly supplied by Prof Susan Jebb of Nuffield Department of Primary Care Health Sciences, Oxford University.


What we are now discussing is, indeed, metabolic regulation. Metabolic regulation in human terms covers the means by which we take in nutrients in discrete meals, and deliver energy as required, varying from moment to moment and from tissue to tissue, in a pattern which may have no relationship at all to the pattern of intake. Metabolic regulation works ultimately at a molecular level, mainly by modulation of the activities of enzymes. But one should not lose sight of the fact that these molecular mechanisms are there to enable us to lead normal lives despite fluctuations in our intake and our expenditure of energy. In this book, the emphasis will be on the systems within the human body which sense the balance of energy coming in and energy required, particularly the endocrine (hormonal) and the nervous systems, and which regulate the distribution and storage of nutrients after meals, and their release from stores and delivery to individual tissues as required. 

The intention of this preamble is to illustrate that, underlying our everyday lives, there are precise and beautifully coordinated regulatory systems controlling the flow of energy within our bodies. Metabolic regulation is not a dry, academic subject thought up just to make biochemistry examinations difficult; it is at the centre of human life and affects each one of us every moment of our daily lives. 

## 1.2 The chemistry of food – and of bodies

Energy is taken into the body in the form of food. The components of food may be classified as macronutrients and micronutrients. Macronutrients are those components present in a typical serving in amounts of grams rather than milligrams or less. They are the well-known carbohydrate, fat, and protein. Water is another important component of many foods, although it is not usually considered a nutrient. Micronutrients are vitamins, minerals, and nucleic acids: they are not oxidised to provide energy, but rather they are used to facilitate biochemical mechanisms of the body. Although these micronutrients play vital roles in the metabolism of the macronutrients, they will not be discussed in any detail in this book, which is concerned with the broader aspects of what is often called energy metabolism. 

The links between nutrition and energy metabolism are very close. We eat carbohydrates, fats, and proteins. Within the body these relatively large molecules are broken down to smaller components, rearranged, stored, released from stores, and further metabolised, but essentially whether we are discussing food or metabolism the same categories of carbohydrate, fat, and protein can be distinguished. This is not surprising since our food itself is of organic origin, whether plant or animal. 

In order to understand metabolism and metabolic regulation, it is useful to have a clear idea of some of the major chemical properties of these components. This is not intended as a treatise in physical or organic chemistry but as a starting point for understanding some of the underlying principles of metabolism. The discussion assumes a basic understanding of the meaning of atoms and molecules, of chemical reactions and catalysis, and some understanding of chemical bonds (particularly the distinction between ionic and covalent bonding). 

## 1.2.1 Some important chemical concepts

## 1.2.1.1 Polarity

Some aspects of metabolism are more easily understood through an appreciation of the nature of polarity of molecules. Polarity refers to the distribution of electrical charge over the molecule. A non-polar molecule has a very even distribution of electrical charge over its surface and is electrically neutral overall (the negative charge on the electrons is balanced by the positive charge of the nucleus). A polar molecule has an overall charge, or at least an uneven distribution of charge. The most polar small particles are ions – that is, atoms or molecules which have entirely lost or gained one or more electrons. However, even completely covalently bonded organic molecules may have a sufficiently uneven distribution of electrical charge to affect their behaviour. Polarity is not an all-ornone phenomenon; there are gradations, from the polar to the completely non-polar. 

Polarity is not difficult to predict in the molecules which are important in biochemistry. We will contrast two simple molecules: water and methane. Their relative molecular masses are similar – 18 for water, 16 for methane – yet their physical properties are very different. Water is a liquid at room temperature, not boiling until $1 0 0 ^ { \circ } \mathrm { C } ,$ whereas methane is a gas (‘natural gas’) which only liquifies when cooled to $- 1 6 1 ^ { \circ } \mathrm { C }$ . We might imagine that similar molecules of similar size would have the same tendency to move from the liquid to the gas phase, and that they would have similar boiling points. The reason for their different behaviours lies in their relative polarity. The molecule of methane has the three-dimensional structure shown in Figure 1.3a. The outer electron ‘cloud’ has a very even distribution over the four hydrogen atoms, all of which have an equal tendency to pull electrons their way. The molecule has no distinct electrical poles  –  it is non-polar. Because of this very even distribution of electrons, molecules near each other have little tendency to interact. In contrast, in the water molecule (Figure 1.3b) the oxygen atom has a distinct tendency to pull electrons its way, shifting the distribution of the outer electron cloud so that it is more dense over the oxygen atom, and correspondingly less dense elsewhere. Therefore, the molecule has a rather negatively charged region around the central oxygen atom, and correspondingly positively charged regions around the hydrogen atoms. Thus, it has distinct electrical poles – it is a relatively polar molecule. It is easy to imagine that water molecules near to each other will interact. Like electrical charges repel each other, unlike charges attract. This gives water molecules a tendency to line up so that the positive regions of one attract the negative region of an adjacent molecule (Figure 1.3b). So, water molecules, unlike those of methane, tend to ‘stick together’: the energy needed to break them apart and form a gas is much greater than for methane, and hence water is a liquid while methane is a gas. The latent heat of evaporation of water is 2.5 kJ $\mathrm { g } ^ { - 1 }$ , whereas that of methane is 0.6 kJ $\mathrm { g } ^ { - 1 }$ . Note that the polarity of the water molecule is not as extreme as that of an ion – it is merely a rather uneven distribution of electrons, but enough to affect its properties considerably. 

The contrast between water and methane may be extended to larger molecules. Organic compounds composed solely of carbon and hydrogen – for instance, the alkanes or ‘paraffins’ – all have the property of extreme non-polarity: the chemical (covalent) bond between carbon and hydrogen atoms leads to a very even distribution of electrons, and the molecules have little interaction with each other. A result is that polar molecules, such as those of water, and non-polar molecules, such as those of alkanes, do not mix well: the water molecules tend to bond to each other and to exclude the non-polar molecules, which can themselves pack together very closely because of the lack of interaction between them. In fact, there is an additional form of direct attraction between non-polar molecules, the van der Waals forces. Random fluctuations in the density of the electron cloud surrounding a molecule lead to minor, transient degrees of polarity; these induce an opposite change in a neighbouring molecule, with the result that there is a transient attraction between them. These are very weak attractions, however, and the effect of the exclusion by water is considerably stronger. The non-polar molecules are said to be hydrophobic (water fearing or water hating). 

A strong contrast is provided by an inorganic ionic compound such as sodium chloride. The sodium and chlorine atoms in sodium chloride are completely ionised under almost all conditions. They pack very regularly in crystals in a cubic form. The strength of their attraction for each other means that considerable energy is needed to disrupt this regular packing  –  sodium chloride does not melt until heated above $8 0 0 ^ { \circ } \mathrm { C } .$ . And yet it dissolves very readily in water – that is, the individual ions become separated from their close packing arrangement rather as they would on melting. Why? Because the water molecules, by virtue of their polarity, are able to come between the ions and reduce their attraction for each other. 


(a)


![image](/assets/images/human_metabolism_images/7413112497d0af35f753723dae8b76da.jpg)


![image](/assets/images/human_metabolism_images/81c183d0e0ad6e7c97f12858b54b0230.jpg)


![image](/assets/images/human_metabolism_images/adcdb7332e686bca9a9942f804220cfb.jpg)



Figure 1.3 (a) Three-dimensional structure of the methane molecule and (b) the molecular structure of water. (a) The hydrogen atoms of methane (CH4) are arranged symmetrically in space, at the corners of a tetrahedron. (b) The molecular structure of water. Top: view of the ‘electron cloud’ surrounding the molecule; bottom, interactions between water molecules. The molecule has a degree of polarity, and this leads to electrical interactions between neighbouring molecules by the formation of hydrogen bonds. These bonds are not strong compared with covalent bonds, and are constantly being formed and broken. Nevertheless, they provide sufficient attraction between the molecules to account for the fact that water is a liquid at room temperature whereas the non-polar methane is a gas.


In fact, each of the charged sodium and chloride ions will become surrounded by a ‘shell’ of water molecules, shielding it from the attraction or repulsion of other ions. Sodium chloride is said to be hydrophilic – water loving. The terms polar and hydrophilic are for the most part interchangeable. Similarly, the terms non-polar and hydrophobic are virtually synonymous. 

Ionic compounds, the extreme examples of polarity, are not confined to inorganic chemistry. Organic molecules may include ionised groups. These may be almost entirely ionised under normal conditions  –  for instance, the esters of orthophosphoric acid (‘phosphate groups’), as in the compounds AMP, ADP, and ATP, in metabolites such as glucose 6-phosphate, and in phospholipids. Most of the organic acids involved in intermediary metabolism, such as lactic acid, pyruvic acid, and the long-chain carboxylic acids (fatty acids), are also largely ionised at physiological hydrogen ion concentrations (Box 1.1). Thus, generation of lactic acid during exercise raises the hydrogen ion concentration (the acidity) both within the cells where it is produced, and generally within the body, since it is released into the bloodstream. 

As stated earlier, polarity is not difficult to predict in organic molecules. It relies upon the fact that certain atoms always have electronegative (electron withdrawing) properties in comparison 

with hydrogen. The most important of these atoms biochemically are those of oxygen, phosphorus, and nitrogen. Therefore, certain functional groups based around these atoms have polar properties. These include the hydroxyl group (–OH), the amino group (–NH ), and the orthophosphate group $( - \mathrm { O P O } _ { 3 } ^ { \dot { 2 } - } )$ . Compounds containing these groups will have polar properties, whereas those containing just carbon and hydrogen will have much less polarity. The presence of an electronegative atom does not always give polarity to a molecule  –  if it is part of a chain and balanced by a similar atom this property may be lost. For instance, the ester link in a triacylglycerol molecule (discussed below) contains two oxygen atoms but has no polar properties. 

Examples of relatively polar (and thus watersoluble) compounds, which will be frequent in this book, are sugars (with many –OH groups), organic acids such as lactic acid (with a COO− group), and most other small metabolites. Most amino acids also fall into this category (with their amino and carboxyl groups), although some fall into the amphipathic (‘mixed’) category discussed below. 

## Box 1.1 Ionisation state of some acids at normal hydrogen ion concentrations

The normal pH in blood plasma is around 7.4. (It may be somewhat lower within cells, down to about 6.8.) This corresponds to a hydrogen ion concentration of $\dot { 3 } . 9 8 \times 1 0 ^ { - 8 }$ mo $| ^ { - 1 }$ (since $- \log _ { 1 0 }$ of $3 . 9 8 \times 1 0 ^ { - 8 }$ is 7.4). 

The equation for ionisation of an acid HA is: 

$$
\mathsf {H A} \Leftrightarrow \mathsf {H} ^ {+} + \mathsf {A} ^ {-}
$$

this equilibrium is described by the equation: 

$$
\frac {[ \mathsf {H} ^ {+} ] [ \mathsf {A} ^ {-} ]}{[ \mathsf {H A} ]} = K _ {\mathrm{i}}
$$

where $K _ { \mathrm { i } }$ is the dissociation or ionisation constant and is a measure of the strength of the acid: the higher the value of $K _ { \mathrm { i } }$ the stronger (i.e. the more dissociated) the acid. 

$K _ { \mathrm { i } }$ in the equation above relates the concentrations expressed in molar terms (e.g. mol/l). (Strictly, it is not the concentrations but the ‘effective ion concentrations’ or ion activities which are related; these are not quite the same as concentrations because of inter-ion attractions. In most biological systems, however, in which the concentrations are relatively low, it is a close approximation to use concentrations. If activities are used, then the symbol $K _ { \mathfrak { a } }$ is used for the dissociation constant of an acid.) 

Some biological acids and their $K _ { \mathfrak { a } }$ values are listed in Table 1.1.1, together with a calculation of the proportion ionised at typical pH (7.4). 

The calculation is done as follows (using acetic acid as an example): 

$$
K _ {\mathrm{a}} = 1. 7 5 \times 1 0 ^ {- 5} = \frac {[ \mathrm{H} ^ {+} ] [ \mathrm{Ac} ^ {-} ]}{[ \mathrm{HAc} ]}
$$

(where HAc represents undissociated acetic acid, Ac− represents the acetate ion). At pH 7.4, $[ \mathsf { H } ^ { + } ] = 3 . 9 8 \times 1 0 ^ { - 8 }$ mol $| ^ { - 1 }$ . Therefore, 

$$
\frac {[ \mathrm{Ac} ^ {-} ]}{[ \mathrm{HAc} ]} = \frac {1 . 7 5 \times 1 0 ^ {- 5}}{3 . 9 8 \times 1 0 ^ {- 8}} = 4 4 0
$$

(i.e. the ratio of ionised to undissociated acid is 440:1; it is almost entirely ionised). 

The percentage in the ionised form $= \frac { 4 4 0 } { 4 4 1 } \times 1 0 0 \% = 9 9 . 8 \%$ 


Table 1.1.1


<table><tr><td>Acid</td><td><eq>K_a</eq></td><td>% ionised at pH 7.4</td></tr><tr><td>Acetic, <eq>CH_3COOH</eq></td><td><eq>1.75 \times 10^{-5}</eq></td><td>99.8</td></tr><tr><td>Lactic, <eq>CH_3CHOHCOOH</eq></td><td><eq>0.38 \times 10^{-4}</eq></td><td>99.9</td></tr><tr><td>Palmitic acid, <eq>CH_3(CH_2)_{14}COOH</eq></td><td><eq>1.58 \times 10^{-5}</eq></td><td>99.8</td></tr><tr><td>Glycine, <eq>CH_2NH_2COOH</eq> (carboxyl group)</td><td><eq>3.98 \times 10^{-3}</eq></td><td>100</td></tr></table>

Another important point about polarity in organic molecules is that within one molecule there may be both polar and non-polar regions. They are called amphipathic compounds. This category includes phospholipids and long-chain fatty acids (Figure 1.4). Cell membranes are made up of a double layer of phospholipids, interspersed with specific proteins such as transporter molecules, ion channels and hormone receptors, and molecules of the sterol, cholesterol (Figure 1.5). The phospholipid bilayer presents its polar faces – the polar ‘heads’ of the phospholipid molecules – to the aqueous external environment and to the aqueous internal environment; within the thickness of the membrane is a non-polar, hydrophobic region. The physicochemical nature of such a membrane means that, in general, molecules cannot diffuse freely across it: non-polar molecules would not cross the outer, polar face and polar molecules would not cross the inner, hydrophobic region. Means by which molecules move through membranes are discussed in Chapter 2 (Box 2.1). 

The long-chain fatty acids fall into the amphipathic category  –  they have a long, non-polar hydrocarbon tail but a more polar carboxylic group head (–COO− ). Another compound with mixed properties is cholesterol (Figure 1.6); its ring system is very non-polar, but its hydroxyl group gives it some polar properties. However, the long-chain fatty acids and cholesterol may lose their polar aspects completely when they join in ester links. An ester is a compound formed by the condensation (elimination of a molecule of water) of an alcohol (–OH) and an acid (e.g. a carboxylic acid, –COO− ). Cholesterol (through its –OH group) may become esterified to a longchain fatty acid, forming a cholesteryl ester (e.g. cholesteryl oleate, Figure 1.6). The cholesteryl esters are extremely non-polar compounds. This fact will be important when we consider the metabolism of cholesterol in Chapter 10. The long-chain fatty acids may also become esterified with glycerol, forming triacylglycerols (Figure 1.4). Again, the polar properties of both partners are lost, and a very non-polar molecule is formed. This fact underlies one of the most fundamental aspects of mammalian metabolism  –  the use of triacylglycerol as the major form for storage of excess energy. 

Among amino acids, the branched-chain amino acids, leucine, isoleucine, and valine, have non-polar side chains and are thus amphipathic. The aromatic amino acids phenylalanine and tyrosine are relatively hydrophobic, and the amino acid tryptophan is so non-polar that it is not carried free in solution in the plasma. 

The concept of the polarity or non-polarity of molecules thus has a number of direct consequences for the aspects of metabolism to be considered in later chapters. Some of these consequences are the following: 

(1) Lipid fuels – fatty acids and triacylglycerols – are largely hydrophobic and are not soluble in the blood plasma. There are specific routes for their absorption from the intestine and specific mechanisms by which they are transported in blood. 

(2) Carbohydrates are hydrophilic. When carbohydrate is stored in cells it is stored in a hydrated form, in association with water. In contrast, fat is stored as a lipid droplet from which water is excluded. Mainly because of this lack of water, fat stores contain considerably more energy per unit weight of store than do carbohydrate stores. 

(3) The entry of lipids into the circulation must be coordinated with the availability of the specific carrier mechanisms. In the rare situations in which it arises, uncomplexed fat in the bloodstream may have very adverse consequences. 

## 1.2.1.2 Osmosis

The phenomenon of osmosis underlies some aspects of metabolic strategy  –  it can be seen as one reason why certain aspects of metabolism and metabolic regulation have evolved in the way that they have. It is outlined only briefly here to highlight its relevance. 

Osmosis is the way in which solutions of different concentrations tend to even out when they are in contact with one another via a semipermeable membrane. In solutions, the solvent is the substance in which things dissolve (e.g. water) and the solute the substance which dissolves. A semipermeable membrane allows molecules of solvent to pass through, but not those of solute. Thus, it may allow molecules of water but not those of sugar to pass through. Cell membranes have specific protein channels (aquaporins, discussed in Section 2.2.2.6) to allow water molecules to pass through; they are close approximations to semipermeable membranes. 

![image](/assets/images/human_metabolism_images/f431bfa34715d86dea3e2e6d5fe83ae3.jpg)


![image](/assets/images/human_metabolism_images/aca848c6ec619abc9b68e8b72936dba4.jpg)


![image](/assets/images/human_metabolism_images/552d319157670fd63971c670fb071631.jpg)



Figure 1.4 Chemical structures of some lipids. A typical saturated fatty acid (palmitic acid) is shown with its polar carboxylic group and non-polar hydrocarbon tail. Glycerol is a hydrophilic alcohol. However, it is a component of many lipids as its hydroxyl groups may form ester links with up to three fatty acids, as shown. The resultant triacylglycerol has almost no polar qualities. The phospholipids are derived from phosphatidic acid (diacylglycerol phosphate) with an additional polar group, usually a nitrogen-containing base such as choline (as shown) or a polyalcohol derivative such as phosphoinositol. Phospholipids commonly have long-chain unsaturated fatty acids on the 2-position; oleic acid (18:1 n-9) is shown.


![image](/assets/images/human_metabolism_images/ff0d766bd3b39409fb84e39da7861433.jpg)



Figure 1.5 Structure of biological membranes in mammalian cells. Cell membranes and intracellular membranes such as the endoplasmic reticulum are composed of bilayers of phospholipid molecules with their polar head-groups facing the aqueous environment on either side and their non-polar ‘tails’ facing inwards, forming a hydrophobic centre to the membrane. The membrane also contains intrinsic proteins such as hormone receptors, ion channels, and sugar transporters, and molecules of cholesterol which reduce the ‘fluidity’ of the membrane. Modern views of cell membrane structure emphasise that there are domains, known as ‘rafts,’ in which functional proteins co-locate, enabling interactions between them. These lipid rafts are characterised by high concentrations of cholesterol and of certain phospholipids (glycosphingolipids).


![image](/assets/images/human_metabolism_images/80df06ca47c2c4bbaecd7f918d7dde48.jpg)



Figure 1.6 Cholesterol and a typical cholesteryl ester (cholesteryl oleate). In the structure of cholesterol, not all atoms are shown (for simplicity); each ‘corner’ represents a carbon atom, or else –CH or –CH . Cholesterol itself has amphipathic properties because of its hydroxyl group, but when esterified to a long-chain fatty acid the molecule is very non-polar.


If solutions of unequal concentration  –  for instance, a dilute and a concentrated solution of sugar  –  are separated by a semipermeable membrane, then molecules of solvent (in this case, water) will tend to pass through the membrane until the concentrations of the solutions have become equal. In order to understand this intuitively, it is necessary to remember that the particles (molecules or ions) of solute are not just moving about freely in the solvent: each is surrounded by molecules of solvent, attracted by virtue of the polarity of the solute particles. (In the case of a non-polar solute in a non-polar solvent, we would have to say that the attraction is by virtue of the non-polarity; it occurs through weaker forces such as the van der Waals.) In the more concentrated solution, the proportion of solvent molecules engaged in such attachment to the solute particles is larger, and there is a net attraction for further solvent molecules to join them, in comparison with the more dilute solution. Solvent molecules will tend to move from one solution to the other until the proportion involved in such interactions with the solute particles is equal. 

The consequence of this in real situations is not usually simply the dilution of a more concentrated solution, and the concentration of a more dilute one, until their concentrations are equal. Usually there are physical constraints. This is simply seen if we imagine a single cell, which has accumulated within it, for instance, amino acid molecules taken up from the outside fluid by a transport mechanism which has made them more concentrated inside than outside. Water will then tend to move into the cell to even out this concentration difference. If water moves into the cell, the cell will increase in volume. Cells can swell so much that they burst under some conditions (usually not encountered in the body, fortunately). For instance, red blood cells placed in water will burst (lyse) from just this effect: the relatively concentrated mixture of dissolved organic molecules within the cell will attract water from outside the cell, increasing the volume of the cell until its membrane can stretch no further and ruptures. 

In the laboratory, we can avoid this by handling cells in solutions which contain solute – usually sodium chloride – at a total concentration of solute particles which matches that found within cells. Solutions which match this osmolarity are referred to as isotonic; a common laboratory example is isotonic saline containing 9g of NaCl per litre of water, with a molar concentration of 154 mmol l−1 . Since this will be fully ionised into $\mathrm { N a } ^ { + }$ and Cl− ions, its particle concentration is 308 ‘milliparticles’ – sometimes called milliosmoles – per litre. We refer to this as an osmolarity of 308 mmol l−1 , but it is not 308 mmol NaCl per litre. (Sometimes you may see the term osmolality, which is very similar to osmolarity, but measured in mmol per kg solvent.) 

The phenomenon of osmosis has a number of repercussions in metabolism. Most cells have a number of different ‘pumps’ or active transporters in their cell membranes which can be used to regulate intracellular osmolarity, and hence cell size. This process requires energy and is one of the components of basal energy expenditure. It may also be important in metabolic regulation; there is increasing evidence that changes in cell volume are part of a signalling mechanism which brings about changes in the activity of intracellular metabolic pathways. The osmolarity of the plasma is maintained within narrow limits by specific mechanisms within the kidney, regulating the loss of water from the body via changes in the concentration of urine. Most importantly, potential problems posed by osmosis can be seen to underlie the metabolic strategy of fuel storage, as will become apparent in later sections. 

## 1.2.1.3 Reduction-oxidation

Metabolic energy in living cells is released by the oxidation of relatively large molecular weight substrates containing substantial amounts of chemically available energy (Gibbs ‘free’ energy, G). This is a form of combustion: energy-rich carbon-containing fuel (metabolic substrate) is ‘burnt’ using oxygen, producing water $\mathrm { ( H } _ { 2 } \mathrm { O ) }$ and carbon dioxide $\left( \mathrm { C O } _ { 2 } \right)$ as waste products, in the same way as carbon-based domestic fuel (coal, wood) is burnt on a fire using atmospheric oxygen, and releasing its contained energy, with the same end-products. Clearly in metabolism there is no flame, but that is because the gradual release of the energy is controlled so stringently and incrementally. 

The term ‘oxidation’ originally referred to the gain of oxygen in a chemical reaction, and the opposite process, ‘reduction,’ to the loss of oxygen (e.g. when metal oxides are heated, they are ‘reduced’ to pure metal, with the loss of oxygen and a reduction in the weight of the ore). However, these terms have now been broadened to encapsulate the general principle of these types of reaction  –  i.e. the transfer of electrons. Oxidation can be thought of as the process of losing electrons, and reduction as gaining electrons (in an analogous fashion to regarding acids as proton (H+ ) donors and bases as proton acceptors). Implicit in gaining an electron is gaining energy, hence reduction actually involves achieving an enhanced energy status. This may sound counter-intuitive as the word ‘reduction’ implies diminution, but if one considers that chemically it refers to gaining a negatively charged entity (an electron, e− ) then this aids understanding. Oxidation and reduction occur simultaneously in a reaction as an electron is transferred, and these reactions are therefore called redox reactions. Following on from this, oxidising agents are substances that are relatively electron poor and can gain electrons (indeed, they attract electrons) causing oxidation (electron loss) in another substance, but becoming themselves reduced, becoming electronenriched. The partner substance, a reducing agent, is electron- (and hence energy-) rich and donates an electron (to the electron acceptor – the oxidising agent) and hence reduces it, becoming itself oxidised: see Box 1.2. 

Oxygen is a powerful oxidising agent (the word ‘oxidising’ derives from oxygen) and is used in metabolism as an electron acceptor. Hydrogen is the reducing agent in many biological reactions and hence reduction could be termed ‘hydrogenation’ although this term has a specific meaning in chemistry, referring to the addition of hydrogen. 

Oxidation and reduction are characterised by a change in the oxidation state of the atoms involved. The oxidation state is the (theoretical) charge (its electron status or ‘count’) that an atom would have if all its bonds were entirely ionic (not true in practice due to covalent bonding) – hence oxidation state denotes the degree of oxidation of an atom; it may be positive, zero, or negative, and an increase in oxidation state during a reaction denotes oxidation of the atom, whilst a decrease denotes reduction, both resulting from electron transfer. The tendency of an atom to attract electrons to itself (i.e. to act as an oxidising agent) is denoted by its electronegativity, and is partly a function of the distribution of its own (valence) electrons; by contrast, the tendency of an atom to donate electrons (i.e. to act as a reducing agent) is denoted by its electropositivity. 

The chemically usable energy in a biomolecule which is a metabolic substrate is therefore present in the form of electrons, and therefore electron-rich molecules will be energy-rich and serve as good energy sources for metabolism. All three major metabolic substrate groups – carbohydrates, lipids, and proteins – contain these electrons in association with carbon-hydrogen (C–H) bonds. They can all be thought of as reduced (electron-rich) carbon (as found in wood, coal, house gas, and heating oil). In energy-yielding metabolism they act as reducing agents, donating these electrons to an electron acceptor, and ultimately themselves getting oxidised (the carbon ending up fully oxidised as $\mathrm { C O } _ { 2 }$ and the hydrogen as $_ \mathrm { H _ { 2 } O ) }$ . The ultimate electron acceptor (oxidising agent) is, of course, oxygen. 

$$
e. g.
$$

$$
\mathrm{C} _ {6} \mathrm{H} _ {1 2} \mathrm{O} _ {6} + 6 \mathrm{O} _ {2} \rightarrow 6 \mathrm{CO} _ {2} + 6 \mathrm{H} _ {2} \mathrm{O}
$$

$$
\text { glucose } \quad \text { oxygen } \quad \text { carbon   dioxide } \quad \text { water }
$$

This demonstrates the importance of oxygen in metabolism: a strong electron acceptor is required to permit adequate electron transfer (and energy yield) from energy-rich substrates to occur, the difference in free energy levels between the tendency of the reducing agent to donate electrons and of the oxidising agent to accept electrons representing the energy yield of the overall process. (This may be contrasted with fermentation reactions which do not involve net reductionoxidation, for example glycolysis of glucose to lactate: the energy yield is too small to sustain mammalian energy requirements and the substrate must be oxidised to maximise energy yield.) It can also be seen that lipids (e.g. fatty acids: CH (CH )n·COOH, where n is typically 12–16, Figure 1.4) are far more reduced (C–H bond-rich; electron-rich) than carbohydrates (e.g. glucose $\mathrm { C _ { 6 } H _ { 1 2 } O _ { 6 } } )$ , in which the carbon atoms are already partially oxidised, with fewer 

## Box 1.2 Redox reactions

![image](/assets/images/human_metabolism_images/404c4a3bfb7ac899e5ce068d4d77b0db.jpg)


for example: 

![image](/assets/images/human_metabolism_images/094a197793d8bd138d0903b2fc3c7e5c.jpg)


CH4 (reducing agent) donates 8 electrons, becoming oxidised (to CO2); 

O2 (oxidising agent) accepts 8 electrons, becoming reduced (to H2O); 

C–H bonds and therefore fewer energy-rich electrons to donate, and hence lipids contain far more energy (per gram) than carbohydrates. Amino acids are comparable to carbohydrates in the state of reduction of their carbon atoms, and hence of their energy content. 

However, if electrons were transferred directly from substrate (e.g. glucose, fatty acid) to oxygen, the large energy yield would be uncontrollable. Therefore, a long series of intermediary electron transfer (redox) reactions occur in which energy-rich e− is transferred sequentially and incrementally down a gradually decreasing (free) energy gradient. This explains why metabolic pathways are relatively long with many steps: small amounts only of energy are given off at each step. The energy (electron) extracted is then conveyed by electron carriers. Examples of electron carriers are NAD+ , NADP+ , and FAD. These are of course redox compounds themselves, accepting electrons (in the form of hydride ions H− , i.e. a hydrogen atom with the extra, energy-carrying electron) from the metabolic pathway (becoming reduced – e.g. NADH; NADPH; FADH ) and passing them on (becoming re-oxidised) to further carriers at sequentially lower energy levels (electron transport chain redox proteins) until ultimately oxygen accepts the electrons, becoming itself reduced to water. It is for this reason that many key energy-yielding reactions in metabolic pathways are catalysed by dehydrogenase enzymes linked to transfer of a hydride ion H− to the hydride acceptor NAD+ : 

![image](/assets/images/human_metabolism_images/f26220afa2b43ba7e9606022d2601f64.jpg)


The redox state of a cell refers to the proportion of these intermediary electron carriers that are in the reduced (high energy) state compared to those in the oxidised (low energy) form: the NAD+ : NADH ratio for example provides an estimate of the energetic ‘charge’ (potential) contained within the cell (in an analogous fashion to the phosphorylation potential denoting the amount of adenine nucleotide in the form of ATP) – it is for this reason that many metabolic pathways are regulated not only by the phosphorylation potential ([ATP]: [ADP] and [AMP]) but, as we are increasingly recognising, also by the redox potential (NAD+ : NADH; NADP+ :NADPH). 

## 1.2.2 The chemical characteristics of macronutrients

## 1.2.2.1 Carbohydrates

Simple carbohydrates have the empirical formula $\mathrm { C _ { n } ( H _ { 2 } O ) _ { n } ; }$ complex carbohydrates have an empirical formula which is similar to this (e.g. $\mathrm { C _ { n } } ( \mathrm { H } _ { 2 } \mathrm { O } ) _ { 0 . 8 \mathrm { n } } )$ . The name carbohydrate reflects the idea, based on this empirical formula, that these compounds are hydrates of carbon. It is not strictly correct but illustrates an important point about this group of compounds  –  the relative abundance of hydrogen and oxygen, in proportions similar to those in water, in their molecules. From the discussion above, it will be apparent that carbohydrates are mostly relatively polar molecules, miscible with, or soluble in, water. Carbohydrates in nature include the plant products starch and cellulose and the mammalian storage carbohydrate glycogen (‘animal starch’), as well as various simple sugars, of which glucose is the most important from the point of view of human metabolism. The main source of carbohydrate we eat is the starch in vegetables such as potatoes, rice, and grains. 

The chemical definition of a sugar is that its molecules consist of carbon atoms, each bearing one hydroxyl group (–OH), except that one carbon bears a carbonyl group (=O) rather than a hydroxyl. In solution, the molecule exists in equilibrium between a ‘straight-chain’ form and a ring structure, but as the ring structure predominates sugars are usually shown in this form (Figure 1.7). Nevertheless, some of the chemical properties of sugars can only be understood by remembering that the straight-chain form exists. The basic carbohydrate unit is known as a monosaccharide. Monosaccharides may have different numbers of carbon atoms, and the terminology reflects this: thus, a hexose has six carbon atoms in its molecule, a pentose five, and so on. Pentoses and hexoses are the most important in terms of mammalian metabolism. These sugars also have ‘common names’ which often reflect their natural occurrence. The most abundant in our diet and in our bodies are the hexoses glucose (grape sugar, named from the Greek γλυκύς [glykys] sweet), fructose (fruit sugar, from the Latin fructus for fruit), and galactose (derived from lactose, milk sugar; from the Greek γαλακτος [galaktos], milk), and the pentose ribose, a constituent of nucleic acids (the name comes from the related sugar arabinose, named from Gum arabic). 

Complex carbohydrates are built up from the monosaccharides by covalent links between sugar molecules. The term disaccharide is used for a molecule composed of two monosaccharides (which may or may not be the same), oligosaccharide for a short chain of sugar units, and polysaccharide for longer chains (>10 units), as found in starch and glycogen. Disaccharides are abundant in the diet, and again their common names often denote their origin: sucrose (table sugar, named from the French, sucre), which contains glucose and fructose (Figure 1.7); maltose (two glucose molecules) from malt; lactose (galactose and glucose) from milk. The bonds between individual sugar units are relatively strong at normal hydrogen ion concentrations, and sucrose (for instance) does not break down when it is boiled, although it is steadily broken down in acidic solutions such as cola drinks; but there are specific enzymes in the intestine (described in Chapter 4) which hydrolyse these bonds to liberate the individual monosaccharides. 

![image](/assets/images/human_metabolism_images/38bda709970700114c088a08ef3438ae.jpg)



Glucose (a hexose)


![image](/assets/images/human_metabolism_images/4d4af8896fe6313a1109fde45b3c5d3d.jpg)


![image](/assets/images/human_metabolism_images/a1a92930d714dfebffc0761045388d41.jpg)


![image](/assets/images/human_metabolism_images/8ee9c2f9d20baf2dfeacc11b14774cdf.jpg)



Sucrose (a disaccharide) (α-D-glucosido-β-D-fructose)



Figure 1.7 Some simple sugars and disaccharides. Glucose and fructose are shown in their ‘ring’ form. Even this representation ignores the true three-dimensional structure, which is ‘chair’ shaped: if the middle part of the glucose ring is imagined flat, the left-hand end slopes down and the right-hand end up. Glucose forms a six-membered ring and is described as a pyranose; fructose forms a five-membered ring and is described as a furanose. In solution the α- and β- forms are in equilibrium with each other and with a smaller amount of the straight-chain form. The orientation of the oxygen on carbon atom 1 becomes fixed when glucose forms links via this carbon to another sugar, as in sucrose; α- and β-links then have quite different properties (e.g. cellulose vs starch or glycogen).


Polysaccharides differ from one another in a number of respects: their chain length, and the nature (α- or β-) and position (e.g. ring carbons 1–4, 1–6) of the links between individual sugar units. Cellulose consists mostly of β-1,4 linked glucosyl units; these links give the compound a close-packed structure which is not attacked by mammalian enzymes. In humans, therefore, cellulose largely passes intact through the small intestine where other carbohydrates are digested and absorbed. It is broken down by some bacterial enzymes. Ruminants have complex alimentary tracts in which large quantities of bacteria reside, enabling the host to obtain energy from cellulose, the main constituent of their diet of grass. In humans there is some bacterial digestion in the large intestine (Chapter 4, Box 4.3). Starch and the small amount of glycogen in the diet are readily digested (Chapter 4). 

The structure of glycogen is illustrated in Figure 1.8. It is a branched polysaccharide. Most of the links between sugar units are of the α-1,4 variety but after every 9–10 residues there is an α-1,6 link, creating a branch. Branching makes the molecules more soluble, and also creates more ‘ends’ where the enzymes of glycogen synthesis and breakdown operate. Glycogen is stored within cells, not simply free in solution but in organised structures which may be seen as granules on electron microscopy. Each glycogen molecule is synthesised on a protein backbone, or primer, glycogenin. Carbohydrate chains branch out from glycogenin to give a relatively compact molecule called proglycogen. The glycogen molecules that participate in normal cellular metabolism are considerably bigger (Figure 1.8), typically with molecular weights of several million. The enzymes of glycogen metabolism are intimately linked with the glycogen granules. 

![image](/assets/images/human_metabolism_images/573370705295ba7d5fd388cd1d65837a.jpg)



Figure 1.8 Structure of glycogen. Left-hand side: each circle in the upper diagram represents a glucosyl residue. Most of the links are of the α-1,4 variety. One of the branch points, an α-1,6 link, is enlarged below. Amylopectin, a component of starch, has a similar structure. Amylose, the other component of starch, has a linear α-1,4 structure. Right-hand side: glycogen is built upon a protein backbone, glycogenin. The first layer of glycogen chains forms proglycogen, which is enlarged by addition of further glucosyl residues (by glycogen synthase and a specific branching enzyme, that creates the α-1,6 branch-points), to form macroglycogen. When glycogen is referred to in this book, it is the macroglycogen form that is involved. Source: pictures of proglycogen and macroglycogen taken from Alonso, M. D., Lomako, J., Lomako, W. M., & Whelan, W. J. (1995). FASEB Journal, 9:1126–1137. Copyright 1995 by Federation of American Societies for Experimental Biology (FASEB). Reproduced with permission of FASEB.


The carbohydrates share the property of relatively high polarity. Cellulose is not strictly water soluble because of the tight packing between its chains, but even cellulose can be made to mix with water (as in paper pulp or wallpaper paste). The polysaccharides tend to make ‘pasty’ mixtures with water, whereas the small oligo-, di-, and monosaccharides are completely soluble. These characteristics have important consequences for the metabolism of carbohydrates, some of which are as follows: 

(1) Glucose and other monosaccharides circulate freely in the blood and interstitial fluid, but their entry into cells is facilitated by specific carrier proteins. 

(2) Perhaps because of the need for a specific transporter for glucose to cross cell membranes (thus making its entry into cells susceptible to regulation), glucose is an important fuel for many tissues, and an obligatory fuel for some. Carbohydrate cannot be synthesised from the more abundant store of fat within the body. The body must therefore maintain a store of carbohydrate. 

(3) Because of the water-soluble nature of sugars, this store will be liable to osmotic influences: it cannot, therefore, be in the form of simple sugars or even oligosaccharides, because of the osmotic problem this would cause to the cells. This is overcome by the synthesis of the macromolecule glycogen, so that the osmotic effect is reduced by a factor of many thousand compared with monosaccharides. The synthesis of such a polymer from glucose, and its breakdown, are brought about by enzyme systems which are themselves regulated, thus giving the opportunity for precise control of the availability of glucose. 

(4) Glycogen in an aqueous environment (as in cells) is highly hydrated; in fact, it is always associated with about three times its own weight of water. Thus, storage of energy in the form of glycogen carries a large weight penalty (discussed further in Chapter 7). 

## 1.2.2.2 Fats

Just as there are many different sugars and carbohydrates built from them, so there are a variety of types of fat. The term fat comes from Anglo-Saxon and is related to the filling of a container or vat. The term lipid, from Greek, is more useful in chemical discussions since ‘fat’ can have so many shades of meaning. Lipid materials are those substances which can be extracted from tissues in organic solvents such as petroleum or chloroform. This immediately distinguishes them from the largely water-soluble carbohydrates. 

Among lipids there are a number of groups (Figure 1.4). The most prevalent, in terms of amount, are the triacylglycerols or triglycerides, referred to in older literature as ‘neutral fat’ since they have no acidic or basic properties. These compounds consist of three individual fatty acids, each linked by an ester bond to a molecule of glycerol. As discussed above, the triacylglycerols are very non-polar, hydrophobic compounds. The phospholipids are another important group of lipids  –  constituents of membranes and also of the lipoprotein particles which will be discussed in Chapter 10. Steroids  –  compounds with the same nucleus as cholesterol (Figure 1.6) –  form yet another important group and will be considered in later chapters, steroid hormones in  Chapter 6 and cholesterol metabolism in Chapter 10. 

Fatty acids are the building blocks of lipids, analogous to the monosaccharides. The fatty acids important in metabolism are mostly unbranched, long-chain (12 carbon atoms or more) carboxylic acids with an even number of carbon atoms. They may contain no double bonds, in which case they are referred to as saturated fatty acids, one double bond (mono-unsaturated fatty acids), or several double bonds  –  the polyunsaturated fatty acids. Many individual fatty acids are named, like monosaccharides, according to the source from which they were first isolated. Thus, lauric acid (C12, saturated) comes from the laurel tree, myristic acid (C14, saturated) from the Myristica or nutmeg genus, palmitic acid (C16, saturated) from palm oil, and stearic acid (C18, saturated) from suet, or hard fat (Greek στέαρ [steatos]). Oleic acid (C18, mono-unsaturated) comes from the olive (from Latin: olea, olive, or oleum, oil). Linoleic acid (C18 with two double bonds) is a polyunsaturated acid common in certain vegetable oils; it is obtained from linseed (from the Latin linum for flax and oleum for oil). 

The fatty acids mostly found in the diet have some common characteristics. They are composed of even numbers of carbon atoms, and the most abundant have 16 or 18 carbon atoms. There are three major series or families of fatty acids, grouped according to the distribution of their double bonds (Box 1.3). 

Differences in the metabolism of the different fatty acids are not very important from the point of view of their roles as fuels for energy metabolism. When considering the release, transport and uptake of fatty acids (not part of triacylglycerols), the term non-esterified fatty acids (NEFAs) will therefore be used without reference to particular molecular species. In a later section (Box 10.5) some differences in their effects on the serum cholesterol concentration and propensity to heart disease will be discussed. 

It will be seen from Figures 1.4 and 1.9 that saturated fatty acids, such as palmitic (16:0), have a natural tendency to fit together in nice orderly arrays. The unsaturated fatty acids, on the other hand, have less regular shapes (Figure 1.9). This is reflected in the melting points of the corresponding triacylglycerols  –  saturated fats, such as beef 

## Box 1.3 The structures and interrelationships of fatty acids

In the orthodox nomenclature, the position of double bonds is counted from the carboxyl end. Thus, α-linolenic acid (18 carbons, 3 double bonds) may be represented as cis-9,12, 15-18:3, and its structure is: 

$$
\begin{array}{l} \mathrm{CH} _ {3} - \mathrm{CH} _ {2} - \mathrm{CH} = \mathrm{C} ^ {1 5} \mathrm{H} - \mathrm{CH} _ {2} - \mathrm{CH} = \\ \mathrm{C} ^ {1 2} \mathrm{H} - \mathrm{CH} _ {2} - \mathrm{CH} = \mathrm{C} ^ {9} \mathrm{H} - (\mathrm{CH} _ {2}) _ {7} - \mathrm{C} ^ {1} \mathrm{OOH} \\ \end{array}
$$

(where the superscripts denote the numbering of carbon atoms from the carboxyl end). However, this is also known as an n-3 (or sometimes as an ω-3) fatty acid, since its first double bond counting from the non-carboxyl (ω) end is after the third carbon atom. On the latter basis, unsaturated fatty acids can be split into three main families, n-3, n-6, and n-9 (Table 1.3.1). 

The saturated fatty acids can be synthesised within the body. In addition, many tissues possess the desaturase enzymes to form cis-6 or cis-9 double bonds, and to elongate the fatty acid chain (elongases) by addition of two-carbon units at the carboxyl end. (These steps are covered in more 

detail in Box 5.4) But these processes do not alter the position of the double bonds relative to the ω end, so fatty acids cannot be converted from one family to another: an n-3 fatty acid (for instance) remains an n-3 fatty acid. Oleic acid (cis-9-18:1, n-9 family) can be synthesised in the human body, but we cannot form n-6 or n-3 fatty acids. Since the body has a need for fatty acids of these families, they must be supplied in the diet (in small quantities). The parent members of these families that need to be supplied in the diet are linoleic acid for the n-6 family and α-linolenic acid for the n-3 family. These are known as essential fatty acids. They can be converted into other members of the same family, although there seem to be health benefits of consumption of other members of the n-3 family, particularly 20:5 n-3 (eicosapentaenoic acid) and 22:6 n-3 (docosahexaenoic acid), found in high concentrations in fish oils. This is discussed further in Box 10.5. Some patients receiving all their nutrition intravenously have become deficient in essential fatty acids. The problem may be cured by rubbing sunflower oil into the skin! 


Table 1.3.1


<table><tr><td>Family</td><td>Source</td><td>Typical member</td><td>Simplified structure</td></tr><tr><td rowspan="3">Saturated</td><td rowspan="3">Diet or synthesis</td><td>Myristic</td><td>14:0</td></tr><tr><td>Palmitic</td><td>16:0</td></tr><tr><td>Stearic</td><td>18:0</td></tr><tr><td>n-9</td><td>Diet or synthesis</td><td>Oleic</td><td>9-18:1</td></tr><tr><td>n-6</td><td>Diet</td><td>Linoleic</td><td>9,12-18:2</td></tr><tr><td>n-3</td><td>Diet</td><td><eq>\alpha</eq>-linolenic</td><td>9,12,15-18:3</td></tr></table>

suet with a high content of stearic acid (18:0), are relatively solid at room temperature, whereas unsaturated fats, such as olive oil, are liquid. This feature may have an important role in metabolic regulation, although its exact significance is not yet clear. We know that cell membranes with a high content of unsaturated fatty acids in their phospholipids are more ‘fluid’ than those with more saturated fatty acids. This may make them better able to regulate metabolic processes  –  for instance, muscle cells with a higher content of unsaturated fatty acids in their membranes respond better to the hormone insulin, probably because the response involves the movement of proteins (insulin receptors, glucose transporters) within the plane of the membrane (discussed in Boxes 3.2, 3.4, and elsewhere), and this occurs faster if the membrane is more fluid. 

An important feature of the fatty acids is that, as their name implies, they have within one molecule both a hydrophobic tail and a polar carboxylic acid group. Long-chain fatty acids (12 carbons and more) are almost insoluble in water. They are carried in the plasma loosely bound to the plasma protein albumin. Nevertheless, they are more water miscible than triacylglycerols, which are carried in plasma in the complex structures known as lipoproteins (discussed fully in Chapter 10). The simpler transport of NEFAs is perhaps why they serve within the body as the immediate carriers of lipid energy from the stores to the sites of utilisation and oxidation; they can be released fairly rapidly from stores when required and their delivery to tissues is regulated on a minute-to-minute basis. 


(a)


![image](/assets/images/human_metabolism_images/bd05dca6dead41f3fd00ecc4c48d1b66.jpg)



(b)


![image](/assets/images/human_metabolism_images/d0630b0cd13b56f6432c0bee43bb0b19.jpg)



Figure 1.9 Pictures of the molecular shapes of different fatty acids. (a) saturated fatty acid, stearic acid (18:0), showing a straight chain; (b) mono-unsaturated fatty acid, oleic acid (18:1 n-9), showing a ‘bend’ in the chain at the double bond. Source: from Gurr, M. I., Harwood, J. L., Frayn, K. N., Murphy, D. J., & Michell, R. H. (2016). Lipids – Biochemistry, Biotechnology and Health. 6th edn. Oxford: Wiley.


But NEFAs would not be a good form in which to store lipid fuels in any quantity. Their amphipathic nature means that they aggregate in micelles (small groups of molecules, formed with their tails together and their heads facing the aqueous environment); they would not easily aggregate in a very condensed form for storage. They would also disrupt structural lipids such as those found in membranes. Triacylglycerols, on the other hand, aggregate readily; these hydrophobic molecules form uniform lipid droplets from which water is completely excluded, and which are an extremely efficient form in which to store energy (in terms of kJ stored per gram weight). This is illustrated in 

Figure 1.10. Thus, triacylglycerols are the form in which fat is mostly stored in the human body, and indeed in the bodies of other organisms; hence they are the major form of fat in food. NEFAs, on the other hand, are the form in which lipid energy is transported in a highly regulated manner from storage depots to sites of utilisation and oxidation. 

## 1.2.2.3 Proteins

Proteins are chains of amino acids linked through peptide bonds. Individual proteins are distinguished by the number and order of amino acids in the chain  –  the sequence, or primary structure. Within its normal environment, the chain of amino acids will assume a folded, three-dimensional shape, representing the secondary structure (local folding into α-helix and β-sheet) and tertiary structure (folding of the complete chain on itself ). Two or more such folded peptide chains may then aggregate (quaternary structure) to form a complete enzyme or other functional protein. 

In terms of energy metabolism, the first aspect we shall consider is not how this beautiful and complex arrangement is brought about; we shall consider how it is destroyed. Protein in food is usually denatured (its higher-order structures disrupted) by cooking or other treatment, and then within the intestinal tract the disrupted chains are broken down to short lengths of amino acids before absorption into the bloodstream. Within the bloodstream and within tissues we shall be concerned with the transport and distribution of individual amino acids. These are mostly sufficiently water soluble to circulate freely in the aqueous environment of the plasma. Only tryptophan is sufficiently hydrophobic to require a transporter; it is bound loosely (like the NEFAs) to albumin. Amino acids, not surprisingly, do not cross cell membranes by simple diffusion; there are specific transporters, carrying particular groups of amino acids (Chapter 2, Table 2.2). 

![image](/assets/images/human_metabolism_images/ce315d999417d1c3d8d8be0d638b410e.jpg)



Figure 1.10 Comparison of fat and carbohydrate as fuel sources. Raw potatoes (right) are hydrated to almost exactly the same extent as glycogen in mammalian cells. Olive oil (left) is similar to the fat stored in droplets in mature human adipocytes. The potatoes (1.05 kg) and olive oil (90 g) here each provide 3.3 MJ on oxidation. This emphasises the advantage of storing most of our energy in the body as triacylglycerol rather than as glycogen.


Protein is often considered as the structural material of the body, although it should not be thought of as the only structural material; it can only assume this function because of the complex arrangements of other cellular constituents, especially phospholipids forming cell membranes. Nevertheless, apart from water, protein is the largest single component in terms of mass of most tissues.1 Within the body, the majority of protein is present in the skeletal muscles, mainly because of their sheer weight (around 40% of the body weight) but also because each muscle cell is well packed with the proteins (actin and myosin) which constitute the contractile apparatus. But it is important to remember that most proteins act in an aqueous environment and are, therefore, associated with water. This is relevant if we consider the body’s protein reserves as a form of stored chemical energy. Since protein is associated with water, it suffers the same drawback as a form of energy storage as does glycogen; with every gram of protein are associated about 3g of water. It is not an energy-dense storage medium. Further, although protein undoubtedly represents a large source of energy that is drawn upon during starvation, it should be remembered that there is, in animals, no specific storage form of protein; all proteins have some function other than storage of energy. Thus, utilisation of protein as an energy source involves loss of the substance of the body. In evolutionary terms we might expect that this will be minimised (i.e. the use of the specific storage compounds glycogen and triacylglycerol will be favoured) and, as we shall see in later chapters, this is exactly the case. 

The monomers from which proteins are made, amino acids, have important chemical characteristics which endow them with the properties that make them ideal for assembling into a peptide chain. They comprise a central (‘α’) carbon, with characteristic chemical groups attached to its four valencies: an amino (NH ) group, a carboxyl (COOH) group, a hydrogen atom, and finally a variable (‘R’) group which defines the actual amino acid species (for example, if $\mathrm { R } = \mathrm { a }$ methyl group, $\mathrm { C H } _ { 3 } ,$ , then the resulting amino acid is alanine), illustrated in Figure 1.11. At acid pH, the amino group is ionised $\mathrm { ( N H } _ { 3 } ^ { + } )$ whilst at alkaline pH the carboxyl group is ionised (COO− ); at physiological pH (7.4) the amino acid is present as a Zwitter ion (both amino and carboxyl groups ionised). Proteins are assembled by adjacent amino acids forming a peptide bond between the carboxyl group of one and the amino group of another. This always leaves a terminal amino group and a terminal carboxyl group on any protein, hence all proteins act as buffers, able to gain or lose a proton. The carbon ‘backbone’ of individual amino acids is relatively energy rich and can be oxidised to yield energy once the amino group has been removed. 

![image](/assets/images/human_metabolism_images/108f8ef0bb6e6258d63b49d3cb36f76e.jpg)



Figure 1.11 Structure of an amino acid. At physiological pH (7.4) the carboxyl group is ionised to COO− and the amino group to $N H _ { 3 } ^ { + }$ . The nature of the ‘R’ group, or side-chain, defines the particular amino acid: the 20 different amino acids which constitute proteins each have a different R group.


## 1.3 General overview of metabolism

## 1.3.1 Human metabolic pathways

The body requires energy for chemical and mechanical work in order to maintain homeostasis; functions include maintenance of ionic gradients, transport, biosynthesis, heat generation and muscle contraction. Metabolism describes the series of biochemical reactions which provide the body with the energy it requires to maintain these biological functions. This energy must ultimately be derived from food, and is sourced from three groups of energy-rich substrates: carbohydrates, lipids, and amino acids (proteins). Multiple groups are utilised because they all have chemical and thermodynamic advantages and disadvantages, and together they provide energy under widely varying conditions and demands. All three nutrient groups exist in large, energy-rich macromolecular storage forms, discussed further in Chapter  7; they are all related to daily fluxes of energy substrates in the body. 

For energy mobilisation these are sequentially broken down into less energy-rich metabolites, the energy liberated being captured by intermediary reduction-oxidation molecules which carry the energy to a common pathway of oxidation linked to the phosphorylation of ADP to ATP. Hence, the energy is used to synthesise ATP, the common energy carrier to which most energyrequiring biological processes are linked. At a whole-body level this process is termed ‘catabolism’ (from the Greek: κατα (kato) – ‘down’ and βαλλω (ballo) – ‘throw’). Conversely, in energyrich states when energy intake exceeds expenditure, these metabolic pathways can be reversed, whereby ingested nutrients from all three groups are assembled into large storage macromolecules (‘anabolism’; again, from the 


Catabolism and Anabolism


![image](/assets/images/human_metabolism_images/fbebcb77d109c70b16974f7fc253e204.jpg)



Figure 1.12 Catabolism and anabolism.


Greek: ανα $[ a n d ] - \mathrm { \dot { \ u p } } )$ . The process of assembling excess energy-rich substrate precursors into complex energy storage molecules is termed anabolism, whilst processes converting substrates into energy-poor end-products to mobilise biologically usable energy, are termed catabolism (Figure 1.12 and Box 1.4). Imbalance of these pathways leads to cachexia (wasting) or obesity, with implications for both energy provision and health. Tissues have specialised metabolic functions – e.g. adipose tissue stores energy, muscle oxidises substrate, lactating mammary gland exports substrate. The liver is a metabolic ‘transformer’ that regulates substrate supply between tissues, and pancreas is the principal afferent detector, and signaller, of nutritional status. 

The rate of energy production is measured under basal conditions (no voluntary muscle contraction; thermoneutrality) – ‘basal metabolic rate’ (BMR), and is affected by many factors, including muscle contraction, food ingestion, size, gender, age, temperature, sepsis, and several hormones, including thyroid hormones and catecholamines. The metabolic rate can be estimated by measuring the oxygen consumption $\mathrm { ( V O _ { 2 } ; }$ indirect calorimetry). For carbohydrate metabolism the rate of $\mathrm { C O } _ { 2 }$ production (VCO ) equals $\mathrm { V O } _ { 2 } \ : ( \mathrm { C } _ { 6 } \mathrm { H } _ { 1 2 } \mathrm { O } _ { 6 } +$ 

$6 \mathrm { O } _ { 2 } \to 6 \mathrm { C O } _ { 2 } + 6 \mathrm { H } _ { 2 } \mathrm { O } )$ ) and the ratio $\mathrm { V C O _ { 2 } / V O _ { 2 } } ,$ , termed the respiratory quotient (RQ), is $6 / 6 = 1$ . For lipid oxidation, however, this is not true (e.g. tripalmitin: $\mathrm { 2 C _ { 5 1 } H _ { 9 8 } O _ { 6 } + 1 4 5 O _ { 2 }  1 0 2 C O _ { 2 } + }$ $9 8 \mathrm { H } _ { 2 } \mathrm { O } ; \mathrm { R Q } = 1 0 2 / 1 4 5 = 0 . 7 0 )$ ) and measurement of RQ can provide useful information on substrate selection and utilisation. This will be discussed further in Chapter 11 (Box 11.2). 

## 1.3.1.1 Energy transduction

Chemical energy transduction is the process of transferring energy between different forms, and involves two main biochemical energy carrier types: (i) ATP (and also, less ubiquitously, GTP and creatine phosphate) which carries energy in the form of ‘high energy’ phosphate groups and (ii) NADH, NADPH, and $\mathrm { F A D H } _ { 2 }$ , which carry energy in the form of an electron (actually, as discussed above, a hydrogen atom with an extra electron – a hydride ion: H− ). The energy status of the cell may be quantified with either of these systems – hence, (i) the ‘energy charge’ (phosphorylation potential) of the cell is an index of the degree of ATP phosphorylation (the amount of AMP that is phosphorylated to ADP and $\mathrm { A T P : = [ A T P ] + [ ^ { 1 } / 2 A D P ] \ : }$ $\mathrm { [ A T P ] ~ + ~ [ A D P ] ~ + ~ [ A M P ] ) }$ , and (ii) the ‘redox 

## Box 1.4 Anabolism and catabolism

The terms anabolism and catabolism are useful but can be confusing and have frequently been misused. They should be used to refer to whole-body energy strategy: 

cle, breaking down glucose to provide energy for contraction (net energy mobilisation), but ‘anabolic’ in liver in the well-fed postprandial state, when absorbed glucose is converted to 

![image](/assets/images/human_metabolism_images/ae941bcd8f0a3ae92bfb57b895969b95.jpg)


Hence, in the postprandial state, after a meal, we are entering an anabolic state, whereas in the post-absorptive state, following absorption and disposition of the meal, we are entering a catabolic state. This is signalled by insulin. 

Classic physiological catabolic states include fasting/starvation (decreased energy intake) and exercise (increased energy expenditure). Diabetes mellitus is an example of a pathological catabolic state (failure of insulin signalling). 

If the terms are applied to individual metabolic pathways, or even individual steps, confusion can arise. For example glycolysis may be thought of as ‘catabolic’ in exercising muspyruvate, but the resulting acetyl-CoA undergoes lipogenesis to fat for energy storage. When analysing metabolism it is important to consider the whole body (anabolic? catabolic?) as well as individual tissues, as these all have specialised metabolic profiles and functions (see Chapter 5). 

The body is subject to many catabolic signals (e.g. ‘stress hormones,’ catecholamines, glucocorticoids, glucagon etc., but one major anabolic signal – insulin. Insulin inhibits catabolism, and therefore when it declines, unopposed catabolism results. This is one reason why insulin is such a crucial signal, and diabetes such an important disease. 

potential’ of the cell denotes the degree of reduction of NAD+ (i.e. the NADH:NAD+ ratio) and NADP+ (NADPH:NADP+ ). Besides carrying energy ‘down’ (catabolism) or ‘up’ (anabolism) metabolic pathways (Figure 1.12), the energy charge/ phosphorylation potential and redox potential are major regulators of metabolic pathways to ensure appropriate energy provision. 

## 1.3.1.2 Energy substrates

By utilising three, chemically diverse, fuel groups, overall metabolic flexibility and hence efficiency are achieved. Energy derived from these compounds is all based on a reduced carbon atom i.e. the C–H bond. Hence, the more C–H bonds, the more reduced the molecule and the more energy it contains, whereas oxidised or partially oxidised carbon (C–O) lacks biochemically usable energy (see Section 1.2.1.3). However, generally speaking, the more reduced the substrate, the less water soluble it is likely to be. This may be an advantage or a disadvantage, depending on the role of the substrate. 

Carbohydrates are partially oxidised and hence do not contain as much energy $( 1 7 \mathrm { k J ~ g ^ { - 1 } } )$ as the highly reduced (–CH rich) lipids. However, carbohydrates are soluble, hence quickly mobilised and utilised, and are relatively non-toxic. Furthermore, some energy can be derived from them anaerobically during hypoxia or ischaemia. However, their water solubility means that in storage form (glycogen) they retain significant water of hydration (about three times their own weight), lowering their energy density and efficiency as energy stores (see Figure 1.10): only very limited amounts are stored (hepatic glycogen ∼ 100g only), but since they can be converted to many other substances, including lipids and intermediates of the tricarboxylic acid (TCA) cycle (also known as the Krebs cycle – see Section 1.3.1.4), they are therefore metabolically ‘flexible’ – carbohydrates are able to supply intermediary metabolites to maintain pathway integrity (anaplerosis, again from the Greek ανα (ana), up, πληρω (plero), to fill) in contrast to lipids, oxidation of which leads to depletion of intermediary metabolites (cataplerosis): hence some carbohydrate is always required for metabolism to proceed efficiently, as captured in the old aphorism ‘fat burns in the fire of carbohydrate.’ This is discussed later (Box 5.3). 

Fats are the most energy-dense metabolic fuels $( - 3 7 \mathrm { k J ~ g ^ { - 1 } } )$ : lipids are highly reduced (energetic), water-insoluble, and very energy-dense, hence their function as the principal energy store for free-living animals, and are major energy providers to most (oxidative) tissues. However, their water-insolubility makes lipids problematic and slow to mobilise, and unlike carbohydrates they cannot yield energy anaerobically – they must be oxidised, therefore cannot be used by red blood cells (erythrocytes) and renal medulla. Because they are more reduced, relatively more oxygen is required to extract energy from lipids (2.8 ATP/ O ) compared to carbohydrates (3.7 ATP/O ) and this may be critical in high work-load oxygenchallenged tissues such as myocardium (and exercising skeletal muscle). The storage form of lipids for energy provision is triacylglycerol, which comprises three fatty acids esterified to a glycerol backbone. Being highly hydrophobic and reduced, triacylglycerols are very energy dense and a highly efficient energy store. However, triacylglycerols are relatively slow to mobilise, must be oxidised to yield energy and cannot provide energy anaerobically, and the NEFAs from which they are assembled are amphipathic (detergentlike) and hence potentially toxic in high concentrations, disrupting structural lipids especially in the central nervous system: they cannot cross the blood-brain barrier so also cannot be used by the central nervous system (more detail in Section 5.6). Furthermore, fatty acids cannot be converted into carbohydrates or proteins, limiting their metabolic flexibility. 

Proteins (polymers of amino acids) have similar energy content to carbohydrates $( \sim 1 7 \mathrm { ~ k J ~ g ^ { - 1 } ) }$ , but each protein has a specific biological function and they are not used as dedicated energy stores. Amino acids (proteins) have similar energy yields to carbohydrates i.e. they are partially oxidised to about the same extent as carbohydrates, and overall have comparable solubility; since most can be converted into glucose (‘glucogenic’), they have similar metabolic flexibility to carbohydrates. In catabolic states of carbohydrate depletion (e.g. starvation), however, proteins are broken down to their constituent amino acids for conversion into glucose to supply glucose-dependent tissues such as brain and erythrocytes for energy, and also to provide general tissue anaplerosis – hence proteins constitute a ‘virtual’ carbohydrate store in catabolic states of carbohydrate exhaustion. 

## 1.3.1.3 Metabolic strategy

Whole body metabolic strategy comprises breaking down large macronutrient storage molecules (triacylglycerols, glycogen, protein  –  by lipolysis, glycogenolysis, and proteolysis respectively) into smaller energy-rich substrate molecules (NEFAs, glucose, amino acids) with distinct characteristics and roles. In the next stage of metabolism these small substrates are converted into a common fuel, acetyl-CoA (by β-oxidation, glycolysis and amino acid metabolism respectively). In the final stage of metabolism the acetyl-CoA is fully oxidised by the TCA cycle into carbon dioxide within the mitochondria. The step-wise release of energy from these pathways is carried as a hydride (H− ) ion by $\mathrm { N A D ^ { \bar { + } } }$ and FAD as their reduced forms, NADH and $\mathrm { F A D H } _ { 2 } \mathrm { : }$ these redox carriers are then reoxidised by the electron transport chain, the energy derived being used to phosphorylate ADP to ATP (oxidative phosphorylation). By contrast, in anabolism these pathways are reversed, chemical energy being used to synthesise complex energy-rich storage macromolecules from simple precursor substrates (Figure 1.12). 

Three key features of metabolism impact metabolic strategy and energy provision: 

Most energy stored in the body is in the form of lipid (triacylglycerols); 

This lipid cannot be converted to carbohydrate; and 

All tissues require some glucose for normal metabolic functioning, and some tissues (glycolytic, lacking mitochondria such as erythrocytes) have an absolute requirement for glucose or cannot utilise NEFAs (brain). 

Since very little carbohydrate is stored (∼100 g hepatic glycogen; <1 day if it was the sole fuel), in catabolic states glucose is rapidly depleted and alternative mechanisms are required to provide or replace glucose: under these conditions breakdown of protein to amino acids, and then conversion of these to glucose by gluconeogenesis, becomes an essential pathway. Indeed, the ability of the body to divert protein from its primary (e.g. contractile) function to a secondary function of glucose provision has been the adaptation that has allowed such limited stores of the energy densityinefficient glycogen to be permitted. Another mechanism is ketogenesis, whereby the liver converts triacylglycerol-derived NEFAs into small, soluble (non-amphipathic) ketone bodies, which can be utilised by many tissues, including brain, hence acting as a ‘glucose-sparing’ substrate. 

During conditions of energy repletion, energy in excess of current requirements is stored in a tissue-specific manner (lipid as triacylglycerols principally in adipose tissue; carbohydrate as glycogen in most tissues but specifically in liver for glucose release to maintain blood glucose concentration; amino acids ‘virtually’ in labile, expendable proteins, e.g. skeletal muscle contractile protein). In subsequent periods of limited energy ingestion (postabsorptive, fasted) this substrate resource can be mobilised in a regulated fashion and directed to specific tissues according to their metabolic requirement. These pathways are illustrated schematically in Figure 1.13. 

![image](/assets/images/human_metabolism_images/b376b2ccffcb8463c6e0fb5dab25902f.jpg)



Figure 1.13 Overall metabolic energy flux. The three energy groups (fats, carbohydrates, proteins) are stored in macromolecular form and can be broken down into small, monomolecular units prior to conversion to the common ‘fuel’ acetyl-CoA to be oxidised in the TCA (tricarboxylic acid) cycle – catabolism. At times of energy excess, the smaller units are assembled into the larger storage molecules – anabolism. Crucially, the conversion of pyruvate into acetyl-CoA (by pyruvate dehydrogenase) is irreversible, hence carbohydrates can be converted into fats, but fats cannot be converted into carbohydrates. 1, esterification; 2, lipolysis; 3, glycogenesis; 4, glycogenolysis; 5, protein synthesis/proteolysis; 6, lipogenesis; 7, β-oxidation; 8, gluconeogenesis; 9, glycolysis; 10, pentose phosphate pathway. Coloured arrows indicate direction of anabolic and catabolic flux, though glycolysis and gluconeogenesis do not always fit this paradigm, depending on nutritional state and particular tissue.


Overall metabolic strategy for energy provision depends on substrate fluxes within and between the three major substrate groups (Figure 1.13). Catabolism is represented as downward flux, anabolism as upward flux (though the situation is a little more complex than this, as we shall see – gluconeogenesis is active in catabolism, and glycolysis in anabolism. This is why the terms anabolism and catabolism are best reserved for the whole-body situation). Each group has a ‘storage’ macromolecule/polymer which can be broken down to individual, relatively small monomeric units in the first stage of metabolism; in the second stage of metabolism, these monomeric units are all converted into a common fuel molecule, acetyl-CoA; in the third stage of metabolism, the acetyl-CoA is completely oxidised to $\mathrm { C O } _ { 2 } + \mathrm { H } _ { 2 } \mathrm { O }$ by the TCA cycle and electron transport chain. In intermediary metabolism it is convenient to think in terms of numbers of carbons rather than molecular weight, since carbon (C–H) represents the energy source of the substrate. Glucose (6 carbons) is stored as glycogen (hundreds of thousands of carbons). NEFAs, or ‘free’ fatty acids (typically 16 or 18 carbons) are esterified with glycerol and stored as triacylglycerols (about 60 carbons). Amino acids (typically 3–6 carbons) are not stored as an energy reserve as such but are available in reserve as proteins (again, depending on protein size, representing thousands of carbons). Acetyl-CoA comprises an acetyl group (2 carbons: CH3·CO–) attached to a carrier molecule (Coenzyme A, CoA). Oxidation of acetyl-CoA by the TCA cycle produces two $\mathrm { C O } _ { 2 }$ molecules (i.e. the acetyl group is completely oxidised). This is highly efficient but means that acetyl-CoA cannot contribute to the dynamic pool of TCA cycle intermediates i.e. it cannot replete the intermediates of the TCA cycle as it is completely oxidised with each turn of the cycle – these must be derived from carbohydrate (>3 carbon) units. Carbohydrate metabolism yields pyruvate (3 carbons), which is next decarboxylated to acetyl-CoA (and CO2) by pyruvate dehydrogenase (PDH). PDH is essentially irreversible (far from equilibrium): acetyl-CoA cannot be converted back to pyruvate. For this reason, carbohydrates cannot be synthesised from the common fuel acetyl-CoA (Figure 1.13). Lipid metabolism comprises lipolysis of triacylglycerols to three NEFAs (+ the glycerol backbone), followed by splitting the fatty acid chain into 2-carbon units: acetyl-CoA (β-oxidation). The acetyl-CoA can be readily oxidised by the TCA cycle to provide energy but it cannot be converted to pyruvate, nor, therefore, to synthesise carbohydrates. The fatty acid chain represents an assembly of 2-carbon (acetyl-CoA-equivalent) units, and the pathway of lipogenesis utilises excess acetyl-CoA (derived from glycolysis and PDH) to synthesise fatty acids and hence triacylglycerol. Indeed triacylglycerol-fatty acid simply represents a storage form of excess acetyl-CoA (hence most fatty acids have even numbers of carbons). This means that whilst excess carbohydrate (glucose) can be readily converted to lipid (through acetyl-CoA), the reverse is not true. This is important because most stored energy is in the form of energy-dense lipid (triacylglycerol), with very little stored as glycogen, (too inefficient; <1 day supply); however, certain tissues (brain, erythrocytes, renal medulla) have an absolute requirement for glucose, and in the face of limited glycogen storage in starvation this is met by protein catabolism. 

Passage of carbohydrate carbon through PDH represents an irreversible ‘gate’ through which the carbon cannot gain re-entry, committing carbohydrate to energy provision, either by immediate oxidation of acetyl-CoA, or by storage of the acetyl-CoA as lipid (fatty acid, triacylglycerol) for reconversion back to acetyl-CoA and oxidation at a later date (e.g. in subsequent starvation); this is the reason why PDH is such a highly regulated enzyme  –  it represents the major control point between carbohydrate and lipid metabolism (Figure 1.13). 

## 1.3.1.4 Tricarboxylic acid (TCA) cycle

Oxidation of the 2-carbon acetyl $\mathrm { ( C H _ { 3 } . C O - ) }$ group of acetyl-CoA is achieved by the TCA cycle within the mitochondrial matrix, with the energy from the oxidation of one acetyl group released in the form of electrons (associated with a hydrogen atom as a hydride (H− ion; see Section 1.2.1.3)) and carried by $\mathrm { N A D ^ { + } }$ (×3 per acetyl group, i.e. per turn of the cycle) and FAD (×1) in their reduced forms (NADH; FADH ). In addition, one step involves a substrate-level phosphorylation  –  a chemical step which is directly linked to the phosphorylation of ADP (or GDP) to ATP (or GTP) without the need for mitochondrial oxidative phosphorylation – converting GDP into GTP (or ADP into ATP in some cells). 

In the TCA cycle (Box 1.5), the 2-carbon acetyl group of acetyl-CoA combines with oxaloacetate (4 carbons) to form the 6-carbon compound citrate (a TCA, hence the name of the cycle; it is also referred to as the citrate cycle or Krebs cycle). The citrate undergoes two decarboxylation reactions, yielding both the two carbon dioxides and 2 NADH (‘oxidative decarboxylation’ reactions), to form succinyl-CoA (4 carbons). The remainder of the cycle concerns regenerating oxaloacetate from the succinyl-CoA: this process involves the (substrate-level) phosphorylation of GDP to GTP and two further oxidations, yielding the FADH and the third NADH, together with the oxaloacetate. 

The stoichiometry is precise, such that both the carbons of the acetyl group are oxidised (though as shown by radiolabelling experiments, not the actual two carbon atoms that entered the cycle), hence all their useful energy is extracted, resulting in two carbon dioxide molecules as ‘waste’ products. The NADH and FADH will subsequently be re-oxidised by passing on the electron(s) they carry down the redox proteins of the electron transport chain, regenerating NAD+ and FAD in the process for further electron carriage; by coupling this sequential oxidation-reduction to phosphorylation of ADP to ATP (‘oxidative phosphorylation’), a common energy carrier for diverse cellular functions (ATP) is synthesised (see below). 

An important point about the TCA cycle is that its intermediates are not specifically dedicated to the cycle – they are also used for other purposes in several other metabolic pathways (e.g. amino acid metabolism; porphyrin synthesis; purine nucleotide metabolism). Processes which utilise TCA cycle intermediates and hence deplete them are termed ‘cataplerotic’ whilst processes which replenish them are termed ‘anaplerotic.’ In order for a substance to be anaplerotic it must have more than two carbons (or equivalent): acetyl groups cannot replenish the cycle because both their carbons (equivalent) are oxidised by the cycle $( 2 \times \mathrm { C O } _ { 2 } )$ and no net gain of carbon occurs. Since fatty acids represent a chain of 2-carbon groups (they are, effectively, a storage form of acetyl groups – hence their mostly even numbers of carbons), when fatty acids are used for energy (e.g. during starvation) they are broken 


Box 1.5 Tricarboxylic acid cycle: overall scheme


![image](/assets/images/human_metabolism_images/96cda7efac02524ba16e5328df37e669.jpg)


Acetyl-CoA is oxidised by losing electrons (H− ions) and ends up as ${ \mathsf { C O } } _ { 2 } .$ . The electrons are captured by NAD+ and FAD to become their reduced forms, NADH and $\mathsf { F A D H } _ { 2 }$ (and they will in turn pass these electrons on to other electron carriers in the electron transport chain, becoming re-oxidised themselves and ready for further electron carriage). This is 

achieved in a step-wise fashion by the TCA or Krebs cycle. In addition, as part of the controlled release of energy, one of the steps of the TCA cycle does not have sufficient energy to reduce ${ \mathsf { N A D } } ^ { + }$ or FAD but does have sufficient energy to phosphorylate GDP to GTP. One acetyl-CoA molecule reduces one FAD and three NAD+ molecules. 

back down to 2-carbon acetyl groups (by β-oxidation) and cannot therefore be anaplerotic – indeed reliance on fatty acids for oxidation does lead to cataplerosis: if a cell were to derive its energy entirely from fatty acids, eventually cataplerotic depletion of TCA cycle intermediates would occur due to ongoing utilisation of the intermediates by other pathways, combined with the inability of the fatty acids (acetyl groups) to ‘top up’ the same cycle intermediates. The same applies for ketone bodies (acetoacetate, 3-hydroxybutyrate) which are 4-carbon compounds but effectively represent two acetyl groups joined together  –  a transport form of acetyl-CoA; their utilisation first requires them to be converted back into acetyl-CoA, and they cannot enter the TCA cycle as 4-carbon compounds. Anaplerosis has to occur from carbohydrates or (glucogenic) amino acids, which can bypass the PDH step and insert 4-carbon intermediates (e.g. oxaloacetate; derived from pyruvate) into the cycle. The importance of these anaplerotic pathways, and the enzymes that achieve them, to maintain cellular metabolic efficiency is now well recognised. See later, Box 5.3, for more information. 

## 1.3.1.5 Electron transport chain

The final stage of energy production is the synthesis of ATP by phosphorylation of ADP, coupled to the re-oxidation of NADH and FAD $\mathrm { { I } } _ { 2 }$ to permit further electron carriage to occur (oxidative phosphorylation). The energy is now carried in the phosphoanhydride bonds of the phosphate groups of ATP; these are commonly called ‘high energy’ bonds (see Box 1.6). 

The energy for the phosphorylation is derived from the electrons contained in the reduced forms of the electron carriers. As the electron is passed sequentially down a series of carriers, the released energy is harnessed. The mechanism responsible is the electron transport chain, located in the inner mitochondrial membrane (IMM). The IMM is a highly specialised membrane which is extremely selectively impermeable. It comprises four protein complexes (complex I, II, III, IV) together with a loosely associated cytochrome (cytochrome c) and the (non-protein) quinone CoQ10 (ubiquinone). All these components have variable redox states and act as electron acceptors (oxidising agents) 

## Box 1.6 High-energy bonds

The term ‘high-energy bond’ is not strictly accurate. They are not ‘special’ bonds, but rather they release their free energy when hydrolysed. They may be denoted ∼, and it can be seen that ADP can act as a source of energy when its terminal phosphate group is hydrolysed to AMP. 

AMP: Ad-P 

ADP: Ad-P∼P 

ATP: Ad-P∼P∼P 

ADP has a special role in bioenergetics because beside acting as a (limited) energy source in its own right, its availability is one factor that regulates the rate of ATP synthesis. 

A close structural analogue of adenosine triphosphate (ATP) is guanosine triphosphate (GTP) which also carries energy. The presence of these two forms of energy carriage likely represents a form of metabolic compartmentation, separating pathways by their molecular preferences. GTP also has a function in regulation, especially in signal transduction involving G-proteins. 

and electron donors (reducing agents); they can function as electron carriers by shifting between their reduced (electron containing) and oxidised (electron deficient) forms. To facilitate this, the proteins contain transition metals (Fe, Cu), complexed in prosthetic groups (e.g. haem) or complexed to sulphur (Fe-S centres) which are readily capable of gaining or losing an electron. They are organised in a sequential arrangement within the IMM such that the electrons are passed down a gradual incremental energy gradient. Complex I oxidises NADH back to NAD+ , whilst complex II oxidises FADH back to FAD, both passing electrons (as pairs) to CoQ10, thence to complex III, then cytochrome $^ { \mathrm { c } , }$ and eventually to complex IV. Complex IV, the final redox protein in the chain, combines the electrons it receives with molecular oxygen $\mathrm { ( O } _ { 2 } \mathrm { ; }$ , the final electron acceptor), reducing it to water. Complexes I, III, and IV use the energy of electron transfer to pump protons (H+ ) out of the mitochondrial matrix across the IMM and into the intermembrane space beyond. This creates an electrochemical gradient between the inside and outside of the mitochondrion. The energy of this H+ gradient is finally utilised to drive phosphorylation of ADP to ATP: the protons can only re-enter the mitochondrial matrix by passing through ATP synthase (Fo/F ATPase; also called complex V although it is not a part of the actual electron transport chain), another IMM-spanning protein. Proton passage through this large protein complex provides the energy for ATP synthesis (the chemiosmotic process). Hence, provided the IMM is otherwise impermeable to protons, the oxidation of NADH/FADH by electron transport is tightly coupled to the phosphorylation of ADP to ATP. However, if protons leak through the IMM back into the mitochondrial matrix, the gradient is dissipated (‘uncoupled’) and ATP synthesis cannot occur, leading to mitochondrial inefficiency. The final step in metabolism is the export of ATP out of the mitochondrion and into the cytosol, and this is achieved by an adenine nucleotide translocator also spanning the IMM. 

In the remainder of this chapter, we will outline the major metabolic pathways of ‘energy metabolism’ that will be considered further in this book, signposting the reader to where these are discussed in more detail. 

## 1.3.2 Carbohydrate metabolism

## 1.3.2.1 Pathways of glucose metabolism

Carbohydrate metabolism centres around the hexose sugar glucose (Figure 1.7). Glucose is a ubiquitous sugar which may be derived from dietary carbohydrate or synthesised in the body. It is stored in polymeric form as glycogen: this removes the osmotic problems that would arise if it were stored in cells as free sugars (Section 1.2.2.1). Glucose, as a polar molecule, cannot cross membranes composed of phospholipid bilayers by diffusion, and two families of glucose transporter proteins (GLUTs, and sodium-glucose linked transporters, SGLTs: see Chapter 2, Box 2.2), expressed in a tissue-specific manner, facilitate its rapid movement in and out of cells. The pathways of glucose metabolism inside the cell are illustrated in simplified form in Figure 1.14, which shows the key steps of the various pathways responsible for its utilisation, disposal and production. Glucose can be stored as glycogen, used to provide 5-carbon sugars and NADPH for, e.g. nucleotide synthesis, and lipogenesis, respectively, and split into pyruvate for further metabolism. It can be synthesised by gluconeogenesis, or by breaking down glycogen. 

## 1.3.2.1.1 Glucose phosphorylation

Following uptake into the cell by glucose transporters, the first step of glucose metabolism within cells is always phosphorylation to glucose 6-phosphate (G6-P), brought about by a member of a family of enzymes (hexokinases) that use ATP, again expressed in a tissue-specific manner. The form expressed in liver and pancreatic β-cells, hexokinase Type IV, is generally known as glucokinase; that expressed in skeletal muscle, Type II, is generally known simply as hexokinase. Phosphorylation ensures that the molecule does not diffuse again out of the cell, locking it into the cell, maintaining its inward concentration (and augmenting further glucose influx), and activating the molecule for further metabolism. G6-P is used by glycolysis (glucose breakdown, next section) and glycogen synthesis as well as the pentose phosphate pathway (Section 1.3.2.1.7 below); it may also be derived from glycogen breakdown (glycogenolysis) and gluconeogenesis (glucose synthesis: Section 1.3.2.1.5 below) depending on tissue and prevailing metabolic state. Thus, G6-P may be seen as lying at a major crossroads in carbohydrate metabolism (Figure 1.14). 

## 1.3.2.1.2 Glycolysis

Glucose (6 carbons: molecular formula $\mathrm { C _ { 6 } H _ { 1 2 } O _ { 6 } } )$ is broken down by the pathway of glycolysis to pyruvate (3 carbons: $\mathrm { C _ { 3 } H _ { 4 } O _ { 3 } } ,$ , showing that H has been lost relative to C and O; i.e. overall this is a partial oxidation); the term glycolysis refers to this splitting of the glucose molecule. A small amount of ATP is generated by substrate-level phosphorylation in glycolysis, hence some usable energy is generated. Indeed, this is a cytosolic pathway and occurs even in cells that lack mitochondria, such as red blood cells (it is their only route for making ATP). Glycolysis ends at pyruvate. This important intermediate can be subsequently: 1, reduced to lactate $\mathrm { ( C _ { 3 } H } _ { 6 } \mathrm { O } _ { 3 } ,$ so exactly half a glucose molecule with no redox changes  –  a true fermentation reaction); 2, oxidised (and decarboxylated) to form acetyl-CoA; 3, carboxylated to form oxaloacetate (anaplerosis); or 4, transaminated to form the amino acid alanine (see Section 1.3.4 below). 

![image](/assets/images/human_metabolism_images/5856337844d2bda0925d018e17a02cc5.jpg)



Figure 1.14 Pathways of glucose metabolism inside the cell. The pathways of glucose (carbohydrate) metabolism are shown with the key (regulatory and energy-yielding) steps marked. Glycolysis (splitting of glucose) is the major top-to-bottom pathway, and it results in two pyruvate molecules: i.e. fructose 1,6-bisphosphate is split, and the products are doubled. G 6-P, glucose 6-phosphate; F 6-P, fructose 6-phosphate; F 1,6-BP, fructose 1,6-bisphosphate; PEP, phosphoenolpyruvate; OAA, oxaloacetate.


Glycolysis is a primitive but vital pathway that occurs in the cytosol of all cells and comprises an initial energy investment phase (priming – phosphorylation) followed by splitting (6 carbons into $2 \times 3$ carbons), and an energy generation phase of oxido-reduction and phosphorylation. During this phase $\mathrm { N A D ^ { + } }$ is reduced to NADH and ATP is produced by substrate-level phosphorylation. Glycolysis of one molecule of glucose therefore yields two molecules of pyruvate, 2 ATP and 2 NADH without requiring oxygen. Glycolysis is a vital pathway because of its multiple functions. In muscle, glycolysis splits glucose in order to provide energy, but in liver, excess glucose remaining once glycogen stores have been repleted is broken down by glycolysis to pyruvate, then acetyl-CoA, for lipid synthesis. 

## 1.3.2.1.3 Lactate and ethanol metabolism

The reduction of glycolysis-derived pyruvate to lactate by the near-equilibrium (freely reversible) enzyme lactate dehydrogenase is an important mechanism to permit glycolysis to proceed. Glycolysis involves one redox step that is linked to NADH formation from $\mathrm { N A D ^ { + } }$ . Normally, when oxygen is present in the cell, the NADH is reoxidised back to $\mathrm { N A D ^ { + } }$ by the electron transport chain within the mitochondria: this is vital because the $\mathrm { N A D ^ { + } }$ is required for further electron capture to permit glycolysis to proceed. In the absence of oxygen however, (or, indeed, in the absence of mitochondria, as in red blood cells), NADH would accumulate and $\mathrm { N A D ^ { + } }$ concentration would fall too low. By converting pyruvate to lactate and linking this to NAD, the $\mathrm { \bar { N } A D ^ { + } }$ is regenerated to permit glycolysis to proceed, but at the cost of accumulating lactate (Figure 1.15a). When oxygen becomes available, lactate dehydrogenase can readily convert the lactate back to pyruvate (and NADH) for oxidation (and red blood cells export the lactate to the liver to be converted back into pyruvate). 

Yeast employ a different strategy to oxidise NADH and regenerate $\mathrm { N A D ^ { + } }$ . Instead of reducing pyruvate to lactate, they reduce pyruvate to ethanol $\mathrm { ( C H _ { 3 } . C H _ { 2 } . O H ) }$ by the process of alcoholic fermentation, shown in Figure 1.15b. Pyruvate is first decarboxylated to acetaldehyde $\mathrm { ( C H _ { 3 } { \cdot } C H O ) }$ and carbon dioxide is produced (anyone who has made their own wine by using yeast to ferment the sugar in grape juice will be familiar with the bubbles of $\mathrm { C O } _ { 2 }$ gas given off during the fermentation). The acetaldehyde is then reduced to ethanol by alcohol dehydrogenase, reoxidising the NADH back to $\mathrm { N A D ^ { + } }$ so that glycolysis can proceed. This process has the advantage for yeasts that the ethanol is toxic to many organisms, but yeast can tolerate ethanol in high concentrations, hence their ‘waste product’ inhibits other, competing micro-organisms. When humans ingest ethanol, it is converted back into acetaldehyde by our alcohol dehydrogenase (and the acetaldehyde is probably at least partly responsible for the ‘hangover’ effects of excessive alcohol consumption), and then on to acetate and ultimately acetyl-CoA (Figure 1.15b). Acetyl-CoA can go on to be oxidised by the TCA cycle or used for lipid synthesis (see Section 1.3.3), in other words ethanol provides a large amount of ingested energy. But in addition, metabolism of ethanol reduces large amounts of $\mathrm { N A D ^ { + } }$ to NADH, providing more energy again, but also disrupting the NAD+ :NADH ratio; this has the effect of inhibiting gluconeogenesis (Section 1.3.2.1.5) and causing the hypoglycaemia that is probably the origin of the stimulated appetite commonly seen following alcohol consumption. 

![image](/assets/images/human_metabolism_images/8175cbb6e12e2d75bd378fa20721e393.jpg)



Figure 1.15 Lactate and ethanol metabolism. Glycolysis produces NADH from $\mathsf { N A D } ^ { + } .$ . (a) In aerobic conditions in mammals the ${ \mathsf { N A D } } ^ { + }$ is regenerated by the electron transport chain, but in anaerobic conditions ${ \mathsf { N A D } } ^ { + }$ must be regenerated by lactate dehydrogenase, permitting glycolysis to continue, at the cost of accumulating lactate. (b) In yeast, pyruvate is instead reduced to ethanol in order to regenerate ${ \mathsf { N A D } } ^ { + }$ and allow glycolysis to proceed (brown arrows). When humans ingest alcohol, the ethanol is oxidised to acetyl-CoA via acetaldehyde, providing a large influx of energy but also altering the NAD+ :NADH ratio.


## 1.3.2.1.4 Pyruvate oxidation

Pyruvate can also enter mitochondria where it is a substrate for the enzyme PDH (PDH is actually a complex of three enzymes, sometimes called pyruvate dehydrogenase complex, PDC). PDC not only further oxidises pyruvate, but also removes one carbon, resulting in the formation of (2 carbon) acetyl-CoA which, as described earlier, can be fully oxidised in the TCA cycle. This reaction is essentially irreversible. The importance of this process is illustrated by looking at the energy yield of these pathways: glycolysis yields 2 ATPs by substrate-level phosphorylation, but much energy remains within the pyruvate molecule; full oxidation of pyruvate, via formation of acetyl-CoA and oxidation in the TCA cycle, yields a further 36 ATPs. This number is a theoretical maximum and allowing for some inefficiency the real figure is probably slightly lower than this, but it illustrates how much energy can be derived from oxidation, and hence how important mitochondria (TCA cycle, electron transport chain) are for producing ATP. 

Breakdown of glucose as far as acetyl-CoA can also be part of a synthetic process. Acetyl-CoA produced from glucose is the starting point for the pathways of lipid synthesis: lipogenesis, which usually refers to the synthesis of fatty acids from glucose, and cholesterol synthesis. These pathways, like most biosynthetic pathways, are cytosolic, and the acetyl-CoA must be transferred out of the mitochondria (to be expanded later – Box 5.4). 

## 1.3.2.1.5 Gluconeogenesis

Gluconeogenesis, despite its name (synthesis of new glucose), is a pathway typically active in catabolic states, when there is a need to make glucose from other fuels for organs that depend upon it. The pathway of glucose synthesis, gluconeogenesis, occurs primarily in liver cells (and to a lesser extent, in kidney) and is essentially a reversal of glycolysis (many of whose steps are freely reversible and shared by both pathways) although with some specific steps, circumventing the energy-yielding and largely irreversible steps of glycolysis (Figure 1.14). Reversal of the last step of glycolysis (phosphoenolpyruvate → pyruvate) requires formation of oxaloacetate, and spans the mitochondrion. The main regulatory enzyme of glycolysis, phosphofructokinase, must also be reversed, and for this gluconeogenesis uses fructose-1, 6-bisphosphatase. Finally, if free glucose is to be produced for export (liver), glucose 6-phosphate must be dephosphorylated to glucose by glucose-6- phosphatase – i.e. this is the final enzyme of both gluconeogenesis and glycogenolysis, both pathways allowing liver to export glucose and maintain blood glucose levels. The major substrate for gluconeogenesis is pyruvate; the major source of this under most conditions is lactate. Amino acids whose carbon skeletons can be converted to pyruvate (e.g. alanine, during starvation, discussed later) can also contribute, and in addition glycerol released from lipolysis of triacylglycerols in adipose tissue can enter the gluconeogenic pathway (and hence breakdown of storage lipids does yield a small amount of carbohydrate). Note that glucose is broken down to lactate (glycolysis) in red blood cells, for instance, and in anaerobic cells such as renal medulla: the lactate is transferred via the bloodstream to the liver where it is used to re-synthesise new glucose. This cycle is sometimes called the Cori Cycle (discussed further in Chapter 7). It does not result in irreversible loss of glucose from the body. Irreversible loss of glucose occurs after the action of PDH, as acetyl-CoA can no longer be reconverted to glucose (PDH is irreversible), and therefore acetyl-CoA is not a substrate for glucose synthesis. 

## 1.3.2.1.6 Glycogen metabolism

Carbohydrate is stored in limited amounts as cytoplasmic glycogen granules in most tissues as an energy resource available within the tissue (and hence independent of blood supply) for rapid utilisation when required. Glycogen is a polymer of glucose whose structure was described earlier (Figure 1.8). Glycogen synthesis starts with glucose 6-phosphate (Figure 1.14) and involves sequential polymerisation of glucose units on a glycogenin protein backbone. Glucose units are added as UDP-glucose (derived from glucose 6-phosphate) to the enlarging glycogen molecule by the enzyme glycogen synthase. Glycogen synthase assembles the glucose units into a linear chain, but every 8–10 residues a branch point is introduced by a branching enzyme. This has the effect of producing a highly branched tree-like structure with many free (‘non-reducing’) ends (Figure 1.8). Glycogenolysis involves the reverse: sequential removal of glucose units. These multiple terminal glucose residues enable rapid glucose release during glycogen degradation, by the enzyme (glycogen) phosphorylase (and a debranching enzyme). Glucose 1-phosphate is released, and is converted into glucose 6-phosphate. In most tissues, which store glycogen for their own utilisation (e.g. muscle), the glucose 6-phosphate then enters the pathway of glycolysis for energy production. In the liver specifically (and to some extent in kidney, especially during starvation) the enzyme glucose 6-phosphatase is expressed (uniquely in these tissues) and converts glucose 6-phosphate to free glucose: thus, glucose derived from glycogenolysis or produced by gluconeogenesis may be released into the bloodstream to maintain blood glucose concentrations in the postabsorptive or the fasting state. 

## 1.3.2.1.7 Pentose phosphate pathway

One further pathway of glucose metabolism will be mentioned briefly: the pentose phosphate pathway. Again, this pathway occurs in the cytosol. This involves the metabolism of glucose 6- phosphate through a complex series of reactions that generate pentose sugars, used in nucleic acid synthesis, and also reducing power in the form of NADPH (Figure 1.14). 

The pathway comprises two parts: an oxidative (irreversible) stage, initiated by the enzyme glucose-6-phosphate dehydrogenase, which generates NADPH and the pentose (5-carbon) sugar ribulose 5-phosphate, and then a non-oxidative (reversible) stage which interconverts the pentose sugar into a wide variety of 3 carbon (triose), 4 carbon (tetrose), 5 carbon (pentose), 6 carbon (hexose), and 7 carbon (heptose) sugars. These sugars are used for the synthesis of nucleotides and aromatic amino acids, whilst NADPH provides energy for many reductive biosyntheses – including lipogenesis and amination of 2-oxoacids to amino acids (glutamate dehydrogenase – see below); hence this is a pathway active in anabolic states. NADPH also maintains the antioxidant glutathione in its reduced (active) form (GSH). Because the relative requirements for the two products of the pentose phosphate pathway (pentose sugars and NADPH) varies, when NADPH demand exceeds pentose need, the sugar can be reinserted into glycolysis (hence ‘pentose phosphate shunt’). 

## 1.3.3 Lipid metabolism

## 1.3.3.1 Pathways of lipid metabolism

Carbohydrate metabolism centres on the sugar molecule glucose, its interconversion with the carbohydrate storage form, glycogen, and its breakdown, ultimately by oxidation. Similarly, lipid metabolism concerns the fatty acids as the central carriers of energy, triacylglycerol as the storage form, and pathways for oxidation of fatty acids. (Here we will not discuss other forms of lipid such as cholesterol and phospholipids. Cholesterol was described in Section 1.2.1.1 and Figure 1.6 and will be covered again in later chapters.) There are four central pathways: (i) esterification of fatty acids with glycerol to form triacylglycerol, and (ii) 

the converse, hydrolysis of triacylglycerol to liberate fatty acids and glycerol: lipolysis, (iii) oxidation of fatty acids: β-oxidation, and (iv) synthesis of fatty acids from other precursors, known as de novo lipogenesis. These are shown in simplified form in Figure 1.16, and transport and storage of lipid in the body is represented in Figure 1.17. 

Fatty acids are the lipids utilised for energy production in oxidative tissues; however, since they are amphipathic and detergent-like (Figure  1.4) they are potentially toxic, and are stored as triacylglycerol, mainly in specialised cells known as adipocytes. Unlike carbohydrates such as glucose, lipids are (by definition) not water-soluble. As discussed in Figure 1.4, triacylglycerol is very hydrophobic, making it a very dense and efficient energy store. Whilst this is an advantage for energy storage, it necessitates specialised forms of intracellular storage and mechanisms for transport through the plasma. 

Triacylglycerol within cells is stored in the form of lipid droplets, discrete droplets each bounded  –  and stabilised  –  by a monolayer of phospholipids, together with some specific proteins (described in more detail later, Box 5.7). This phospholipid coat is similar to the structure of a cell membrane shown in Figure 1.5, but with just the outer layer of phospholipids. In specialised cells for fat storage, adipocytes, there may be just one large lipid droplet, occupying much of the volume of the cell (and discussed in more detail in Chapter 5), but in most cells there are multiple, small lipid droplets. 

Plasma fatty acids themselves, not esterified to glycerol, are known as NEFAs, sometimes called free fatty acids (FFAs). In plasma they are mainly bound loosely and non-specifically to the plasma protein albumin. They dissociate from albumin to enter cells. Triacylglycerol is also transported in plasma, usually along with cholesterol. This is 

![image](/assets/images/human_metabolism_images/130e34bbd59cb682e53f5004be421242.jpg)



Figure 1.16 Pathways of lipid metabolism in the cell. Synthesis of fatty acids from acetyl-CoA (lipogenesis) is driven by NADPH (from the pentose phosphate pathway), whilst the opposite pathway, breakdown of fatty acids to form acetyl-CoA (β-oxidation) also produces NADH (and FADH ). Esterification of fatty acids to glycerol produces triacylglycerols; the glycerol is released when the triacylglycerol undergoes lipolysis. Hence triacylglycerols are ‘storage’ forms of acetyl-CoA. Acetyl-CoA can be transported in the form of ketone bodies.


![image](/assets/images/human_metabolism_images/0d6ffe94aab5cb824b0e76f0d5589c84.jpg)



Figure 1.17 Lipid metabolism pathways. Importance of lipolysis and esterification pathways in lipid metabolism. Dietary fat, in the form of triacylglycerol, is hydrolysed in the intestinal lumen by pancreatic lipase and the products taken up into enterocytes (more detail in Section 4.2.3.2.3). Within the enterocytes, the fatty acids are re-esterified to glycerol [in fact some are taken up as monoacylglycerols and this is the basis for esterification – see Section 4.3.3]. The triacylglycerol is exported into plasma in the form of large lipoprotein droplets, the chylomicrons. Lipolysis of this circulating triacylglycerol by a lipase bound to endothelial cells (lipoprotein lipase) allows fatty acids to be taken up into cells for further esterification (adipose tissue) or for oxidation (muscle and other tissues). Triacylglycerol stored in adipocytes may be hydrolysed by intracellular lipases (further details in Chapter 5, Figure 5.10) to release fatty acids, which can travel through plasma for delivery to other tissues for oxidation. Most tissues also contain smaller amounts of triacylglycerol, formed by esterification of incoming fatty acids. Lip, lipolysis step; Est, esterification step. Structures are shown very diagrammatically. Fatty acids are represented by short wavy lines (more detail in box) but see Figures 1.4 and 1.9 for more detail.


achieved by formation of sub-microscopic lipid droplets in which a core of triacylglycerol is stabilised in the aqueous environment of the plasma by a surface monolayer of phospholipids, like intracellular lipid droplets. These droplets, or particles as they are often known, are associated with specific proteins to guide them round the circulation. The whole particle is then known as a lipoprotein. Lipoprotein metabolism will be discussed extensively in Chapter 10. Here we will briefly mention two relevant classes of lipoprotein particles: the chylomicrons and the very-low-density lipoproteins (VLDLs)  –  the reasons for these names will be explained in Chapter 10. 

The reactions involved in interconversion of fatty acids and triacylglycerol are central to lipid metabolism. As shown in Figure 1.4, triacylglycerols consist of three fatty acid molecules esterified to one of glycerol (a trihydric alcohol, CH OH-CHOH-CH OH). These ester bonds are hydrolysed by lipase enzymes. There are several families of lipases, which will be mentioned where relevant in the text. The reaction is identical to that used in the manufacture of soap, known as saponification. In soap manufacture, a triacylglycerol (usually of vegetable oil origin) is treated with caustic soda (NaOH), resulting in the hydrolysis of ester bonds and the liberation of glycerol and fatty acids (in the form of their sodium salts). In metabolism, however, the hydrolysis is achieved by lipase enzymes (Figure 1.18). 

![image](/assets/images/human_metabolism_images/ed7309780644334799fb9a1c5635ac67.jpg)



Triacylglycerol


![image](/assets/images/human_metabolism_images/745fa85c3fd8c422c73cb8e3165ce4fc.jpg)


![image](/assets/images/human_metabolism_images/c559e42f25dd6daf3f8358b04bc76db4.jpg)



(Non-esterified) fatty acids


![image](/assets/images/human_metabolism_images/92797f0af242386649cbd6d20e420729.jpg)


![image](/assets/images/human_metabolism_images/0d2275da929576d64c509ccb5a57087a.jpg)


![image](/assets/images/human_metabolism_images/6073cc8c0b6c2c2699a7b97c27b87da7.jpg)



Figure 1.18 Parallel between soap manufacture (saponification) and fat mobilisation. In saponification, an alkali (usually NaOH) is used to hydrolyse a source of triacylglycerol – animal fat or a vegetable oil. The resultant sodium salts of fatty acids (together with glycerol) constitute soap. The hydrolysis of triacylglycerol stored in adipocytes is similar, but brought about by enzymes (more details in Chapter 5, Figure 5.10), and releases non-esterified fatty acids (NEFA) that may be used as a fuel in other tissues. However, in metabolism, unlike in soap manufacture, the process is reversible: fatty acids can also be re-esterified with glycerol to make new triacylglycerols (pathways are given in Chapter 4, Figure 4.8). This is the basis of the pathway by which triacylglycerol is laid down in adipocytes.


Unlike the relationship between vegetable oils and soap, however, in metabolism the process can be reversed: fatty acids can be re-esterified with glycerol to make new triacylglycerol. (The reaction usually uses glycerol 3-phosphate and will be described further in Chapter 5.) The fatty acids are added in the form of their coenzyme A esters, known as fatty acyl-CoA (i.e. fatty acid-CoA). (Note that fatty acyl-CoA is different from acetyl-CoA, although acetyl-CoA could be considered the simplest of the family of acyl-CoAs.) 

## 1.3.3.2 Fat deposition and mobilisation

Most dietary fat is in the form of triacylglycerol (Table 4.1). Within the small intestine, dietary triacylglycerol molecules are hydrolysed by intestinal lipases and the products are absorbed into the cells lining the intestines (mucosal or epithelial cells, collectively known as enterocytes). The products of lipolysis are recombined with the enterocytes to form new triacylglycerol. These triacylglycerols, composed of dietary fat, are liberated into the circulation as lipoprotein particles: in fact, the largest and most fat-enriched of the lipoprotein particles, known as chylomicrons (more detail in Chapters 4 and 10). At target tissues, the triacylglycerol in the lipoprotein particles is hydrolysed by a lipase bound to the endothelial cells lining the capillaries, known as lipoprotein lipase. The resulting fatty acids are taken up by cells, and have two potential fates: (i) re-esterification with glycerol 3-phosphate to make new triacylglycerol (and other lipids) – the pathway of fat deposition; or (ii) oxidation. The former is the major route by which dietary fat is laid down for storage in adipose tissue (Figure 1.17; Section 5.2.2.1). 

When the stored fat is required as a source of energy, for instance during physical activity when muscles will oxidise fatty acids, or during periods between meals, then the stored triacylglycerol is hydrolysed by a series of intracellular lipases to liberate fatty acids and glycerol, which can be released into the plasma. This is the process known as $f a t$ mobilisation. As noted earlier, these non-esterified (‘free’) fatty acids are transported bound to albumin. Glycerol, which is freely soluble, will travel mainly to the liver where it is a substrate for gluconeogenesis as described above (Section 1.3.2.1.5). On average, in a mature adult who is weightstable, the amount of fat stored in a typical day will equal the amount mobilised. Most tissues can utilise NEFAs, but importantly fatty acids cannot cross the blood-brain barrier and therefore cannot be used as an energy source by the central nervous system. Also, their oxidation requires mitochondria, meaning that red blood cells (erythrocytes), which lack mitochondria, are unable to use them. However, fatty acids are a major fuel source for muscle and kidney, and for the heart and liver under certain conditions. 

## 1.3.3.3 Fatty acid oxidation

Following uptake into cells, fatty acids are rapidly ‘activated’ by esterification to CoA, forming fatty acyl-CoA; this esterification (known as thioesterification because of the –SH thio group of the CoA molecule) also removes the amphipathic, detergent-like character of the fatty acid, making it less toxic in the membrane-rich cytosol. This reaction requires ATP and releases inorganic pyrophosphate, PP . $\mathrm { P P _ { i } }$ is rapidly broken down to $\mathrm { { P _ { i } , } }$ meaning that this step is essentially irreversible. It therefore achieves the same end as glucose phosphorylation to glucose 6-phosphate on entering a cell: it both traps the fatty acid within the cell, and creates a concentration gradient to draw more fatty acids into the cell. The enzymes concerned are known as acyl-CoA synthases (ACSs): again there is a family of these, suited for fatty acids of different carbon chain lengths. The action of the ACSs may be intimately linked to the process of fatty acid transport into the cell, discussed further in Chapter 2. 

The fatty acyl moiety may then undergo $\beta -$ oxidation to yield acetyl-CoA (together with 

NADH and FADH ) for further oxidation and ATP formation (Figure 1.16 and Box 1.7). This process occurs in mitochondria (hence cells lacking this organelle, such as red blood cells, are unable to derive energy from fatty acids because they cannot oxidise substrates). However, in order to get inside the mitochondria, the fatty acyl-CoA must cross the IMM on the carnitine shuttle (Box 1.7), and it is the activity of the carnitine shuttle that regulates the rate of supply of fatty acids to the mitochondria, and hence of the rate of β-oxidation. 

Although most β-oxidation occurs in mitochondria, some fatty acid oxidation also takes place in organelles called peroxisomes. Peroxisomes seem to be particularly responsible for oxidation of fatty acids of relatively unusual (or at least, relatively rare) structure, especially very long chain fatty acids (22 or more carbons) and branched chain fatty acids, such as phytanic acid. Peroxisomal β-oxidation of very long chain fatty acids produces medium chain fatty acids which can then be further oxidised in mitochondria (at least in humans), but also produces hydrogen peroxide $\left( \mathrm { H } _ { 2 } \mathrm { O } _ { 2 } \right)$ , a reactive oxygen species which must be reduced. Very long- and branched chain fatty acids can only be metabolised in peroxisomes: congenital lack of peroxisomes, such as occurs in Zellweger syndrome and infantile Refsum’s disease, is associated with inability to oxidise these fatty acids and consequent hepatic and neurological dysfunction. 

Whilst the above pathway predominates in muscle, supplying large amounts of ATP for biological work such as contraction, in liver acetyl-CoA derived from fatty acid β-oxidation is also used for ketone body synthesis (ketogenesis). Ketone bodies (acetoacetate, 3-hydroxybutyrate) are 4-carbon compounds and represent a soluble transport form of acetyl-CoA (effectively two acetyl-CoA's joined together). This will be discussed further in Chapter 5. Acetoacetate undergoes spontaneous decarboxylation to the 3-carbon acetone: acetone probably has no physiological function in humans but is volatile and excreted in the breath with a characteristic sweet-smelling odour. (There is some evidence that acetone is converted into methylglyoxal and 1,2-propanediol, which can both act as gluconeogenic substrates, hence this is another [but also quantitatively minor] mechanism for converting lipids into 

## Box 1.7 Fatty acid oxidation

Once a fatty acid enters the cell it is rapidly joined to Coenzyme A (CoASH) to form fatty acyl-CoA, by the enzyme ACS – it has been suggested that it may be linked with fatty acid transport into the cell so that the intracellular concentration of free fatty acids is kept very low. The fatty acyl-CoA may undergo esterification to triacylglycerol (for example, in adipose tissue) or it may be oxidised for energy release, by β-oxidation in the mitochondrion. However, long chain fatty acyl-CoA cannot cross the highly selective inner mitochondrial membrane (IMM), therefore the fatty acid is transported across on the carnitine shuttle. Carnitine is a highly charged molecule $( ( \mathsf { C H } _ { 3 } ) _ { 3 } \mathsf { N } ^ { + } \mathsf { C H } _ { 2 } \mathsf { C H } ( \mathsf { O H } )$ ${ \mathsf { C H } } _ { 2 } { \mathsf { C O O } } ^ { - }$ ) and there is a specific translocase for it to move (with and without esterified acyl group) across the mitochondrial membranes. The carnitine shuttle is initiated by carnitine palmitoyl transferase-1 (CPT-1) on the outer mitochondrial membrane (OMM), which transfers the fatty acyl group from CoA to carnitine. This compound can cross the IMM in association with a translocase before being reconverted to fatty acyl-CoA by carnitine palmitoyl transferase-2 (CPT-2). CPT-1 is strongly inhibited by malonyl-CoA, the first intermediate of the ‘opposite’ pathway – lipogenesis – hence a reciprocal regulatory mechanism prevents fatty acid degradation (oxidation) and synthesis from occurring simultaneously, which would represent an inefficient futile cycle. 

![image](/assets/images/human_metabolism_images/9fbfc71011686486cca8b746bc8b4429.jpg)


## Box 1.7 Fatty acid oxidation (continued)

The fatty acyl-CoA that results in the mitochondrial matrix now undergoes β-oxidation. β-oxidation is so called because the β-carbon (second methyl carbon) of the FA chain is attacked, in a reaction sequence involving oxidation, hydration and thiolysis, releasing the 2-carbon acetyl group, again attached to $\mathtt { C o A }$ , all within mitochondria. The process is cyclically repeated until the entire FA chain has been broken down to acetyl-CoA 2 carbon units. β-oxidation occurs by a multienzyme trifunctional protein complex which catalyses an oxidative cycle generating acetyl-CoA, NADH and $\mathsf { F A D H } _ { 2 } .$ . The acetyl-CoA undergoes further oxidation to ${ \mathsf { C O } } _ { 2 }$ in the TCA cycle (also within the mitochondrial matrix), whilst the NADH and $\mathsf { F A D H } _ { 2 }$ (that derived both from oxidation of the acetyl-CoA by the TCA cycle and also that derived from β-oxidation itself) are then re-oxidised by the electron transport chain, yielding ATP. Each cycle of β-oxidation produces a theoretical maximum of 17 ATPs (though due to some inherent inefficiencies including some proton ‘leak’ across the IMM, in practice ∼14 ATP) – hence palmitate (16 carbons → 8 acetyl-CoA) yields a theoretical maximum of 106 ATP. Odd number carbon fatty acids (which are relatively rare) produce the 3-carbon propionyl-CoA in their final β-oxidation cycle; this can go on to produce succinyl-CoA, an intermediate of the TCA cycle, and hence an anaplerotic substrate – an example of lipids potentially producing carbohydrates, though limited by the relative rarity of these fatty acids. 

carbohydrates.) Since brain cannot utilise fatty acids, the liver converts NEFAs to ketone bodies, which are exported to the brain (and other oxidative tissues such as muscle) where they are readily converted back into acetyl-CoA for oxidation in the TCA cycle and ATP production. Ketone bodies therefore constitute a major glucose-sparing fuel. Ketogenesis occurs exclusively in the liver; however, liver lacks the pathway for ketone body utilisation (ketolysis), preventing intracellular substrate cycling. 

## 1.3.3.4 Fatty acid synthesis

The body may acquire fatty acids either from dietary fats, or it may synthesise them de novo from dietary non-lipid sources (lipogenesis). Acetyl-CoA derived from excess carbohydrates and amino acids surplus to current energy requirements is assembled into long chain fatty acids in the cytosol of lipogenic tissues such as liver and adipose tissue (and then esterified to form triacylglycerol) for energy storage. The initiating (first committed) step involves generation of malonyl-CoA (the first committed intermediate of lipogenesis, and unique to this pathway) from acetyl-CoA and bicarbonate $\mathrm { ( H C O } _ { 3 } ^ { - } \mathrm { ) }$ by acetyl-CoA carboxylase, and is highly regulated. The malonyl group is the donor for fatty acid synthase, a multi-catalytic polypeptide which elongates the growing fatty acid chain by 2 carbons in a repeated cycle using NADPH for energy. The fatty acid chain formed can undergo several modifications, including desaturation. The commonest fatty acids in human metabolism are palmitic (16 carbons, saturated) and oleic (18 carbons, one unsaturated bond). (This is explored further in Chapter 5, see Box 5.4.) Lipogenesis is the opposite pathway to β-oxidation, but although the chemical processes are opposite (β-oxidation: hydration, oxidation; lipogenesis: dehydration, reduction), the pathways do not utilise the same enzymes. Furthermore, lipogenesis occurs in the cytosol, whilst β-oxidation occurs in the mitochondrion, an example of intracellular compartmentation preventing substrate (futile) cycling of two opposing pathways. 

The mature fatty acid is activated with CoA, forming fatty acyl-CoA, the starting point for further metabolism, by ACS (one of a family of enzymes acting on different chain length fatty acids). The primary end-point of mammalian fatty acid synthesis is palmitic acid (see Box 1.3), a 16-carbon saturated fatty acid (16:0 using the nomenclature of Box 1.3). For most cellular functions, a wide range of fatty acids is required (e.g. phospholipids formed entirely of saturated fatty acids would form very rigid membranes). Lipogenic tissues therefore also express elongase enzymes (there is a family of these: they use acetyl-CoA to add 2 carbons at a time to the carboxyl end of a fatty acid), and desaturases, which can remove hydrogen to form double-bonds. Thus, for instance, palmitic acid (16:0) can be converted to palmitoleic acid (16:1 n-7), stearic acid (18:0) and oleic acid (18:1 n-9). More details will be given later (Box 5.4). 

Although the pathway of de novo lipogenesis, primarily the synthesis of fatty acids from glucose, is expressed and undoubtedly operates in human cells (adipocytes and liver; Chapter 5), it contributes only a small proportion of the fat stored in adipose tissue under most conditions – this will be discussed further in Chapter 7 (Box 7.2). 

## 1.3.4 Protein metabolism

## 1.3.4.1 Pathways of amino acid metabolism

Amino acids may be synthesised, obtained from the diet or derived from proteolysis (although no dedicated protein exists whose sole function is simply to supply amino acids for energy). ‘Nonessential’ amino acids can be synthesised from intermediary metabolites (or from other amino acids); ‘essential’ amino acids cannot be synthesised by humans and therefore must be obtained from the diet. ‘Conditionally essential’ amino acids can be synthesised in only limited amounts, and this must be supplemented by the diet in states of rapid protein synthesis (e.g. growth). Free amino acids constitute a soluble amino acid substrate pool; this is quantitatively small, but dynamic, turning over rapidly. From this pool, amino acids are used for biosynthetic functions as well as degradation for energy production, their carbon skeletons entering the common metabolic pool of intermediary metabolites shared with carbohydrate and lipid metabolism. Dietary amino acids surplus to synthetic requirements (for proteins, nucleotides, hormones, neurotransmitters, creatine, porphyrins etc.) are utilised directly for energy production. Some tissues (e.g. liver, intestine, leukocytes) preferentially oxidise amino acids for energy. Amino acids contain approximately the same energy as carbohydrates – about half that of lipids. Amino acids may be used to provide metabolic energy either (i) in the well-fed state, when amino acid intake exceeds protein synthesis requirement, in which case excess exogenous amino acids are oxidised or stored as non-protein energy reserve, or (ii) in starvation, when endogenous amino acids derived from ‘dispensable’ protein are oxidised for energy. 

Whilst amino acids are used to synthesise proteins, most proteins are not inert but are constantly broken down (proteolysis) to amino acids and re-synthesised (protein synthesis), this constituting the protein turnover rate: this cycling varies between individual proteins. For a protein to be useful as a source of amino acids for energy production, its turnover rate must be relatively high, and there must be a relatively large amount of it in the body (and it must be, at least in part, expendable). The rate of protein turnover depends on the individual protein – generally, gastrointestinal and hepatic proteins turn over rapidly (5–15% per day) whilst skeletal muscle contractile protein turnover is relatively slow (∼2% per day) (see Chapter 7 for more detail); however, because of the large mass of skeletal muscle, and the ability to maintain viability despite loss of >50% of actin and myosin, this depot makes the largest contribution to whole body protein turnover, and hence amino acid availability for metabolism and energy release. 

Typical dietary protein intake is ${ \sim } 1 0 0 \ g \ \mathrm { d ^ { - 1 } }$ (with the same amount excreted as nitrogenequivalent), whilst the ∼10 kg of body protein is turned over to ∼100  g of free amino acids at a turnover rate of ${ \sim } 3 0 0 \dot { \mathrm { ~ g ~ d ~ } ^ { - 1 } }$ . Dietary proteins are digested in the small intestine and absorbed as free amino acids and short peptides (see Chapter 4, Section 4.3.2). Enterocytes of the small intestine remove some amino acids, especially glutamine, for use as an oxidative fuel (see Chapter 5.8). The remaining products of digestion enter the portal vein and then the liver, where further preferential amino acid extraction occurs (most are extracted by the liver). Amino acid oxidation is, under most circumstances, the major oxidative pathway in the liver – about 60% of incoming amino acids may be directed into immediate oxidation. The rate of hepatic protein synthesis is also high, and since much of the protein is secreted (e.g. albumin), this represents a net loss of amino acids from the liver (perhaps a further 20% of the incoming amino acids). The remaining mixture of amino acids, around 20% of those absorbed, enters the systemic circulation. This mixture is enriched in branched chain amino acids (leucine, isoleucine, and valine), which have a special role in muscle (see Chapter 5.3.3.3). Branched chain amino acids make up approximately one third of all amino acids in the body; whilst the other amino acids are metabolised principally in the liver, these essential amino acids are metabolised in peripheral (non-hepatic) tissue, especially skeletal muscle. 

Although multiple amino acids exist in vivo, and individual amino acid metabolic pathways exist, most follow a common biochemical strategy to yield their energy. Amino acids contain C, H, O atoms, like carbohydrates and lipids, but also a distinguishing N atom in the amino group (see Section 1.2.2.3 and Figure 1.11). Therefore the essential feature of amino acid metabolism is removal of the amino-N group (deamination). Deamination of amino acids produces ammonia (NH ) and the ‘carbon skeleton.’ Ammonia is highly toxic and must either be excreted directly into the urine (kidney) or converted into relatively non-toxic urea in the urea (ornithine) cycle (liver) (or, occasionally, incorporated into some other biomolecules), followed by utilisation of the remaining carbon skeleton (2-oxoacid; α-ketoacid) (Figure 1.19). The fate of the 2-oxoacid carbon skeleton depends on where it enters the common metabolic pool of intermediary metabolism. 

## 1.3.4.2 Amino acid-nitrogen disposal

Deamination of amino acids is achieved by two types of reaction which function in a complementary manner. The first is transamination, in which the amino group from one amino acid is transferred to another 2-oxoacid (carbon skeleton), forming its corresponding amino acid (i.e. amino acid-1 + 2-oxoacid-2 ↔ 2-oxoacid-1 + a mino acid-2). The enzymes responsible for transamination reactions are aminotransferases (transaminases), all of which contain pyridoxal 

![image](/assets/images/human_metabolism_images/0d5e441ab2eaa11fe674b10f9630bc8b.jpg)



Figure 1.19 Metabolism of amino acids. To be metabolised, amino acids must first be deaminated to remove the nitrogen (amino group) from the central α carbon. This leaves the carbon skeleton (the corresponding 2-oxoacid [α-ketoacid]) which undergoes metabolism in the common metabolic pool, by a route which depends on its structure, ultimately producing energy. The amino group becomes ammonia, some of which can be excreted directly in the urine, but most of which must be detoxified by the urea cycle.


![image](/assets/images/human_metabolism_images/d7c0a2e456bf914544054b6bdf276ca9.jpg)



Figure 1.20 Transamination reactions. Transamination involves the transfer of an amino group from the α-carbon of an amino acid to a recipient 2-oxoacid (α-ketoacid), forming its corresponding 2-oxoacid and generating an amino acid. These reactions are catalysed by aminotransferase enzymes, all of which are readily reversible. Although no net deamination occurs, these reactions allow the amino groups of all amino acids to be ‘funnelled’ into key amino acids prior to net deamination and hence metabolism.


phosphate, a derivative of vitamin B6, in their active centres (Figure 1.20). Aminotransferases are widespread in most tissues and are near-equilibrium, and hence readily reversible. Each is specific for a limited number of amino acids, but most utilise 2-oxoglutarate (also called α-ketoglutarate) as the amino (N) acceptor (the ‘2-oxoacid-2’ in Figure 1.20), producing the carbon backbone of the donor amino acid together with glutamate (amino acid  +  2-oxoglutarate  → 2-oxoacid  +  glutamate). Hence 2-oxoglutarate and glutamate are central to amino acid catabolism as these reactions ‘funnel’ the various amino acids into glutamate (and note that 2-oxoglutarate is common to the TCA cycle, and its utilisation by this pathway depletes TCA cycle intermediates  –  cataplerosis). Alanine aminotransferase (ALT) transfers the amino group of alanine to 2-oxoglutarate, forming pyruvate and glutamate. The pyruvate can be used for gluconeogenesis (see below), e.g. during starvation. Alanine is a key transport form of amino acid carbon and nitrogen, hence this enzyme is important for inter-tissue amino acid flux. Aspartate aminotransferase (AST) transfers the amino group of aspartate to 2-oxoglutarate, forming oxaloacetate and glutamate  –  however, this enzyme usually works in the reverse direction, its function being to convert glutamate (derived from amino acid funnelling, above) into aspartate, which is required to donate a second urea N-atom to the urea cycle. Since ALT and AST are both intracellular enzymes and widespread, necrosis of many tissues, including liver, causes them to increase in plasma; they are commonly used to diagnose hepatocellular damage (so-called ‘liver function tests’). 

The second type of reaction responsible for amino acid deamination is oxidative deamination. Since most amino acids have been funnelled (deaminated) into glutamate by transamination, glutamate is the only amino acid that undergoes direct, oxidative, deamination, by glutamate dehydrogenase, regenerating 2-oxoglutarate and producing ammonia (NH ). Unusually for a highly regulated enzyme, glutamate dehydrogenase is reversible, and can use NAD+ /NADH or NADP+ /NADPH as electron carriers. In the ‘forward’ direction of deamination (catabolic, amino acid breakdown), it uses NAD+ , but in the ‘reverse’ direction of amination of 2-oxoglutarate to glutamate (anabolic, amino acid synthesis) it uses NADPH, reflecting the different roles of these cofactors as redox energy carriers in different metabolic states (Box 1.8; for simplicity, ionisation states are not always shown as they would be at physiological pH; ammonium ion shown here [NH + ] may be considered the same as ammonia). Hence, aminotransferases (transamination) and glutamate dehydrogenase (oxidative deamination) work together to produce ammonia for detoxification to urea in the urea cycle, and carbon skeletons for further intermediary metabolism (Figure 1.21). 

![image](/assets/images/human_metabolism_images/2ee843ebf38034e28eb6b1bfe0a8e968.jpg)



Figure 1.21 Deamination of amino acids. By linking transamination reactions to oxidative deamination, and then to the urea cycle, all amino acids can be efficiently deaminated, their carbon backbones (2-oxoacids) going on to further metabolism for energy production, and the amino group being safely detoxified by the urea cycle.


The urea (ornithine) cycle occurs in the liver. Urea $\mathrm { ( C O . ( N H _ { 2 } ) _ { 2 } ) }$ contains two nitrogen atoms: one derives from ammonia (oxidative deamination of glutamate), the other from aspartate (transamination, also of glutamate, by AST) (Figure 1.21): the body excretes nitrogen with minimal carbon (and energy) loss. Because urea is very water-soluble, much nitrogen waste can be excreted for relatively little water loss, an important adaptation in terrestrial animals. Urea lacks toxicity at physiological concentrations; it is (neuro)toxic only in extremely high concentrations, for example those seen in untreated renal failure, but considerably less so than ammonia. 

The urea cycle starts by forming carbamoyl phosphate from ammonia by the enzyme carbamoyl phosphate synthase (Figure 1.22). This is the regulated step of the urea cycle, but since ammonia is so toxic, the entire urea cycle must have a high capacity in order to deal with any sudden influx of ammonia-nitrogen if amino acid deamination is acutely increased. This may occur for example in starvation, when endogenous protein is broken down to yield amino acids for deamination and gluconeogenesis, or following consumption of large amounts of protein in the diet (protein cannot be stored as such and therefore the excess amino acids ingested are converted to more efficient energy storage forms [lipid], again following deamination). The carbamoyl phosphate transfers the nitrogen to ornithine, one of a series of amino acid intermediates found in the urea cycle but not used in protein synthesis. The second 

## Box 1.8 Deamination

•	 transamination is a type of deamination but does not remove net N 

•	 presence of α-amino group prevents oxidative breakdown 

•	 therefore α-amino group must be removed before catabolism can proceed 

•	 the nitrogen can be incorporated into other compounds or excreted in the urine 

•	 different types of deamination but oxidative deamination is quantitatively the most important 

![image](/assets/images/human_metabolism_images/cef69b0164a4e8085cb81bd975df190f.jpg)


•	 oxidative 

•	 non-oxidative 

•	 hydrolytic 

glutamate dehydrogenase 

serine & threonine: hydroxyl in side chain 

asparagine & glutamine: N in side chain 

•	 glutamate is the only amino acid that undergoes oxidative deamination (glutamate dehydrogenase) 

![image](/assets/images/human_metabolism_images/0ffe552f5d85bda40af4318c35df5b33.jpg)


•	 mostly occurs in liver and kidney 

•	 unusually can use either ${ \mathsf { N A D } } ^ { + }$ or NADP+ as coenzyme 

• ${ \mathsf { N A D } } ^ { + }$ used mostly in oxidative deamination 

• ${ \mathsf { N A D P } } ^ { + }$ used mostly in reductive amination 

•	 direction of reaction depends on substrate availability (& hence metabolic state) 

•	 allosteric regulation (unusually for a readily reversible reaction): 

![image](/assets/images/human_metabolism_images/a94251c8b14e528a0d3c72705df9df91.jpg)


![image](/assets/images/human_metabolism_images/3d63fb7618eaa01b86c38fd8e8facc48.jpg)



Figure 1.22 Urea cycle. One nitrogen atom enters the cycle as an ammonium ion from glutamate dehydrogenase, whilst another enters from the amino acid aspartate, itself derived principally from glutamate via a transamination reaction. Hence the urea molecule contains two nitrogen atoms for only one carbon atom. The entire cycle is found only in liver, but sections of the cycle are present in other tissues, notably the intestine and kidney.


nitrogen in the urea molecule is introduced by aspartate from aspartate transaminase (see above). Of note, the urea cycle spans both cytosolic and mitochondrial compartments of the liver cell, as well as being partially present in other tissues (intestine, kidney) – possibly a mechanism to ensure that ornithine is not limiting and always available to accept carbamoyl phosphate (and hence ammonia, which cannot be allowed to accumulate). 

Besides urea formation, another route of nitrogen-ammonia excretion exists. In peripheral tissues (e.g. muscle) ammonia may be formed by the oxidative deamination of glutamate (by glutamate dehydrogenase, Box 1.8). This reaction, in combination with the aminotransferases, can be seen to capture amino nitrogen from a number of amino acids. However, blood ammonia concentrations are very low (it is highly toxic) and instead it is exported by being fixed in the amido (side chain) group of glutamine by the enzyme glutamine synthase: hence glutamine is ‘safely’ carrying two nitrogen atoms. In liver, the enzyme glutaminase removes the amido nitrogen of glutamine as ammonia for rapid incorporation into urea (an example of hydrolytic deamination: see Box 1.8). In kidney, glutaminase also removes the amido group of glutamine to form ammonia (and glutamate; glutamate dehydrogenase then deaminates this to form a second ammonia molecule), but here in the kidney the resulting ammonia is excreted directly into the urine where is acts as a urinary buffer (this means that the urine can be buffered without carbon loss). There is also a supply of ammonia from the small intestine (see Chapter 5, Section 5.8). These relationships are discussed further in Chapter 7 (Section 7.4). 

![image](/assets/images/human_metabolism_images/213cafc6b4745a66cb4260aa5d403a60.jpg)



Figure 1.23 Metabolism of the carbon skeletons of amino acids following their deamination. Following deamination, the remaining 2-oxoacid (carbon skeleton) enters intermediary metabolism in one of only seven sites. Glucogenic amino acids are shown in blue, ketogenic amino acids in green.


## 1.3.4.3 Metabolism of the carbon skeleton

Following deamination, the remaining carbon skeleton enters the common metabolic pool; its fate depends on where it enters this pool of intermediary metabolites. All amino acid carbon skeletons ultimately yield just seven products of intermediary metabolism: pyruvate, 2-oxoglutarate (α-ketoglutarate), succinyl-CoA, fumarate, oxaloacetate, acetyl-CoA and acetoacetyl-CoA. The first five of these represent ≥ 3 carbons, hence amino acids producing these metabolites can be used for glucose synthesis (‘glucogenic’): it is this property that confers on proteins the ability to act as a carbohydrate reserve. The acetyl-CoA and acetoacetyl-CoA, however, yield two (or the equivalent to two) carbons, and amino acids which produce them cannot be used for gluconeogenesis (since PDH cannot be reversed (see Section 1.3.1.3 above) – they can only be oxidised directly in the TCA cycle, undergo lipogenesis or be used to synthesise ketone bodies (‘ketogenic’). This is illustrated in Figure 1.23). 

## Supplementary resources

Supplementary resources related to this chapter, including further reading and multiple choice questions, can be found on the companion website at www.wiley.com/go/frayn. 

![END](/assets/config_images/end.jpg)
