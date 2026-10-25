## X 上 RSI 进展速览（HenryL_AI 及相关圈）

**日期**：2026-10-25 Asia/Shanghai  
**方法**：X 公开读取（`get_users_*` / `search_posts_all`）；不读论文 PDF 正文。  
**口径**：只写帖子里可核验的主张；宣传数字以当事人帖为准，未独立复现。

## Henry Lu（@HenryL_AI）

- Bio：Research Lead @Amazon；Self-improving AI；ex-CMU / MSFT Research；Co-Lead @OpenRSI  
- ~787 followers（读档时）

### 近期主张（按时间）

| 北京时间约 | 要点 | 链接 |
|---|---|---|
| 2026-10-23 | 点评 Mirendil/Recursive：agent 写了 >99% 代码，但瓶颈是「决定跑哪些实验」 | https://x.com/HenryL_AI/status/2113661320411353425 |
| 2026-10-23 | Article：Flint & Mirendil-Base 里 AI 实际做了什么 | https://x.com/HenryL_AI/status/2113368498080719134 |
| 2026-10-21 | 称 Mirendil 3.5 月预训练 500B 为 RSI milestone；挂钩 LM2LM | https://x.com/HenryL_AI/status/2113005818715283892 |
| 2026-10-20 | **LM2LM**：用 RL 训 27B 提出更好的 LM 改进提案；引用 companion「AI Research World Model」 | https://x.com/HenryL_AI/status/2112337614049366102 |
| 2026-09-24 | 共领 OpenRSI：批评「便宜重试尺度」上的 RSI 评测；真问题在单 trial ~20K GPU-hour | https://x.com/HenryL_AI/status/2102844593251471453 |
| 2026-08-21 | 两篇 self-improving agents 录 EMNLP 2026；代码在 **A-Evolve**（Harness Updating ≠ Benefit；Evo-Harness） | https://x.com/HenryL_AI/status/2090830907854963052 |

**他的 RSI 角度**：偏「研究环 / 提案质量 / 高成本评测」与 harness 进化（A-Evolve），不是聊天客户端 RSI。

## 关联人物与机构（近 4–6 周硬信号）

| 账号 | 角色线索 | 近进展（帖内） | 代表帖 |
|---|---|---|---|
| @OpenRSI | 基金会；开放 RSI 评测/环境 | 2026-09-23 OpenRSI-Index v0.1 / Marin；2026-10-07 三枚 agent 优化 PR 合入 SGLang-Omni；Harness：Experiment→Submit→Evaluate→Improve | https://x.com/OpenRSI/status/2107945219199230157 · 启动帖见 Henry quote |
| @mirendil | 使命写 RSI；种子轮叙事 $200M（创始人帖） | 2026-10-21：无预训练团队的规模预训练；1 人+agents、3.5 月、100B–500B 量级（Henry/当事人叙事） | https://x.com/mirendil/status/2112967808858648871 |
| @Recursive_SI / @RichardSocher / @jeffclune | Recursive；Eureka Machine | 2026-10-21 **Flint**：本地快速 coding 模型；自称 Eureka 参与栈多环节；<4 个月 | https://x.com/RichardSocher/status/2112944385415426249 |
| @MillionInt | Core Automation；ex-OpenAI VP RL | Henry 8 月文：离开前沿实验室赌 RSI 的三条路径之一 | https://x.com/HenryL_AI/status/2085391742061441071 |
| @hillclimbai / @jparkjmc | DeepRSI 评测数据 | 2026-10：DeepRSI（真人 ML 研究环境任务）；招人做 RSI evals | https://x.com/jparkjmc/status/2114044750642979319 · 综述 https://x.com/anshuman1/status/2114121172413743416 |

## 主题归纳（X 当前舆论）

1. **预训练环自动化**：Mirendil / Recursive Flint ——「少人 + agent 写代码/搜配方」被当成 RSI 里程碑叙事。  
2. **提案质量 > 代码占比**：Henry 反复强调 bottleneck 是选实验 / 评提案（LM2LM）。  
3. **开放评测基建**：OpenRSI-Index、DeepRSI ——「仪表盘」层；强调高成本尺度与 maintainer 门控。  
4. **Harness 自改进仍在学术线**：Henry 的 A-Evolve / EMNLP 线与「造 frontier 模型」创业线并行，勿混为一谈。  
5. **标签通胀**：有研究者（如 @giffmana 线程语境）对把小改进叫 RSI 表示厌烦——需分清 harness 补丁 vs 模型研发环。
