# LEDGER — Collie（方法论与构想库）

## NOW
- (空)

## NEXT
- owner 逐条拍板 CAO-31 决策清单(人的活)→ 拍板后派「结论追加回写 Collie-项目初想.md」任务 → 再启动阶段三(架构选型)批次
- T4 Orca 接入主攻项目（ai_financial），练熟"一任务一 worktree + 分支名带任务号"（阶段一）
- T6 每周日复盘机制首次完整运转：翻四项目 LEDGER + 重排分级 + 填工具观察笔记
- T7 点子库建立（封存想法的统一去处，《现状盘点》提到但未落地）
- T10 本仓库 git init + 首次提交（文档也是资产，目前零保护）
- T11 Multica 进阶：BUFN 分支合并后试"agent 自调 multica CLI 更新 issue"、评估 Squads/Autopilots（阶段三胶水前置）

## DONE
- 2026-11-19 | 展示规范化 | README 改为双语项目主页:补英文首屏/徽章/文档导航,保留中文定位与文档地图;仓库更名为 Collie-Multi-Agent-Playbook 并补齐元数据 | 本仓库自提交(见 git log) | README 本地链接检查通过;未改动其他文档与产品构想
- 2026-07-31 | owner 指令 | docs/ 目录建立并规范落盘:CAO-31 决策清单→`docs/decisions/`、CAO-32 三份竞品笔记→`docs/research/`,新增 `docs/README.md` 索引;README/AGENTS.md 职责边界与规则 1 同步(owner 拍板:交付物进 git) | 本仓库自提交(见 git log) | 文件清单:docs/README.md、docs/decisions/2026-07-31-开放问题决策清单.md、docs/research/2026-07-31-{herdr,orca,multica}.md
- 2026-07-31 | CAO-30 | 构想澄清期第一批(阶段一/二并行)验收:CAO-31 决策清单(owner 已「通过审核」)+ CAO-32 三份竞品笔记,证据齐全(收工评论+LEDGER 回写+commit),父 issue 转 in_review 待 owner 复核 | 本仓库自提交(见 git log) | 子 issue 交付全文见 CAO-31/CAO-32 评论;下一步待 owner 拍板决策清单
- 2026-07-31 | CAO-27 | Collie 头像定稿:owner 拍板方向 A「哨兵」;design-language.md v0.1 与头像源文件(主稿+深底/浅底/单色/favicon 变体)落盘 design/ | `2877024` | 五版 PNG 已目检,favicon 64px 缩略可辨;效果图见附件(issue CAO-27 评论)
- 2026-07-31 | CAO-32 | Herdr/Orca/Multica 竞品深度拆解(三份笔记:产品速览+核心机制拆解+值得抄+要避开的坑+两个差异化洞察差距判定),按「改旧不建新」以 issue 评论交付(每份一条评论) | 本仓库自提交(见 git log) | issue CAO-32 评论有三份笔记全文,取证:官方文档/GitHub API/本机 multica CLI 实证,事实均带源链接
- 2026-07-31 | CAO-31 | 开放问题决策清单(7 条:计划内 6 + 计划外新增 1),逐条给候选选项+权衡+建议倾向,按「改旧不建新」以 issue 评论交付 | 本仓库自提交(见 git log) | issue CAO-31 评论有清单全文
- 2026-07-31 | CAO-26 | Collie 小队初步团队计划（五阶段草案：构想澄清→竞品调研→架构选型→spike 预研→文档沉淀），按「改旧不建新」以 issue 评论交付，落盘位置待 owner 拍板 | 本仓库自提交（见 git log） | issue CAO-26 评论有计划全文
- 2026-07-30 | T5 | Multica Cloud 最小环跑通（BUFN 试点）：建 issue CAO-4 → assign kimi-worker → daemon 隔离 worktree 执行 → 自验 → in_review | BUFN `cf0f762`（分支 agent/kimi-worker/232a4ea5 已推送待合并） | npm run build 通过、issue 评论有冷启动报告
- 2026-07-30 | T9 | AGENTS.md 修正：职责边界表指向 LEDGER-规范.md、新增本仓库台账行、已知坑同步现状 | — | 已目检
- 2026-07-30 | T8 | 交叉引用修正：现状盘点中失效的《通用工作模式》改为文件名引用 | — | 已目检
- 2026-07-30 | T3 | 目录规范化：立三件套，LEDGER 规范改名 LEDGER-规范.md 消除冲突 | — | 已目检
- 2026-07-30 | T2 | 通用工作流 + 现状盘点 + 工具观察笔记成文，LEDGER 规范定稿 | — | —
- 2026-07-29 | T1 | Collie 项目初想成文（基石文档） | — | —
