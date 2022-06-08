---
title: "D&D5e PL 战斗指南"
linkTitle: "战斗指南"
weight: 21
type: docs
---

{{% pageinfo %}}
作者：星尘
{{% /pageinfo %}}

## 前置要求
本文旨在帮助初次使用 FVTT 的 DM 和 PC 快速入门战斗操作。

默认你已经车好了一张正确的人物卡。

作者安装的模组为：
- [核心系统中文化](../../../../modules/mods/#核心系统中文化)
- [5e 中文化](../../../../modules/mods/5e/#5e-中文化)
- [5e 中文职业合集包](../../../../modules/mods/5e/#5e-中文职业合集包)
- [Tidy 5e Sheet](../../../../modules/mods/5e/#tidy-5e-sheet)

~~毕竟这几个模组不装就几乎玩不成 5e 吧\~~~

----

## DM 准备工作
1. 首先，需要有指示物在地图上
2. 在战斗指示器开启一轮战斗遭遇
   - ![战斗指示器](/images/tutorial/pl/battle/combat-tracker.png)
   - 点击左边的小加号可以创建一个战斗遭遇
3. 将参与战斗的目标指示物置入战斗板
   - ![加入战斗](/images/tutorial/pl/battle/join-combat.png)
   - 方法是：选中目标指示物，右键，会出现六个图标，点击右下角的剑盾相交图标
4. 投掷先攻
   - ![先攻](/images/tutorial/pl/battle/roll-init.png)
   - 从左到右依次是 **全体骰先攻**、**NPC 骰先攻**、**重置先攻**
   - *PC 的系统也会有这个，而且可以自己骰自己的。*
   - 先攻检定完成之后系统会按顺序排列战斗次序，如图：
   - ![投掷完的先攻](/images/tutorial/pl/battle/rolled-init.png)
5. 开始战斗！
   - 点击最下方的开始战斗，进入战斗轮，每一个单位结束自己的战斗轮后，点击结束战斗右边的右箭头，进入到下一个单位的战斗轮。但战斗结束时，单击结束战斗以退出战斗板
   - *战斗板的一个小技巧：*
      + *单击头像会以地图上的指示物为目标自动对齐，并切换到目标的视野*
      + *双击头像可调出目标的数据或者人物卡*

**具体的战斗操作将放在 [PC 篇](#pc-操作)一起讲解。**

----

## PC 操作
### 战前准备
*这时就默认你会人物卡的基本检定和车卡工作了*
* 点开自己的人物卡，把你的武器、法术、物品、职业特性和其他常用的东西拖到快捷栏里，当然，追求效率的DM也可以这样做

   ![地精的常用武器](/images/tutorial/pl/battle/hotbar-weapons.png)

   （由于兼容原因，有时候用快捷键调用物品会弹出报错，这时候就自己点吧）
* DM检查一下你的怪物图标放进去了没，这里顺便说一下选中后右键指示物的按钮用法

   ![右键指示物](/images/tutorial/pl/battle/rightclick-token.png)
   + 左上：指示物的高度
   + 左中：设置界面，有关指示物的名称什么的杂七杂八的东西都在这里
   + 左下：选择/取消选择目标，注意，不是选中指示物，选择目标后，它会被四个三角形所包围起来，选中指示物的话啊，包围的是个框框。选中的效果是应用某些东西，比如伤害或者治疗
   + 下方：显而易见，这是 HP，靠上面些的绿色格子是血条
   + 右下：加入战斗板
   + 右中：左键单击可对目标添加状态的标记物，比如倒地、昏迷或中毒等
   + 右上：设置指示物可见性，点击一下，DM 视角变得半透明，PC 视角看不见，再点一下恢复原来的样子

-----------

### 开始战斗

对于玩家，你需要进到战斗板里骰先攻，点击你头像后的骰子就可以，FVTT 会自动排序

![玩家的先攻检定](/images/tutorial/pl/battle/player-roll-init.png)

--------

> 这里说一个小技巧，或许你对在战斗轮时来回切换聊天界面和战斗板界面有些厌倦，这时候你可以这样：
>
> 右键单击最上面一排功能键中的战斗板，你就会获得一个半透明的浮动板面了，就算在展开也不会消失，大部分板面都可以这样，非常美观。
>
> ![浮动的战斗板](/images/tutorial/pl/battle/pop-combat-tracker.png)

---------

D&D 5e 里的战斗，在 FVTT 需要说的更多是攻击、施法和移动

#### 攻击
打开聊天记录面板，然后选择你的攻击目标，之后单击快捷栏或者人物卡里的武器，系统会自动把相关信息发到聊天框里面。

![攻击界面](/images/tutorial/pl/battle/attack-dialog.png)

首先，你应该点击攻击（以 DM 的意见为准）。

![攻击骰](/images/tutorial/pl/battle/attack-dice-dialog.png)

输入具体的信息，比如加减值（注意别改公式），之后就可以单击下面的三个按钮进行检定了。

![攻击骰结果](/images/tutorial/pl/battle/attack-dice-result.png)

之后会给出结果，当你的攻击命中后，之后是投掷伤害。

![伤害骰](/images/tutorial/pl/battle/damage-dice-dialog.png)

按 DM 的要求就可以，比如我这次就按普通骰出伤害。

再然后你就可以把伤害给应用上去了，选则目标后（被三角形围住），右击你的伤害面板，选择对应的应用方案（也可以由勤劳的 DM 代劳），这样，怪物的血量就会降低相应的值了。

![伤害骰结果](/images/tutorial/pl/battle/damage-dice-result.png)

这就是一次攻击的过程了，值得一提的是，DM 需要在 NPC和 PC 进入某种状态时加上对应的标记物。

当某个目标失去战斗能力后，可以点击战斗板对应头像下的骷髅头，使之退出战斗，还可以将其隐藏方便观察战场。

![死亡标记](/images/tutorial/pl/battle/death-skull.png)

此时在下一轮，会自动跳过去它的回合，直到恢复战斗力（记得死亡豁免）。

#### 施法
以一环法术 *燃烧之手* 举例，仍然是先拖到快捷栏，当然不嫌麻烦的话从人物卡点也行。施法操作和攻击操作差别不大，主要是多了一个放置量板和可能有的豁免。

我们点击 *燃烧之手* 的图标，弹出这个：

![施法](/images/tutorial/pl/battle/cast-spell-dialog.png)

按默认勾选就可以，系统会自动计算法术位之类的东西，单击释放法术。

然后会出现一个跟随鼠标的量板，比如这个就是扇形的：

![测量板](/images/tutorial/pl/battle/measure-template.png)

把量板挪到需要释放法术的位置，单击一下，会自动帮你算法术波及的范围。

![放置测量板](/images/tutorial/pl/battle/place-measure-template.png)

然后 DM 或者 PC 可以进行相对的豁免检定，法术攻击检定，如果有的话。

![进行豁免](/images/tutorial/pl/battle/spell-save.png)

另外，从聊天记录里面进行豁免检定时，你需要先选中一个指示物或者目标才可以。

之后与上面的攻击相同的，投掷伤害，应用伤害，如此这般。

此外，如果是一些不需要放量板的法术，就直接用就可以了，比如修复术，直接点击就会发出相应的信息，便于查看。

![直接施法](/images/tutorial/pl/battle/spell-direct.png)

#### 移动
选择你的指示物，在地图上拖动就可以了。

---

第一次写指南，或许有错误与疏忽之处，敬请指出。