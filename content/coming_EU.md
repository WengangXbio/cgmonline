---
title: "欧洲区预告"
date: "2022-02-18"
menu: [top]
weight: 4
---

- 题目：AnchorWave:一个为解决植物基因组比对痛点而开发的软件
- 时间：欧洲中部时间 2022 年 2 月 18 号（星期四）02 PM（美国中部时间 2 月 18 号 7AM，北京时间 2 月 18 号 09PM）
- Zoom会议 ID：861 0146 4725 密码：269044 
- Zoom会议链接：https://us06web.zoom.us/j/86101464725?pwd=bXphV2NYdGRZeVRaZys0WnNjczF4Zz09
- 主讲人：2006.09-2010.07	郑州大学 生物工程系 学士; 2010.09-2013.07	西北农林科技大学 动物医学院 硕士; 2014.02-2018.11	德国 马克思普朗克植物育种研究所 博士; 2018.12 – 至今    美国 康奈尔大学 Edward S. Buckler课题组 博士后

<div align="center">
<img src="https://i.ibb.co/gMxxf3R/ad.jpg" height=250>
</div>

# 中文摘要

CGM欧洲区新一期（CGM-EU24），我们非常荣幸地邀请到了美国康奈尔大学的宋宝兴博士。针对目前对具有长插入缺失、高度多样化序列等特征的复杂基因组，普遍使用的局部比对策略没有达到对简单基因组的效果。因此，宋宝兴博士开发了AnchorWave，AnchorWave软件使用蛋白编码基因等保守序列作为锚定位点，设计了最长路径算法分析两个基因组的共线性区域。本期我们欢迎宋宝兴博士来给大家讲述他们如何开发AnchorWave软件以及AnchorWave软件的具体应用。

植物基因组尤其是农作物基因组有很多不同于动物基因组的特点，然而现有的基因组比对工具大多是针对人类和黑猩猩的基因组比对进行的优化和测试。虽然这些工具也能应用于拟南芥等较小的模式植物基因组，但是应用到较大植物基因组时，往往比对结果和其它生物学研究结果相差甚远。很多农作物和野生近源物种之间存在全基因组复制差异，并且全基因组复制后往往会发生重新排列组合。使用多对多或一对一的策略产生的序列比对结果和进化背景不相符。植物功能元件的核心motif平均仅有6-7bp，远远短于k-mer/seed的长度，这部分较保守的序列往往不能被比对。转座子和其它重复序列造成大量假阳性或假阴性比对结果。植物基因组中十分活跃的转座子插入和缺失并不能够被比对成完整的indel。为解决这些农作物基因组的比对难题，我们开发了AnchorWave。AnchorWave使用蛋白编码基因等保守序列作为锚定位点，设计了最长路径算法分析两个基因组的共线性区域。我们使用目前最快的全局序列比对算法WFA设计了一个2-piece affine gap cost的比对策略，并通过WFA对每个锚定位点区和锚定位点间区进行单碱基分辨率的序列比对，进而获得每个共线性区域的序列比对和全基因组水平的序列比对。通过比对两个较小的十分相似的基因组，两个较长的具有很高的转座子活性的基因组，两个序列差异大、有全基因组复制差异的基因组等对AnchorWave和现有的工具进行比较，我们发现AnchorWave比目前最优的基因组比对软件更优或相当。使用AnchorWave比对B73和Mo17两个玉米基因组，可以把基因组的比对率从60-70%提高到99%。AnchorWave能将大约87%已报道的转座子差异位点比对成完整的单个插入或缺失，而目前常用的基因组比对工具的转座子差异位点召回率（recall）为０。通过比对高粱和玉米基因组、大豆和其野生物种基因组、番茄和马铃薯基因组显示AnchorWave能产生符合全基因复制进化预期的序列比对深度。显著提高调控序列区域的比对率，并降低转座子区域的假阳性。



# 参考文献
1. Baoxing Song#, Santiago Marco-Sola, Miquel Moreto, Lynn Johnson, Edward S. Buckler#, Michelle C. Stitzer#. AnchorWave: sensitive alignment of genomes with high diversity, structural polymorphism and whole-genome duplication variation. PNAS. 04 Jan 2022.
