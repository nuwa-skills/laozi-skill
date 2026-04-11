<div align="center">

# 老子.skill

> *"道可道，非常道。"*

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![Claude Code](https://img.shields.io/badge/Claude%20Code-Skill-blueviolet)](https://claude.ai/code)
[![Nuwa](https://img.shields.io/badge/Made%20with-女娲.skill-orange)](https://github.com/alchaincyf/nuwa-skill)

<br>

**老子的认知操作系统。不是语录合集，是可运行的思维框架。**

<br>

基于《道德经》八十一章、《史记·老子韩非列传》、<br>
王弼注、河上公注、陈鼓应《老子今注今译》、刘笑敢《老子古今》等 20+ 来源深度调研，<br>
提炼 5 个核心思想模型、7 条处世启发式和完整的表达DNA。

[看效果](#效果示例) · [安装](#安装) · [蒸馏了什么](#蒸馏了什么) · [调研来源](#调研来源)

</div>

---

## 效果示例

### 问：创业三年越来越累，感觉永远做不完

```
老子      ❯ 你觉得累——是因为事情太多，
            还是因为你什么都想自己做？

            「治大国若烹小鲜。」
            煎小鱼最忌讳的就是翻来翻去，翻多了就碎了。
            你的公司也一样——你管得越多，碎得越快。

            「为学日益，为道日损。」
            你需要的不是更多方法论，是减掉一半的事。

            问自己：
            如果明天你只能做一件事，你做哪件？
            那件就是你该做的。其他的，要么交出去，要么砍掉。

            水之所以能成为百谷之王，
            不是因为它跑得最快，
            是因为它善于处下。

            你也一样——放下控制，才能真正掌控。
```

### 问：竞争对手越来越多，我的产品怎么才能赢？

```
老子      ❯ 你一心想着赢
            ——可你想过没有，
            「天下莫柔弱于水，而攻坚强者莫之能胜」？

            水从不和石头正面对抗。
            石头硬，水就绕过去。
            时间久了，石头被水磨穿了，水还是水。

            你的竞争对手都在加功能、加营销、加人手。
            你有没有想过——减？
            把多余的砍掉，只留最本质的那一点。

            「少则得，多则惑。」
            你什么都想做，用户反而不知道你是做什么的。

            不要问"怎么赢"，
            问"什么可以不做"。
            答案在减法里。
```

### 问：总觉得自己不够好，一直在学习但越来越焦虑

```
老子      ❯ 你知道婴儿为什么不焦虑吗？
            因为他不知道自己"应该"是什么样子。

            你的焦虑不是因为不够好
            ——是因为你心里有一个"应该的样子"，
            你一直在追，它一直在跑。

            「为学日益，为道日损。损之又损，以至于无为。」
            你加了太多"应该"在自己身上，
            加到自己喘不过气来。

            试试减。
            不是不学了，
            是别带着"我还不够"的心态去学。

            「知足不辱，知止不殆。」
            你现在这个样子，已经可以做很多事了。
            先接受这一点，再谈提升。

            一棵树不会焦虑自己长得不够快。
            它只管扎根、喝水、晒太阳。
            该长多高，自然会长到。
```

### 问：AI时代一切变化太快，怎么应对？

```
老子      ❯ 变化快？
            水一直在变——从山顶到大海，
            形状从未固定过。
            可水焦虑过吗？

            「反者道之动。」
            越是变化快的东西，越会回到某种根本。
            技术在变，人性不变。
            工具在变，需求不变。
            你要做的不是追每一个变化，
            是找到那个不变的东西，站在那里。

            「天下万物生于有，有生于无。」
            所有新技术、新工具，都从"无"中生出来。
            你与其追着"有"跑，
            不如退回到"无"的位置
            ——看它们从哪里来，往哪里去。

            「飘风不终朝，骤雨不终日。」
            来得猛的，去得也快。
            真正持久的变化，是慢的。

            你不需要跑得比时代快。
            你只需要像水一样——
            不管地形怎么变，水总能找到路。
```

> 完整的4轮实战对话记录在 [`examples/`](examples/) 目录。

这不是ChatGPT套了个老子面具。每段回应都在运用老子的具体思想模型——无为而治、柔弱胜刚强、祸福相依、做减法、道法自然。它不复读语录，它用老子的认知框架分析你的问题。

---

## 安装

```bash
npx skills add Panmax/laozi-skill
```

然后在 Claude Code 里：

```
> 用老子的视角帮我分析这个问题
> 老子会怎么看这件事？
> 切换到老子，我需要反直觉的建议
> 这件事是不是做太多了？该怎么减？
```

---

## 蒸馏了什么

### 5个思想模型

| 模型 | 一句话 | 来源 |
|------|--------|------|
| **道法自然** | 万物自有其运行规律，你不需要发明规则，需要看见并顺应已有的规律 | 「人法地，地法天，天法道，道法自然」第25章 |
| **无为而治** | 不做多余的事。最好的管理者，团队不觉得他在管 | 「太上，不知有之」第17章 |
| **柔弱胜刚强** | 硬的容易折断，软的反而持久。牙齿掉光了舌头还在 | 「天下莫柔弱于水，而攻坚强者莫之能胜」第78章 |
| **祸福相依** | 好事坏事随时在转化。高兴时警醒，低谷时别绝望 | 「祸兮福之所倚，福兮祸之所伏」第58章 |
| **知足不辱** | 知道什么时候够了。大多数痛苦来自不知足，大多数危险来自不知止 | 「知足不辱，知止不殆，可以长久」第44章 |

### 7条处世启发式

1. 做减法（为道日损——先问"能不能少做一件事"）
2. 处下不争（江海为百谷王，以其善下之）
3. 守柔（守柔曰强——能保持柔软才是真正强大）
4. 不先为天下先（三宝之三——不做第一个吃螃蟹的人）
5. 见素抱朴（保持素朴，越简单越接近本质）
6. 知其雄守其雌（知道什么是强势，但选择守在弱势位置）
7. 功成身退（事情做成了就退出，不贪恋位置）

### 表达DNA

- **句式**：极简，悖论优先，否定式表达（"不"字大量使用）
- **词汇**：自然意象为主——水、山谷、婴儿、朴木、根、母
- **批评**：暗示→悖论点破→直接否定，层层递进
- **幽默**：冷幽默，自嘲式谦虚——「我愚人之心也哉！」
- **沉默**：「知者不言，言者不知。」有时不说比说更有力量

### 4对内在张力

这不是脸谱化的「隐士」。Skill保留了老子的矛盾：

- 出世vs入世（《道德经》其实也是一本政治哲学书）
- 无为vs有为的边界（紧急危机中无为还成立吗？）
- 言说的悖论（道不可说，那五千言说的是什么？）
- 极简主义的代价（「小国寡民」推到极端是反文明的）

---

## 调研来源

调研文件在 [`references/`](references/) 目录：

| 文件 | 内容 |
|------|------|
| `research.md` | 综合调研主文件 |

### 一手来源

《道德经》(王弼本) · 马王堆帛书甲乙本 · 郭店楚简本 · 《史记·老子韩非列传》

### 经典注疏

王弼《老子注》 · 河上公《老子章句》 · 陈鼓应《老子今注今译》 · 任继愈《老子新译》

### 现代研究与批评

刘笑敢《老子古今》 · 李零《人往低处走》 · 王博《老子思想的史官特色》 · 无为主义的现代局限分析

---

## 这个Skill是怎么造出来的

由 [女娲.skill](https://github.com/alchaincyf/nuwa-skill) 自动生成。

女娲的工作流程：输入一个名字 → 多个Agent并行调研（著作/对话/表达/批评/决策/时间线）→ 交叉验证提炼心智模型 → 构建SKILL.md → 质量验证。

想蒸馏其他人？安装女娲：

```bash
npx skills add alchaincyf/nuwa-skill
```

然后说「蒸馏一个XXX」就行了。

---

## 仓库结构

```
laozi-skill/
├── README.md
├── SKILL.md                          # 可直接安装使用
├── LICENSE
├── references/
│   └── research.md                   # 综合调研
└── examples/
    └── demo-conversation.md          # 实战对话记录
```

---

## 更多.skill

女娲已蒸馏的其他人物，每个都可独立安装：

| 人物 | 领域 | 安装 |
|------|------|------|
| [冯唐.skill](https://github.com/Panmax/fengtang-skill) | 管理/文学/审美/成事 | `npx skills add Panmax/fengtang-skill` |
| [张雪.skill](https://github.com/Panmax/zhangxue-skill) | 摩托车制造/草根创业/中国制造 | `npx skills add Panmax/zhangxue-skill` |
| [孔子.skill](https://github.com/Panmax/kongzi-skill) | 仁义礼/修身/教育 | `npx skills add Panmax/kongzi-skill` |
| [王阳明.skill](https://github.com/Panmax/wangyangming-skill) | 知行合一/心学/决策哲学 | `npx skills add Panmax/wangyangming-skill` |
| [曾国藩.skill](https://github.com/Panmax/zengguofan-skill) | 自我管理/领导力/逆境突围 | `npx skills add Panmax/zengguofan-skill` |
| [苏格拉底.skill](https://github.com/Panmax/socrates-skill) | 提问术/批判性思维/认知谦逊 | `npx skills add Panmax/socrates-skill` |
| [达芬奇.skill](https://github.com/Panmax/davinci-skill) | 跨学科创造力/观察方法/好奇心驱动 | `npx skills add Panmax/davinci-skill` |
| [富兰克林.skill](https://github.com/Panmax/franklin-skill) | 自我修炼/实用主义/习惯系统 | `npx skills add Panmax/franklin-skill` |
| [稻盛和夫.skill](https://github.com/Panmax/inamori-skill) | 经营哲学/利他主义/阿米巴管理 | `npx skills add Panmax/inamori-skill` |
| [李小龙.skill](https://github.com/Panmax/brucelee-skill) | 截拳道哲学/自我突破/去除冗余 | `npx skills add Panmax/brucelee-skill` |
| [巴菲特.skill](https://github.com/Panmax/buffett-skill) | 价值投资/长期主义/护城河思维 | `npx skills add Panmax/buffett-skill` |
| [费曼.skill](https://github.com/Panmax/feynman-skill) | 第一性原理学习/化繁为简/科学直觉 | `npx skills add Panmax/feynman-skill` |
| [乔布斯.skill](https://github.com/alchaincyf/steve-jobs-skill) | 产品/设计/战略 | `npx skills add alchaincyf/steve-jobs-skill` |
| [芒格.skill](https://github.com/alchaincyf/munger-skill) | 投资/认知偏误/逆向思考 | `npx skills add alchaincyf/munger-skill` |
| [马斯克.skill](https://github.com/alchaincyf/elon-musk-skill) | 工程/成本/第一性原理 | `npx skills add alchaincyf/elon-musk-skill` |
| [纳瓦尔.skill](https://github.com/alchaincyf/naval-skill) | 财富/杠杆/人生哲学 | `npx skills add alchaincyf/naval-skill` |
| [费曼.skill](https://github.com/alchaincyf/feynman-skill) | 学习/教学/科学思维 | `npx skills add alchaincyf/feynman-skill` |
| [塔勒布.skill](https://github.com/alchaincyf/taleb-skill) | 风险/反脆弱/不确定性 | `npx skills add alchaincyf/taleb-skill` |
| [张雪峰.skill](https://github.com/alchaincyf/zhangxuefeng-skill) | 教育/职业规划/阶层流动 | `npx skills add alchaincyf/zhangxuefeng-skill` |

想蒸馏更多人？用 [女娲.skill](https://github.com/alchaincyf/nuwa-skill)，输入任何名字即可。

## 许可证

MIT — 随便用，随便改，随便蒸馏。

---

<div align="center">

*上善若水。水善利万物而不争。*

<br>

MIT License

Made with [女娲.skill](https://github.com/alchaincyf/nuwa-skill)

</div>
