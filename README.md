# AIWG: AI World Generator / AIWG: AI 世界生成器

**English**

[Project page](https://ruixiaozhang.com/index_EN#work-aiwg)

A room is more than a collection of plausible objects. Its purpose depends on what people can do there, how objects work together, and whether there is room to move and use them. AIWG explores these relationships across assets, activity groups and spaces.

![Objects, activities and spaces](docs/media/representation-scales.png)

The nesting shows relationships between scales—not model stages or the order of generation.

The current prototype combines learned asset features with explicit rules. Learned models for activity groups and spaces remain experimental; this is not an end-to-end learned system.

**中文**

[项目网页](https://ruixiaozhang.com/#work-aiwg)

房间不只是一些看起来合理的物件。它的用途取决于人在其中能做什么、物件如何配合，以及是否留出了通行和使用的空间。AIWG 从资产、活动组和空间三个尺度研究这些关系。

![物件、活动与空间](docs/media/representation-scales-zh.png)

嵌套表示尺度之间的关系，不表示模型阶段或生成顺序。

当前原型结合学习得到的资产特征与显式规则。活动组和空间层的学习模型仍在实验中，不是端到端学习系统。

## From similarity to usable space / 从相似物件到可用空间

**English**

Embeddings describe aspects of similarity and context. They can help choose related objects, but similarity alone cannot establish access, physical fit or usability. The current hospital prototype combines learned asset features with explicit spatial and interaction rules, followed by inspection and revision in Unreal Engine.

**中文**

Embedding 用于描述相似性和使用情境，可以帮助选择相关物件，但相似不等于放得下、走得到或用得了。当前医院原型把学习得到的资产特征与明确的空间、交互规则结合，在 Unreal Engine 中检查并修改生成的环境。

## Reusable construction / 可复用的建构

**English**

AIWG is also exploring reusable geometry and material construction, so scene variety can extend beyond selecting items from a fixed asset collection. The direction connects spatial understanding, functional allocation, model construction and placement dependencies across objects, activity groups and rooms. Current prototypes still require geometric and material inspection; this is a development direction, not a demonstrated universal scene generator.

**中文**

AIWG 也在探索可复用的几何与材质建构，让场景种类不只取决于固定资产集合中的选件。这一方向把空间理解、功能分配、模型建构和依赖放置联系起来，覆盖物件、活动组与房间。当前原型仍需几何和材质检查；这里介绍的是开发方向，不代表已具备通用场景生成能力。

## My work and current limits / 我的工作与当前限制

**English**

I develop the research concept, interaction design and prototype workflow. The three scales organise the problem; they are not three validated learned models. Higher-level learning remains experimental, and its benefit over simple baselines has not been established.

**中文**

我负责研究构思、交互设计和原型流程开发。三个尺度用于组织问题，不代表三个经过验证的学习模型。高层学习仍处于实验阶段，相对简单基线的收益尚未确立。

## Work in progress / 仍在推进的研究

**English**

The work and manuscript are in progress. These scene images show the setting and visual development, not proof of complete interaction reliability or research effectiveness. This page shares the approach and its limits, without training details, experimental figures or player-study results.

Since October the prototype has been extended from the hospital to a second setting, a commercial kitchen. The kitchen is built from reusable parametric parts with full material maps, and is used to test whether the same construction and checking workflow carries over to a different kind of space. Its interaction checks are scripted samples; it has not been reviewed in free play.

**中文**

工程与论文仍在推进。这里的场景图呈现场景和视觉探索，不证明交互已全面可靠或研究方法已经有效。本页只介绍思路与限制，不公开训练细节、实验数字或玩家研究结果。

10 月起，原型从医院扩展到第二类空间：商用后厨。后厨由可复用的参数化部件搭建，材质带完整贴图，用来检验同一套搭建与检查流程能否用到另一类空间。后厨的交互检查是脚本化的抽样，还没有经过自由试玩评审。

## Inside the hospital prototype / 医院原型场景

**English**

### Corridor and circulation

![Corridor and circulation](docs/media/corridor.webp)

Development scene from the hospital prototype, shown as a lighting study—not evidence of completed interaction tasks.

### A connected multi-storey setting

![A connected multi-storey setting](docs/media/atrium.webp)

Development scene from the hospital prototype, shown as a lighting study—not evidence of completed interaction tasks.

### A room organised around use

![A room organised around use](docs/media/ward.webp)

Development scene from the hospital prototype, shown as a lighting study—not evidence of completed interaction tasks.

**中文**

### 走廊与通行


医院原型的开发场景，呈现灯光探索，不作为交互任务已完成的证据。

### 彼此连通的多层空间


医院原型的开发场景，呈现灯光探索，不作为交互任务已完成的证据。

### 围绕使用组织的房间


医院原型的开发场景，呈现灯光探索，不作为交互任务已完成的证据。

## Inside the kitchen prototype / 后厨原型场景

**English**

### A kitchen organised by work stations

![A kitchen organised by work stations](docs/media/kitchen.webp)

Development scene from the commercial kitchen prototype, an entrance overview—not evidence of completed interaction tasks.

**中文**

### 按工位组织的后厨

![按工位组织的后厨](docs/media/kitchen.webp)

商用后厨原型的开发场景（入口全景），不作为交互任务已完成的证据。

## Related pages / 相关页面

**English**

[AINPC](https://github.com/Shawn200212/Author-Constrained-AINPC)

[Disclosure](DISCLOSURE.md) · [Image inventory](docs/public-media.json) · [Rights and credits](RIGHTS_AND_CREDITS.md)

Overview updated 28 October 2026. Existing concepts and the hospital images correspond to the earlier project website overview. The kitchen paragraph and image were added here; the website was not synchronized in this update. This repository is a research overview, not a runnable project or a complete research artifact.

**中文**

[AINPC](https://github.com/Shawn200212/Author-Constrained-AINPC)

[公开范围](DISCLOSURE.md) · [图片清单](docs/public-media.json) · [权利与署名](RIGHTS_AND_CREDITS.md)

概览更新于 2026 年 10 月 28 日。既有概念与医院场景图对应此前的项目网页概览。本次在此加入了后厨的说明和场景图，尚未同步项目网页。本仓用于研究介绍，不是可运行工程或完整研究材料。
