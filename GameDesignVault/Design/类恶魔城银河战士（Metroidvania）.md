# 类恶魔城银河战士（Metroidvania）

 #design  #todo 
 
作者：Foursay
首次创建时间：2022-07-10 05:04


## 参考链接

#### 老祖宗 #todo 
- 超级密特罗德
- 月下
- Cave Story (2004)

#### 祖先（？？）
- 三角力量

#### GMTK
- Dread https://www.youtube.com/watch?v=5pop-cc9kmY
- Axiom Edge https://www.youtube.com/watch?v=ZGWHxQ2WcBE
- Hollow Knight https://www.youtube.com/watch?v=vWiDS8SUvds
- *Boss Key*: Metroid Prime 2 https://www.youtube.com/watch?v=GBAQTd2MJFQ
- *Boss Key*: Hollow Knight https://www.youtube.com/watch?v=7ITtPPE-pXE

#### 其他
- 游必有方：Vol.9 论正常的 Metroidvania 有什么坑 https://indienova.com/indie-game-review/indienova-podcast-vol9-momodora/
- 2021 TGDC 暗影火炬城部分 https://www.bilibili.com/video/BV1Cg411P72p?p=5&vd_source=ccfa9fb411806612e333b3d7e055ddc0
- GDC 月下 https://www.youtube.com/watch?v=gLyjAWYK2Kg

#### 文内
- 从“鼻祖”出发，聊聊银河恶魔城游戏的设计理念 https://indienova.com/indie-game-news/metroidvania-design-101/

## 什么是类恶魔城银河战士（Metroidvania）？

类恶魔城银河战士（Metroidvania，简称银河城）现在一般指玩法类似恶魔城系列和银河战士系列的动作冒险游戏。



![[Pasted image 20220710063726.png]]

## 特点：探索 -> 能力成长






探索 
>  "扩张式"!
- **连通的世界**(Connected)
	- “伪开放世界/半开放世界” -> **“回溯探索”**Backtracking
		- Backtracking的核心就是不变的（世界部分本身）和变化的（你：你的角色能力和玩家能力（包括对世界的理解和））
	- 移动
	- 探索的收益
		- Ability（能力），与进程相关
		- Utility（增强？）
		- Space（空间）
- 基于空间关系和能力的锁钥设计（空间（道具）锁和**能力锁**）

> 可控的线性体验，同时感受世界的开放性

能力成长
- 能力 ！= 装备和更好的数值，能力需要和机制相联系
	- 从这个角度来说，魂1确实不算
- 能力进化实质上是一种“进程控制”，机制与游戏进程之间是同步的（？）
- 能力的进化带来的必须是截然不同的游戏体验，改变玩家的游玩思路（而不仅仅是新装备武器）


#todo 关于锁钥和能力锁

> 道具锁 —— 较低的游玩价值
> 谜题锁 —— 极低的可复用性
> 挑战锁 —— 挑战能力的熟练程度
> 能力锁 —— ？



## 分支：更像Metroid还是更像Castlevania

二者共有的是上面的，Castlevania对应的是RPG的部分
- 故事（演出，对话，多结局，场景叙事）
- 数值战斗（装备，技能，道具）
- 系统（商店）

> 很有意思的是，当时月下的目标是“延长游戏时长”
> 这种轻量化的处理，很像RogueLike到Roguelite

## 次级特征

#### 设计
- 环境驱动：游戏内的“重大事件”会半永久性的改变世界地貌
	- [[Metroid Dread]]：冰箱地形
	- [[Hollow Knight]]：梦境泄露后的十字路
	- #todo 月下里的颠倒城
- 碎片化叙事
- 黑暗主题叙事
	- 这个主要和游戏难度有关

- 线性与非线性
	- #todo 关于分支的Best Practice?
	- 关于游戏的“量级”（轻量化 = 线性?），和玩家受众

#### 能力合集
- 常见的能力（90%）
	- 二段跳
	- 冲刺
	- 爬墙
- 非常见的能力（20%）
	- 抓钩
	- 特殊地形
- 独有的 #todo
	- 猛击（Ori）
	- 格挡反击（Grime，这个其实算跨类别）
	- 隐藏位移能力（Ori 2）(这个严格来说，应该放到Feature里)

## 有意思的东西

- 最新的一些银河城，常见能力拿到的都**偏早**，更多
- 在刚进入房间的时候就介绍锁在哪里
- 早一点告诉玩家走不通
- #todo Dread的半砖卡位

## 注意事项（长期更新）

- 保证一次性内容（解密，战斗考验，单向跳跳乐）对玩家来说也是一次性的


## 相关游戏


2D

Tier 1
- [[Metroid Dread]]
- [[Hollow Knight]]
- [[Salt and Sanctuary]]
- [[Ori and the blind forest]]
- [[Axiom Verge]]
- [[Ender Lilith]]
- [[Grime]]
- [[Bloodstain: Ritual of the Night]]
- [[暗影火炬城]]






3D游戏
- [[Dark Souls]]
- [[Control]]
- [[Prey]]