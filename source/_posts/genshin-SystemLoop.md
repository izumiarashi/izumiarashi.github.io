---
title: 《原神》系统拆解及经济循环分析
img: 'https://izumi-blog.oss-cn-shanghai.aliyuncs.com/img/paimon.jpg'
cover: false
coverImg: 'https://izumi-blog.oss-cn-shanghai.aliyuncs.com/img/7873d29833c490a00214010afcc7fed5.png'
date: 2021-03-09 11:43:12
category: 游戏拆解
tags: 
- 游戏策划
- 原神
summary: 没有找到比较全面的经验表，且个人水平有限，暂不分析数值投放。
---

<!--more--> 

**文档修改列表**

| 时间       | 完成事项                                                     |
| ---------- | ------------------------------------------------------------ |
| 2020-10-10 | 建立文档                                                     |
| 2020-11-15 | 大体框架完成                                                 |
| 2021-01-05 | 细化大地图系统；增加优化建议（蓝字）、不足之处（红字）       |
| 2021-01-15 | 罗列运营、辅助模块；细化养成和社交系统；增加设计目的（绿字） |
| 2021-02-05 | 细化经济、战斗、养成系统、辅助模块；调整排版                 |
| 2021-03-08 | 细化各模块的规则说明，绘制经济循环图                         |
| 2021-03-10 | 分析经济循环，对拆解框架勘误                                 |
| 2021-03-11 | 细化战斗系统                                                 |

# 总体框架

![原神](https://izumi-blog.oss-cn-shanghai.aliyuncs.com/img/原神.png)

**注：**本文中的“伤害公式”因本人水平有限，并非亲自推导，资料来源于网络。

[【原神机制分解②】【超硬核】伤害精确计算（各大乘区详细讲解、干货知识补充）](https://www.bilibili.com/video/BV1Sh411y7Pr)

# 经济循环

![原神养成](https://izumi-blog.oss-cn-shanghai.aliyuncs.com/img/原神养成.png)

注：图中的一次性产出是指在日期更新、版本更迭等会造成新内容投放的节点后，玩家仍然无法再次获得的产出手段。

注2：由于在单次运营活动（邮件、海灯节）内，奖励仅可获得一次，在此将其划分为一次性产出。



​		可以看出，《原神》通过控制树脂的投放来限制摩拉和冒险阅历的产出作为主要手段，同时限制材料狗粮的产出作为辅助手段，共同限制玩家养成进度。

​		根据玩家不同时期的游戏目标，本文将游戏进度分为3个时期。

## 1、探索期（冒险等阶1-20级）

​		刚进入游戏的玩家探索欲望较强，此时的限制主要在于逐步开放功能，避免一次性开放过多功能使玩家学习困难。《原神》在该时期将功能、剧情的解锁与冒险等阶相联系，同时通过主线任务投放大量的冒险阅历，让玩家可以较为平滑的度过这一段时期，解锁完全部功能。玩家可以为了新功能/新区域/新剧情而去持续地游玩。

​		

![功能开启顺序](https://izumi-blog.oss-cn-shanghai.aliyuncs.com/img/image-20210309230312603.png)

## 2、瓶颈期（冒险等阶20-40级）

​		20级之后（约15小时体验时长）开始设置卡点，主要体现在主线剧情需要提升到相应冒险等阶才能够解锁，玩家仅通过主线剧情给予的冒险阅历难以满足条件，因而会需要参与到委托等日常活动之中。《原神》于该时期开始**对玩家的日常活动进行行为训练**。此时玩家的养成进度主要由冒险阅历及材料的投放进行限制，由控制树脂的投放作为限制手段。

​		玩家每天能够不限次数的挑战秘境或boss，但每次挑战会消耗树脂，树脂仅能通过每8分钟1点的自动恢复，或是每天有限次的消耗原石进行补充。和大多数手游一样，付费玩家可以用金钱换时间，一定程度上缩短养成周期，免费玩家则需要更长的时间养成。避免了玩家在短时间内体验完游戏内大部分内容导致流失。

​		同时，在冒险等阶到达20级后，每升5级便会提升1级世界等级，怪物的等级、种类也会相应的增加。使玩家在长时间处在“完成目标——树立新目标”的心流体验之中。

![世界等级提升后，战斗力底层的史莱姆也有很高的属性](https://izumi-blog.oss-cn-shanghai.aliyuncs.com/img/image-20210310225107635.png)

​		完成每日委托也会获得大量的冒险阅历，却只能较少的获得养成所需素材，容易让玩家出现世界等级虚高的情况。《原神》对此的解决方案是在可提升世界等级时玩家获得一个突破任务，玩家需要通关特定关卡才能够提升世界等级。给予了玩家主动选择权，又设置关卡进行数值验证。确保玩家在提升等级后不会遇到远超自己队伍实力的怪物。

​		但这也一定程度上**破坏了玩家的沉浸体验**，将玩家的成长和世界的变化过程过于露骨的量化，缺乏一定的文案包装。可以将突破关卡本身进行文案包装，比如“玩家解决日常任务后发现某处地脉异常，前往调查发现魔物聚集，密谋着什么。玩家消灭怪物后暂且消除了危机，但也使深渊更加警觉，加强了各地的怪物。”这样，有些生硬和俗套，却也更加合理。

​		将剧情与冒险等阶相结合也一定程度上造成了玩家在探索时的心流体验中断，可以学习mmorpg的养成模式，通过**更多的支线、收集要素**，增加玩家获得冒险阅历的渠道，在主线流程中让玩家的注意力被其他事物分散，在完成这些非主线内容后不知不觉中便满足了解锁剧情的条件。

![《激战2》在地图中分配了大量的可探索要素，众多获取经验的渠道增加了玩家探索的欲望](https://izumi-blog.oss-cn-shanghai.aliyuncs.com/img/image-20210316230616019.png)

​		此外，游戏内的秘境采用的是比较简单的等级准入规则，没有到对应等级就不允许进入，同样破坏了沉浸感。个人认为一方面应当设置风龙废墟的风墙这类较符合世界观的障碍，并结合“配置等级较高的强力怪物挡路”的数值手段来限制玩家的通行。

![异度之刃2中通过高等级怪物来限制玩家的移动路线，使生态更加合理的同时也使玩家养成获得的反馈更加强烈](https://izumi-blog.oss-cn-shanghai.aliyuncs.com/img/image-20210310221820292.png)

​	

## 3、长草期（冒险等阶40级后）

​		40级之后，和大多数游戏一样，玩家已经体验完了游戏内大多数玩法和收集要素，对新事物的探索热情下降，且剧情更新进度难以跟上玩家进度，难以持久的吸引玩家。此时的玩家需要一个或多个目标来维持用户粘性，于是游戏将主/支线剧情全部开放，不再通过剧情作为限制玩家的手段，开始引导玩家将游玩目标从剧情逐渐转向数值培养。

​		《原神》针对这一部分玩家设计了两套系统。

（1）圣遗物

​		网上对该系统已有诸多介绍，在此不再赘述其内容。

​		[圣遗物机制详解！附满级主属性、副属性数据【空荧酒馆】](https://www.bilibili.com/read/cv7784365/)

​		①设计目的

​		主副属性及套装属性的设计很好地满足了不同阶段玩家的需求，较前期玩家仅仅需要刷满一套能够触发套装属性的圣遗物即可；较后期时玩家会开始刷有更高稀有度、更优秀主属性词缀的圣遗物；而追求极限的玩家会进一步刷需要的副属性词缀。

​		而引入随机掉落圣遗物，随机追加、强化词条的功能带来的大量冗余要素又为养成挖下了更深的坑，使玩家能持续的维持“斯金纳箱”式的状态，长期保有游玩的动力。同时，秘境所能获得的圣遗物稀有度完全由世界等级进行控制，由于树脂的机制存在，进一步拉长了养成线。

​		玩家在高世界等级后才能够获得所有种类的5星圣遗物，一方面提高了玩家对提升世界等级的欲望，一方面也间接引导了前中期玩家的体力规划，——将刷圣遗物的优先级置后，优先养成角色和武器。

​		②存在问题

​		·消耗方式单一

​		目前多余的圣遗物，尤其是多余的高稀有度圣遗物没有一个较好的回收机制。花费大量时间精力刷到的词条不好的圣遗物，只能简单地将其作为狗粮或是摧毁以获取摩拉，投入和产出不成正比，会不断降低其在玩家心中的锚定价值，从而导致玩家在获得圣遗物时的正反馈大幅下降。可以从两方面入手：

​		一方面扩展其用途。可以对已有圣遗物进行定向强化，比如消耗同名同稀有度的圣遗物可以随机重置一个词条的内容，或是可以定向强化某个当前已有的词条的数值；或者增加摧毁时的收益，类似于《战双帕弥什》的意识系统，分解n个橙色圣遗物获得的碎片可以兑换1个随机词条橙色圣遗物。

​		另一方面增加圣遗物的需求量。通过角色设计、队伍元素共鸣设计，使能够在同一队伍中配置更多同属性/同定位角色，而这些角色所需的圣遗物大多相同，玩家不再能够一套圣遗物给角色轮流用。

​		这样，降低了玩家养成难度，也提高了玩家对于下一个养成深坑的接受度，从而可以推出圣遗物精炼、突破或共鸣等一系列加大圣遗物需求、进一步拉开玩家差距的系统，延长玩家生命周期。

![《战双帕弥什》看似可方便兑换的意识，实际隐藏着更深的养成大坑：共鸣](https://izumi-blog.oss-cn-shanghai.aliyuncs.com/img/image-20210310232417639.png)

​		·反馈效果弱

​		如果希望玩家能获得比较强烈的正反馈，就需要设置一些难度较高、前期难以攻克、奖励较好的目标。目前玩家的目标较为单一，仅有周常boss和深境螺旋这两种，且前者的奖励多为大量消耗的素材，定位为需要多次重复挑战的周回本，降低了玩家对其的心理预期，也就降低了攻克时的成就感；后者为定期开放的固定奖励活动，不仅与开放世界的设定所割裂，同时关卡内的战斗也较为单调。

​		要增加数值验证的途径，可以新增一类挑战型关卡，作为玩家养成的终极目标。关卡内设置的高伤害、低容错率，并有数值检测机制（血量检测、DPS检测）的boss，玩家需要长期的养成来提高容错率，并通过数值检测。关卡奖励为可以增强指定角色某一属性的一次性道具，并具有一定的象征意义（戒指、礼物等），该道具仅有此一种产出方式。

​		![《碧蓝幻想》中的路西法HL有着极高的难度，首次通过后产出制作强力武器的材料，玩家solo成功还有额外称号奖励，玩家能从中获得极强的成就感](https://izumi-blog.oss-cn-shanghai.aliyuncs.com/img/image-20210315230730455.png)

（2）深境螺旋

​		玩家通过养成抬高了自己的各项数值，但数值带来的反馈不够直观也不够强烈，因而《原神》又设计了“深境螺旋”系统。

​		深境螺旋分为两部分：深境回廊和渊月螺旋。

​		深境回廊为一次性挑战关，共有8层，1层有3间，每间最高可获得3颗渊星的评价，每层获得6颗渊星后可以进入下一层，每层获得到3/6/9星时都可以获取一次奖励，在前两间获得渊星后中断挑战，也可以保留前两间的评价，进一步降低门槛的同时也鼓励了玩家有针对性的进行多次挑战。

​		各层有专属的地脉异常，每月初会更新渊月祝福，两者都会为玩家提供不同的增益buff。关卡内采用伪roguelike式的玩法，每间开始时可从三个深秘降福词条选择一个，会在本关或本层内获得增益buff。降低了玩家养成门槛，增加了可玩性，并引导玩家组建更加合适的阵容。

![三个深秘降福的词条不会因为退出重进关卡而改变](https://izumi-blog.oss-cn-shanghai.aliyuncs.com/img/image-20210310225736417.png)

​		渊月螺旋在深境回廊通关8层后开启，共有3层（9-12层），关内机制同深境回廊。每月月初和月中重置可获取奖励次数。

​		深境螺旋为玩家提供了数值验证的平台，使玩家养成角色所带来的反馈更加直观。且能够获得大量的原石作为奖励，鼓励玩家参与到该玩法之中，进一步提高玩家养成的动力。

（3）小结

​		上述两个系统，前者为后者提供基础，后者为前者赋予意义。使玩家很长一段时间内都拥有明确的目标，并不断从中获取成长的快感。

​		此外，经济系统在这一时期也为养成线的拉长发挥了巨大的作用。在武器/角色/圣遗物较高等级时，摩拉的消耗飞速增长。而摩拉的主要产出途径与树脂及每日/每周更新的任务直接相关。延缓了玩家达成目标的进度，也一定程度上增强了达成目标时的成就感。

