# 碱基周报（第 006 期）：不是 β 淀粉样蛋白导致阿尔兹海默症

记录值得分享的生命科学和生物信息学前沿进展，周日发布。

## 封面图

![img](https://static.fungenomics.com/images/2022/06/2013-647528033-2013-647392058-2013091986229_20130919_20130920.jpg)


## 本周话题： 不是 β 淀粉样蛋白导致阿尔兹海默症

![image-20220609081811447](https://static.fungenomics.com/images/2022/06/image-20220609081811447.png)

一直以来，学界都认为脑内神经细胞外 β 淀粉样蛋白沉积（又称老年斑）是阿尔兹海默症的主要病变原因。所以，“β 淀粉样蛋白”长久以来一直是阿尔兹海默症发病机制的主流学说。但基于此来预防和治疗阿尔兹海默症的药物和方案所产生的效果却不尽人意。

今年 6 月 2 日《自然神经科学》刊登了一项来自美国纽约大学格罗斯曼医学院联合内森克莱恩研究所的最新研究成果，革新了我们过去关于阿尔兹海默症 **“先有细胞外淀粉样斑块形成，后有神经细胞死亡”** 的认识。他们认为实际上应该是：**“先有神经细胞死亡，后有细胞外淀粉样斑块出现”**。这样一来，即便我们清除了细胞外的淀粉样斑块，也已经于事无补，因为被害神经细胞早已死亡。

文章的作者认为 **阿尔兹海默症的发生，始于神经细胞自噬溶酶体“酸化”功能障碍**。

自噬溶酶体是由自噬泡与溶酶体融合形成，溶酶体是细胞的 **“垃圾处理厂“**，自噬泡相当于 **“细胞垃圾运输车”**，它将细胞内损伤的蛋白质、核酸、细胞器等运输到溶酶体进行分解消化。溶酶体内的水解酶需要在**酸性环境**下才能发挥消化分解作用，而这种酸性环境主要靠质子泵 vATPase 将细胞质中的 H+ 离子泵入溶酶体内才能得以实现，一旦溶酶体酸化障碍，垃圾分解的流水线就会停滞，从而造成大量垃圾中间产物的形成并蓄积在溶酶体内，这其中就包括 β 淀粉样蛋白及其前体蛋白。当溶酶体承受不住堆积的”垃圾“破裂后，溶酶体内的水解酶就会被释放进入细胞质中，分解消化细胞，导致细胞膜瓦解，胞内垃圾泄了一地，最终形成我们看到的“细胞外”淀粉样斑块。也就是说，**细胞死亡要先于细胞外淀粉样斑块的形成，甚至可以说这些淀粉样斑块正是死亡的神经细胞混合着β淀粉样蛋白的遗骸**。

研究人员是通过阿尔兹海默症小鼠来证明他们的这个结论的。

这个研究对于踟蹰不前的阿尔兹海默症治疗无异于为临床研究 “拨开云雾见天日”，**发现了阿尔兹海默症的病因不在细胞外，而在于细胞内。而减少斑块生成，避免细胞死亡，关键在于“修好垃圾处理厂”，恢复溶酶体的酸化功能**。这必定会大大影响以后对阿尔兹海默症药物的研究和开发！

事实上，该团队今年4月发表在 Science Advances 上的研究已经证明通过改善溶酶体酸化功能，能够显著减轻阿尔兹海默症小鼠神经损伤！

我在上一期的[碱基周报(第 005 期)](https://mp.weixin.qq.com/s/ceHVw51haQBaXKIa5rJJOA)中提到去年 FDR 批准了一款针对 β 淀粉样蛋白沉积的新药，当时就说到这个药的效果也是饱受质疑的，如今再加上这项研究的证实，这个新药恐怕真的用途不大。

> 1. Faulty autolysosome acidification in Alzheimer’s disease mouse models induces autophagic build-up of Aβ in neurons, yielding senile plaques. https://www.nature.com/articles/s41593-022-01084-8
> 2. Axonal transport of late endosomes and amphisomes is selectively modulated by local Ca2+ efflux and disrupted by PSEN1 loss of function. https://www.science.org/doi/10.1126/sciadv.abj5716


## 文章和资讯

1、**UKBB 38万人数据的孟德尔随机研究发现，喝咖啡和心律失常风险关系不大**

![Coffee Doesn&#39;t Disturb Heart Rhythm: UK Biobank Analysis | tctmd.com](https://static.fungenomics.com/images/2021/07/Coffee%20Doesn%E2%80%99t%20Disturb%20Heart%20Rhythm.jpeg)

这项研究成果在2021年7月21日发表在 *JAMA Internal Medicine*，这个 JAMA 子刊影响因子很高，达到：21.873。

这个研究的主要内容是：

- 利用英国 *Biobank(UKBB)* 中的386,258名受试者，平均随访4.5年期间，共发生16,979 例心律失常；

- 校正人口统计学指标、并发症及生活方式等变量后，每天多摄入一杯咖啡，与心律失常风险降低3%显著相关；

- 单独分析不同类型的心律失常，咖啡摄入与心房颤动、心房扑动及室上性心动过速的风险降低显著相关；

- 基于咖啡因代谢基因（包括 *CYP1A2* rs762551在内的7个SNP）的孟德尔随机化研究显示，**咖啡因代谢与心律失常风险并无显著关联**，甚至还可能和心率失常（包括心房颤动、心房扑动及室上性心动过速）的风险降低相关。

以前的研究而言，认为咖啡可能会增加心率失常的风险，现在研究结果 “打架” 了。

> Coffee Consumption and Incident Tachyarrhythmias: Reported Behavior, Mendelian Randomization, and Their Interactions, https://pubmed.ncbi.nlm.nih.gov/34279564/

2、**适量喝咖啡与死亡风险降低存在相关性**

![Image](https://static.fungenomics.com/images/2022/06/640-20220617160917985.png)
这是一项今年 5 月 31 日发表在 Annals of Internal Medicine (IF=25) 上的一项成果。该研究纳入的是英国 UK Biobank 的参与者，使用了基线期时收集的人口统计学、生活方式和饮食相关数据，随访从2009年开始，到2018年结束。各类咖啡的摄入量由参与者自己报告，研究结局包括全因死亡率、癌症死亡率和心血管疾病死亡率。

在调整生活方式、社会地理位置以及临床相关因素后，结果显示，喝无糖咖啡或加糖咖啡与全因死亡率存在 U 型相关性（低点是 1.5-2.5 杯），且达到统计学显著性（P<0.001），而与不喝咖啡相比，不论无糖咖啡的饮用量如何，全因死亡的风险均降低。

我想这个研究的潜在问题是，能够经常喝咖啡的人通常生活水平比较高，个人的健康护理相对也要更好，工作也更偏向脑力活动。那么平均而言，这群人就会比没喝咖啡的疾病风险更低一些，所以喝咖啡和死亡风险降低之间还不一定能建立因果关系。

> Association of Sugar-Sweetened, Artificially Sweetened, and Unsweetened Coffee Consumption With All-Cause and Cause-Specific Mortality. https://www.acpjournals.org/doi/epdf/10.7326/M21-2977

3、**过量喝咖啡会减少大脑容量并增加患痴呆症的风险**

2021年6月24日，南澳大利亚大学 Kitty Pham 等人在 *Nutritional Neuroscience* 在线发表题为”High coffee consumption, brain volume and risk of dementia and stroke“ 的研究论文。他们同样适用英国 UK Biobank 的数据进行研究，一共包含了 398,646 参与者（37-73 岁）的习惯性咖啡消费，其中包括 17,702 名具有 MRI 信息的参与者。该研究使用协变量调整线性回归检查了与脑容量的关联，并使用逻辑回归检查了痴呆（4,333 例）和中风（6,181 例）的几率。

研究发现，大量饮用咖啡与较小的总脑容量和增加患痴呆症的几率有关。并且咖啡消费与痴呆之间的关联是非线性的（P 非线性 = 0.0001）在调整了相关协变量后，发现与每天 1-2 杯相比，> 6 杯/天的摄入量与痴呆的几率高 53% 相关，但与中风相关的证据则不明显。 

> https://mp.weixin.qq.com/s/d9UQ78Ll5mMLkH5HKp18Bg

4、**多吃“草”与多吃肉的代谢组学特征有何差异?**

![多吃蔬菜反而长胖？](https://static.fungenomics.com/images/2021/07/nRMgyb7rK-szF5v3nhslMXJvhpnd7ORwUeZJINdho6uPzlqH4XWp5Vm-L_Bea_KeGFD8kMIyYQfRNJmYX6AT6mST__6j8flgEDC9ehRfSm65jKgbNf41yJiA.jpeg)

现在的时代，我们营养过剩了，身体受不了，所以很多人已经主动或者被动地认为“多吃草少吃肉”的饮食方式是一个更加健康的生活方式。7月初发表在 *Advances in Nutrition* 上的一篇综述文章明确总结了已有的一些研究成果：**富含动物蛋白（AP）或植物蛋白（PP）的饮食会导致不同的代谢组学特征，一些代谢物可以解释它们与心脏代谢风险的不同关联**。

- 这篇综述纳入了 16 项观察性研究和8项临床试验，发现 439 种代谢物能够区分富含动物蛋白（AP）和植物蛋白（PP）的饮食，其中46种被认为提供了强有力证据，尤其是氨基酸及其相关产物；
- 支链氨基酸、芳香族氨基酸 (AAAs)、谷氨酸、短链酰基肉碱和三甲胺-N-氧化物水平（它们与心脏代谢风险增加相关）与富AP饮食有关，而甘氨酸（与降低风险有关）与富PP饮食有关；
- 三羧酸循环中间体和来自肠道菌群 AAA 降解产物与心脏代谢风险关联还无定论。

> A Scoping Review: Metabolomics Signatures Associated with Animal and Plant Protein Intake and Their Potential Relation with Cardiometabolic Risk. https://academic.oup.com/advances/advance-article-abstract/doi/10.1093/advances/nmab073/6316463

5、熬夜存在危害的一个原因：**免疫系统不陪你一起熬夜**

![image-20210806085904910](https://static.fungenomics.com/images/2021/08/image-20210806085904910.png)

近日，美国得克萨斯大学西南医学中心的一个研究团队在 Cel l上发表了一项名为 "The microbiota coordinates diurnal rhythms in innate immunity with the circadian clock" 的新研究，说的是，**人体的抗感染能力在一天中是不断起落变化的，在该睡觉的时候最弱**。

![image-20210806083704968](https://static.fungenomics.com/images/2021/08/image-20210806083704968.png)

生物钟是一个转录因子网络，存在于几乎所有的组织中，并通过大脑核心时钟的神经元和激素信号与环境光的周期同步，在一个约为 24 小时的周期内驱动有节律的基因表达，从而预测和应对环境的变化。

免疫力减弱和熬夜以及慢性睡眠中断有关。这篇文章的研究人员通过研究小鼠肠道的抗菌免疫力变化找到了引发这一个问题的机制。哺乳动物进食时会使自己暴露于与食物和环境相关的微生物中。为了防止感染，肠上皮细胞会产生先天免疫效应因子，包括分泌大量的抗菌蛋白（AMP），但产生AMP需要耗费掉大量能量。这也就意味着，**肠道先天免疫存在高峰和低谷**。

**这项研究的研究人员通过小鼠实验发现肠道菌群和生物钟协同产生了肠道先天免疫的昼夜节律**。具体来说，小鼠的进食行为促进了肠道分段丝状菌（SFB）节律性地附着于肠上皮，并驱动上皮细胞信号传导和转录激活因子3（STAT3）的表达和激活振荡，从而产生了一种被称为再生胰岛衍生蛋白3γ（REG3G）的抗菌分子在夜间的含量更高（此时为夜行性动物的活跃状态）；而在白天睡眠时含量较少。但在无菌小鼠体内，无论白天还是晚上，REG3G 基本上都不存在。他们发现，**当在睡眠时间用细菌感染正常小鼠的时候，这些小鼠的细菌负荷和死亡率更高**。

**所以大家半夜要起来吃夜宵的时候要三思，因为那时正是你的肠道防御能力最弱的时候。**

> https://doi.org/10.1016/j.cell.2021.07.001

6、**运动确实可抗癌**

![img](https://static.fungenomics.com/images/2022/06/T7z70K32532VNV.png)

科学家证实，有氧运动可以激活特定抗癌免疫细胞，抑制胰腺癌生长。

> https://www.toutiao.com/article/7106121315135947301

7、**运动过度损害线粒体的功能**

![High-intensity exercise training — too much of a good thing? | Nature  Reviews Endocrinology](https://static.fungenomics.com/images/2022/06/41574_2021_500_Fig1_HTML.png)

随着运动强度的增加，线粒体功能和血糖调节功能得到改善。然而，一些运动员提出存在运动限度，超过这一限度之后，其运动表现会下降。一项发表在 *Cell metabolism* 上的研究发现在过度运动（该限度因人而异）的情况下，线粒体功能（尤其是通过糖酵解生成三磷酸腺苷的功能）大幅下降，葡萄糖耐量也大幅下降。同时发现耐力项目运动员的葡萄糖调节功能较差（他们每日处于高血糖和低血糖范围的时间较长)

> https://nejmqianyan.cn/article/yxqy-jw.NA53457

8、**日研究称小行星样本含多种氨基酸，系首次在地球外确认存在氨基酸**

![img](https://rs-channel.huanqiucdn.cn/imageDir/bed0a125b0c734b2adc66f3d7609deba.jpg)

今年 6 月 6 日，日本宇宙航空研究开发机构（JAXA）在“隼鸟2号”小行星探测器带回的岩石样本（5.4 克）中，发现了超过20种氨基酸，这是首次在地球以外确认氨基酸的存在。

这个成果还没通过研究论文正式发表，我们拭目以待吧。

> https://3w.huanqiu.com/a/0c789f/48K7rfiQXUc


## 订阅

《碱基周报》首发于个人公众号：**helixminer（碱基矿工）**

<img src="https://static.fungenomics.com/images/2021/03/helixminer-mid-red.png" alt="helixminer-mid-red" style="zoom:60%;" />

