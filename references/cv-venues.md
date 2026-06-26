# Computer Vision 期刊 Cover Letter 要点

## 核心发现：顶会 vs 期刊

| 类型 | 代表 venue | 需要 Cover Letter？ |
|------|-----------|-------------------|
| **顶会** | CVPR, ICCV, ECCV, NeurIPS, ICML, ICLR, AAAI | **不需要** — 用 OpenReview，只交论文 |
| **期刊** | TPAMI, TIP, IJCV, IJCV, Pattern Recognition, Neural Networks | **需要** — 编辑初审第一关 |

所以这个 skill 主要服务的是 **IEEE TPAMI、TIP、IJCV** 等期刊投稿。

---

## IEEE TPAMI Cover Letter 四大要素

来源：manusights.com/blog/ieee-transactions-on-pattern-analysis-and-machine-intelligence-cover-letter

### 1. 确认 scope fit
- 必须说明为什么是 TPAMI 的 scope，而不是 TIP 或 TMI
- TPAMI = pattern analysis + machine intelligence（更偏方法论）
- TIP = image processing（更偏应用）
- 一句话说清楚："This contribution addresses [X] at the pattern-analysis level, distinguishing it from image-processing-focused work in TIP."

### 2. 披露会议扩展（最关键！）
- 如果是从 CVPR/ICCV/ECCV 扩展来的，**必须**在 cover letter 里声明
- 说明新增了什么：30%+ 新方法、新消融实验、新理论分析
- 格式："This paper extends our conference paper [Citation]. The journal version adds [specific new contributions]."
- IEEE 会用 iThenticate 查重，不披露 = 学术不端

### 3. 推荐审稿人
- 3-5 个无利益冲突的审稿人
- 不能是近期合作者、同一机构、导师
- 应该是了解你的方法或 benchmark 的人

### 4. 必要声明
- 原创性声明
- 非一稿多投
- 全体作者同意
- 利益冲突声明

---

## IJCV Cover Letter 要点

来源：manusights.com/blog/international-journal-of-computer-vision-submission-guide

- IJCV 期望 journal 版本有**实质性的期刊级贡献**，不能只是会议论文加了几个实验
- Cover letter 必须 map 旧贡献 → 新贡献
- 需要说清楚新增了哪些理论/算法/实验/应用层面的 advance
- 首轮编辑筛查很严格，看不到期刊级贡献 = desk reject

---

## IEEE TIP Cover Letter 要点

- 比 TPAMI 更偏应用和图像处理
- 如果你的工作偏方法论（pattern analysis），应该投 TPAMI
- 如果偏具体图像处理任务（去噪、超分、压缩感知），投 TIP
- Cover letter 需要说明为什么是 TIP 而不是 TPAMI

---

## CS/视觉领域期刊 Cover Letter 通用模板

```
Dear Editor,

[PARAGRAPH 1: 核心发现 + 技术贡献 — 2-3 句]
直接报结果。如果是从会议扩展来的，第一段就要说清楚。

[PARAGRAPH 2: 为什么是这个期刊 — 1-2 句]
- TPAMI: "This contribution addresses [X] at the pattern-analysis level, 
  distinguishing it from image-processing-focused work in TIP."
- TIP: "This work targets [specific image processing task], which aligns 
  with TIP's scope on [specific scope phrase]."
- IJCV: "This paper advances [area] beyond our prior conference version 
  [Citation] by [specific new contributions]."

[PARAGRAPH 3: 会议扩展声明（如果适用）— 1-2 句]
"This paper extends our conference paper [Full Citation]. The journal version 
adds [specific new methodology/ablations/theory], representing approximately 
[X]% new material beyond the conference version."

[PARAGRAPH 4: 贡献点 — 3-5 条]
每条：痛点 → 方案 → 结果（带数字）

[PARAGRAPH 5: 声明]
All authors have approved this submission. This manuscript is original, has not 
been published previously, and is not under consideration elsewhere. There are 
no conflicts of interest to declare. [If applicable: This paper extends our 
conference work [Citation].]

[推荐审稿人 — 3-5 个]
We suggest the following potential reviewers:
- [Name], [Affiliation] — [reason]

Sincerely,
[Corresponding author]
[Affiliation]
```
