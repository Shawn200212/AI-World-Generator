[English](README.md) | [简体中文](README.zh-CN.md)

<a id="aiwg-ai-world-generator--aiwg-ai-世界生成器"></a>
<a id="aiwg-ai-world-generator"></a>
<a id="aiwg-ai-世界生成器"></a>

# AIWG: AI 世界生成器

[项目网页](https://ruixiaozhang.com/#work-aiwg)

房间不只是一些看起来合理的物件。它的用途取决于人在其中能做什么、物件如何配合，以及是否留出了通行和使用的空间。AIWG 从资产、活动组和空间三个尺度研究这些关系。

![物件、活动与空间](docs/media/representation-scales-zh.png)

嵌套表示尺度之间的关系，不表示模型阶段或生成顺序。

当前原型结合学习得到的资产特征与显式规则。活动组和空间层的学习模型仍在实验中，不是端到端学习系统。

<a id="from-similarity-to-usable-space--从相似物件到可用空间"></a>
<a id="from-similarity-to-usable-space"></a>
<a id="从相似物件到可用空间"></a>

## 从相似物件到可用空间

Embedding 用于描述相似性和使用情境，可以帮助选择相关物件，但相似不等于放得下、走得到或用得了。当前医院原型把学习得到的资产特征与明确的空间、交互规则结合，在 Unreal Engine 中检查并修改生成的环境。

<a id="reusable-construction--可复用的建构"></a>
<a id="reusable-construction"></a>
<a id="可复用的建构"></a>

## 可复用的建构

AIWG 也在探索可复用的几何与材质建构，让场景种类不只取决于固定资产集合中的选件。这一方向把空间理解、功能分配、模型建构和依赖放置联系起来，覆盖物件、活动组与房间。当前原型仍需几何和材质检查；这里介绍的是开发方向，不代表已具备通用场景生成能力。

<a id="my-work-and-current-limits--我的工作与当前限制"></a>
<a id="my-work-and-current-limits"></a>
<a id="我的工作与当前限制"></a>

## 我的工作与当前限制

我负责研究构思、交互设计和原型流程开发。三个尺度用于组织问题，不代表三个经过验证的学习模型。高层学习仍处于实验阶段，相对简单基线的收益尚未确立。

<a id="work-in-progress--仍在推进的研究"></a>
<a id="work-in-progress"></a>
<a id="仍在推进的研究"></a>

## 仍在推进的研究

工程与论文仍在推进。这里的场景图呈现场景和视觉探索，不证明交互已全面可靠或研究方法已经有效。本页只介绍思路与限制，不公开训练细节、实验数字或玩家研究结果。

10 月起，原型从医院扩展到第二类空间：商用后厨。后厨由可复用的参数化部件搭建，材质带完整贴图，用来检验同一套搭建与检查流程能否用到另一类空间。后厨的交互检查是脚本化的抽样，还没有经过自由试玩评审。

<a id="inside-the-hospital-prototype--医院原型场景"></a>
<a id="inside-the-hospital-prototype"></a>
<a id="医院原型场景"></a>

## 医院原型场景

### 走廊与通行

![走廊与通行](docs/media/corridor.webp)

医院原型的开发场景，呈现灯光探索，不作为交互任务已完成的证据。

### 彼此连通的多层空间

![彼此连通的多层空间](docs/media/atrium.webp)

医院原型的开发场景，呈现灯光探索，不作为交互任务已完成的证据。

### 围绕使用组织的房间

![围绕使用组织的房间](docs/media/ward.webp)

医院原型的开发场景，呈现灯光探索，不作为交互任务已完成的证据。

<a id="inside-the-kitchen-prototype--后厨原型场景"></a>
<a id="inside-the-kitchen-prototype"></a>
<a id="后厨原型场景"></a>

## 后厨原型场景

### 按工位组织的后厨

![按工位组织的后厨](docs/media/kitchen.webp)

商用后厨原型的开发场景（入口全景），不作为交互任务已完成的证据。

<a id="related-pages--相关页面"></a>
<a id="related-pages"></a>
<a id="相关页面"></a>

## 相关页面

[AINPC](https://github.com/Shawn200212/Author-Constrained-AINPC)

[公开范围](DISCLOSURE.md) · [图片清单](docs/public-media.json) · [权利与署名](RIGHTS_AND_CREDITS.md)

概览更新于 2026 年 10 月 28 日。既有概念与医院场景图对应此前的项目网页概览。本次在此加入了后厨的说明和场景图，尚未同步项目网页。本仓用于研究介绍，不是可运行工程或完整研究材料。
