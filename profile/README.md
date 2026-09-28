<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/logo-avatar.png">
  <img src="assets/logo.png" alt="CourseLingo 课语 · 译课 AI" width="132">
</picture>

# CourseLingo · 译课 AI

**AI-powered translation & explanation for classic CS courses.**

### 让经典 CS 课程，跨语言也能学懂。

</div>

---

## 这是什么

CourseLingo 用 AI 把经典的计算机科学课程翻译并讲解成中文。

课程之外，还有课程**围绕的对象**：经典论文。MIT 6.824 的一半内容就是 MapReduce、GFS、Raft、Paxos —— 所以我们把论文也当成一等公民：**每篇论文单独核实授权**，能翻译就翻译，不能就写我们自己的导读。论文的版权通常在出版社手里，跟课程授权完全是两回事，不能想当然。

不是把字幕机翻一遍就算了 —— 而是**带着上下文的讲解**：先建课程术语表保证全篇一致，再补概念前置、拆解推导过程、给代码加注释。目标是让中文读者**真正学懂**，而不是**勉强读完**。

英文原版的表达习惯、术语密度和默认知识背景，是中文学习者的真实门槛。我们做的就是拆掉这道门槛。

## 现状

> **Phase 1 · 内容生产**
> 平台与流水线已就绪：授权闸门、术语表、配图房规、文风机检都能在 CI 里拦截。
> MIT 6.824 已产出 3 讲讲解与 2 篇论文导读，正在继续推进。

## 课程路线图

| 课程 | 学校 | 主题 | 语言 | 状态 |
| --- | --- | --- | --- | --- |
| [MIT 6.5840 / 6.824](https://pdos.csail.mit.edu/6.824/) | MIT | 分布式系统 | EN → ZH | **施工中** |
| [CS 61A](https://cs61a.org/) | UC Berkeley | 计算机程序的构造与解释 | EN → ZH | ⛔ **明确不做**（版权保留） |

候选课程（待排期，**每门都要先逐材料核实授权**）：

| 课程 | 学校 | 主题 | 授权状态 |
| --- | --- | --- | --- |
| [MIT 6.1810 / 6.S081](https://pdos.csail.mit.edu/6.S081/) | MIT | 操作系统 | ⚠️ 未确认（与 6.824 同：主页有 CC BY 徽章，讲义未单独取证） |
| [CMU 15-445](https://15445.courses.cs.cmu.edu/) | CMU | 数据库系统 | 🔴 未声明 = 保留所有权利 |
| CS 144 | Stanford | 计算机网络 | ⚠️ 混合：站点未声明，实验禁发解答 |
| MIT OCW 系列 | MIT | 各科 | 🟡 CC BY-NC-SA 4.0（可改编，禁商用，SA 传染） |

## 仓库

| 仓库 | 用途 |
| --- | --- |
| [`.github`](https://github.com/courselingo/.github) | 组织主页与社区规范 |
| [`courselingo`](https://github.com/courselingo/courselingo) | 平台主仓库：架构、术语规范、翻译流水线、写作与配图规范 |

## 我们的原则

- **讲懂优先于译完** —— 术语一致、上下文完整，宁可慢，不可糊。
- **尊重原作者与授权** —— 逐课程、**逐材料**核实后才动手。MIT 6.824 的 CC BY 3.0 US 徽章**只出现在课程主页**，讲义文件本身没有任何许可声明，覆盖范围**未确认** —— 因此这门课我们只发布**自己撰写的讲解**，不产出逐字稿，也不做双语原文对照。**UC Berkeley CS 61A** 声明版权归 Regents of the University of California 所有，我们**明确拒绝**这门课的翻译请求，而不是先发了再说。原始课件与视频一律指向官方来源。
- **中英对照，可溯源** —— 每段讲解都能对回原始出处。
- **AI 生成，人工负责** —— AI 产出须经术语校验与人工抽检后才算完成。

## 参与

现阶段欢迎讨论架构、术语表与课程选型。请先阅读 [`CONTRIBUTING.md`](./CONTRIBUTING.md)，也请留意各课程的授权限制 —— 侵权风险是这个项目最大的敌人。

---

<div align="center">
<sub>CourseLingo · 译课 AI — 让经典 CS 课程，跨语言也能学懂。</sub>
</div>
