---
project_id: Project-0039
authorization_id: AUTH-20261013-016
previous_authorization_id: AUTH-20261013-015
updated: 2026-10-19
source_work_dates: ["2026-10-13", "2026-10-18"]
repair_date: 2026-10-14
source_sha256: b8e2b544ca3b8d9d2a9bb5d7798f440c59ec09bad29382bd243f31df07b4aa4f
cssclasses: [brain-note]
tags: [第二大脑, 科研文献]
intake_authorization_id: AUTH-20261013-016
last_intake_work_date: 2026-10-18
obsidian_policy: project_summary
ownership: user_project
---
# Sb-Te实测XRD图谱 · 摘要

> [!abstract] 当前记录状态
> 参考版已交付；原始ICDD表待补；10/12—18周总结部分覆盖。

## 最近一次核验的要点（2026-10-18）

- 从NBS Monograph 25 Section 3印刷页8的Sb₂Te₃三方相粉末表转录hkl/d/I数据，保存44行CSV
- Origin对照图绘制相对线强度≥1且计算角度位于实测5–85°范围内的29条参考线
- 三条实测曲线未改，交付可编辑Origin工程及PDF、PNG、TIFF、SVG。
- 本版标为NBS Monograph 25来源，不能称作ICDD/JCPDS 00-015-0874标准卡

## 验证边界

核验原始PDF哈希与来源记录一致、44行转录和29行绘图筛选条件通过；`"native_origin_reopen_and_data_readback": "passed"`，三条实测数据保持不变。`"status": "passed_with_nonblocking_poppler_font_warnings"`；PDF实际渲染页已检查，参考线清楚、无裁切与文字遮挡。弹出的字体替代提示非阻断，实际可见文字可读。`"source_rows": 44`；`"plotted_rows": 29`；`original ICDD/JCPDS 00-015-0874 remains unacquired.`

## 下一步

若需要与指定ICDD卡逐峰比较，由用户本人通过ICDD学生计划账号申请并选择卡片；收到原始卡后另建来源明确的对照版本，不覆盖本次NBS版本。没有原卡时，本版只作为NBS公开表对照。

来源：[已通过的工程记录](<C:/Users/Administrator/Desktop/workspace/Projects/Project-0039-Sb-Te实测XRD图谱/07-复盘与日志/Sb-Te实测XRD图谱 · 2026-10-18工作总结.md>)；旧版本、历次交付与周记录在下方完整保留。

> [!history]- 历次工作与原始入库记录（追溯时展开）
> 
> <!-- DAILY-INTAKE-BEGIN -->
> > [!abstract] 最近工作与边界 · 2026-10-18
> > NBS公开表新增44行转录数据与29条参考线；实测曲线未改，ICDD原卡仍未获取，不据此作物相结论。
> > 当前研究归属（10月15日确认）：本人做碲化铋，旧Sb–Te属师兄体系；历史论文、参数和图谱保留原材料标签，不改成本人碲化铋实验结果。 [[跨项目记忆/02-项目/Project-0022-阵列与多孔表面热电文献/阵列与多孔表面热电文献 · 摘要|研究总览与来源]]
> 
> ## 逐日成果、决定与下一步
> 
> ### 2026-10-13工作 · 2026-10-16入库
> 
> **目标：**把2 h、3 h、6 h三份实测XRD绘成可继续编辑的Origin工程，并补上用户确认的底轴参考棒图。
> 
> **完成结果：**三份XY各7999点，范围5.01–84.99°、步长0.01°；图中采用显式归一化与错位，不平滑或扣背景。输入原件保留在原路径，项目内保存同内容副本及配套 XRDML 元数据。所有线条、字体、坐标和标签均为 Origin 原生对象。最终采用文件名含“标准谱平铺”的OPJU、PNG和PDF。
> 
> **关键决策：**初版缺参考棒线后，依据Wu2022 Fig.1中的JCPDS 00-015-0874数字化参考峰补充；按语音确认改为底部独立竖棒。标准棒线独立地从底部轴向上绘制，连接横线和分隔线已移除；实测与参考值不变。
> 
> **验证与边界：**10月13日保存的delivery、reopen、standard-reference和flat-reference报告记录原生工程重开、可编辑性及Origin/PNG/PDF检查通过，本日整理只回查已有记录。参考峰来自论文图片数字化，估计角度误差约0.12°；原始ICDD卡片表未取得，不能用于精确匹配或定量分析。
> 
> **问题与改进：**用户两次纠正图底参考样式：缺失参考棒图和仍有连接/分隔横线。最终以确认的平铺样式验收，不能再把早期版本当最新版。
> 
> **待办与下一步：**实际使用从“标准谱平铺”工程继续编辑；若要精确物相判定、单相结论或定量，先取得可靠原始峰表或晶体结构并核验，不由当前参考图直接作结论。
> 
> [工作台通过的项目总结](<C:/Users/Administrator/Desktop/workspace/Projects/Project-0039-Sb-Te实测XRD图谱/07-复盘与日志/Sb-Te实测XRD图谱 · 2026-10-13工作总结.md>) · [工作台核验回执](<C:/Users/Administrator/Desktop/workspace/Projects/Project-0005-Codex全局治理体系/06-质量检查/每日归位回执-2026-10-13.json>)
> 
> 总结SHA-256：`9479367991dc62c138b9c55575b898a0b4fb9314770013a53efa6e9f5f8745af`；收录授权：AUTH-20261013-016；规则：`project_summary`。
> 
> <!-- DAILY-INTAKE-END -->
> ### 2026-10-18工作 · 2026-10-19入库
> 
> #### 实际工作与结果
> 从NBS Monograph 25 Section 3印刷页8的Sb₂Te₃三方相粉末表转录hkl/d/I数据，保存44行CSV；按Cu波长1.5405 Å和一阶Bragg关系计算2θ。Origin对照图绘制相对线强度≥1且计算角度位于实测5–85°范围内的29条参考线，<1记录保留在CSV且未当作0。三条实测曲线未改，交付可编辑Origin工程及PDF、PNG、TIFF、SVG。
> 
> #### 决策、归属与限制
> 本版标为NBS Monograph 25来源，不能称作ICDD/JCPDS 00-015-0874标准卡；不据此声称样品相判定或精修结果。该Sb–Te体系属于师兄独立体系，与本人当前Bi₂Te₃研究分开记录。ICDD/JCPDS原始卡片尚未获取；若需逐峰比较，应由用户取得原卡后另建来源明确的版本，不覆盖NBS版本。
> 
> #### 验证与来源
> 固定工作台核验通过，数据转录、筛选条件、三条实测曲线不变及Origin重开回读均有记录；PDF字体替代提示为非阻断且页面可读。主来源：`C:/Users/Administrator/Desktop/workspace/Projects/Project-0039-Sb-Te实测XRD图谱/07-复盘与日志/Sb-Te实测XRD图谱 · 2026-10-18工作总结.md`（SHA-256 `f57e80e6e2383acd4b405ba9548163089ee9e21d52e2ffb4044cc3bc722304ab`）；工作台回执 `C:/Users/Administrator/Desktop/workspace/Projects/Project-0005-Codex全局治理体系/06-质量检查/每日归位回执-2026-10-18.json`（SHA-256 `0eb6f1154d4069c8799755fc2219c278e9cc614c509d52d72f3ebe4245cbbd5d`）。
> ## 入库前记录（保留原时间与适用边界）
> 
> > [!abstract] 当前结论
> > 三份2 h、3 h、6 h实测谱已整理为Origin原生可编辑图；最新版本为“标准谱平铺”。每份7,999点全部保留，归一化及错位用于比较峰位和相对峰形。参考棒线是文献图数字化，不能确认单相或代替ICDD原表。
> 
> ## 完成结果
> 
> 三份 2 h / 3 h / 6 h 实测 XY 数据在本机 OriginPro 2024 中绘制。主图为完整角度范围的归一化错位叠加图；OPJU 内同时保存原始强度及显式变换。最新采用文件名含“标准谱平铺”的版本：标准棒线独立地从底部轴向上绘制，连接横线和分隔线已移除。
> 
> 每份保留全部7,999点，2θ为5.01–84.99°、步长0.01°；各自最大强度归一化到100，上移量为0、120、240。未平滑、扣背景、插值或排除数据，图中纵向位置及峰高不能比较原始绝对强度。A列为角度，B–D为原始强度，E–G为归一化强度，H–J为展示强度，保留显式列公式及可编辑的原生曲线和标签；时间标签沿用文件名，不推定工艺阶段。
> 
> ## 证据与限制
> 
> Sb₂Te₃参考棒线来自Wu等2022年论文Fig.1，图上卡号为JCPDS 00-015-0874；提取28条可识别棒线，角度保守精度约0.12°。原始ICDD卡片表未取得，不能用于精确匹配或定量分析。多个实测强峰未与参考图完全重合，不能据此确认单相Sb₂Te₃，也不能直接用于晶面归属或Rietveld定量。
> 
> 工程当时已有原件哈希、Origin逐值回读、工程重开与编辑、PNG/PDF视觉检查记录。本次修复核验的是摘要正文、来源哈希及链接，未重新绘图或重复图像验收。
> 
> ## 继续入口
> 
> [最新可编辑Origin工程](<C:/Users/Administrator/Desktop/workspace/Projects/Project-0039-Sb-Te实测XRD图谱/05-交付物/Sb-Te_XRD_2h-3h-6h_标准谱平铺.opju>) · [平铺版说明](<C:/Users/Administrator/Desktop/workspace/Projects/Project-0039-Sb-Te实测XRD图谱/05-交付物/标准谱平铺说明.md>) · [原始数据与变换说明](<C:/Users/Administrator/Desktop/workspace/Projects/Project-0039-Sb-Te实测XRD图谱/05-交付物/图谱说明.md>) · [参考谱来源与精度](<C:/Users/Administrator/Desktop/workspace/Projects/Project-0039-Sb-Te实测XRD图谱/05-交付物/标准谱对照说明.md>) · [历史核验记录](<C:/Users/Administrator/Desktop/workspace/Projects/Project-0039-Sb-Te实测XRD图谱/06-质量检查/flat-reference-verify.json>)。
> 
> 下一步：若要精确判相，先取得原始标准卡表或可靠晶体结构数据，再建立匹配依据；参考图保持原始位置，不为迎合样品移动峰位。
> 
> 来源聊天：`01a134e2-df2a-7811-9f50-7503f3353375`。
> 
> ## 来源与授权
> 
> 工作日期：2026-10-13；正文修复日期：2026-10-14。工程来源：[README](<C:/Users/Administrator/Desktop/workspace/Projects/Project-0039-Sb-Te实测XRD图谱/README.md>)；原件继续留在工作台。来源SHA-256：`b8e2b544ca3b8d9d2a9bb5d7798f440c59ec09bad29382bd243f31df07b4aa4f`。
> 
> 本次修复依据[[跨项目记忆/03-归档/原始资料/Project-0005/日常归位与分类入库 · 用户确认（2026-10-13）|日常归位与分类入库用户确认]]（AUTH-20261013-016）；既有内容的授权定位保留在[[跨项目记忆/03-归档/原始资料/Project-0019/Obsidian第二大脑 · 近期对话补录授权原文（2026-10-13）|近期补录授权原文]]（AUTH-20261013-015）。本次是受控正文修复，不提交日／周成功检查点。
> 
> [[跨项目记忆/02-项目/Project-0039-Sb-Te实测XRD图谱/Sb-Te实测XRD图谱|Sb-Te实测XRD图谱 · 项目入口]]
> 
> <!-- WEEKLY-RECEIPT:2026-10-12至2026-10-18:Project-0039 -->
> ## 周总结 · 2026-10-12—2026-10-18（部分覆盖）
> 
> # Sb-Te实测XRD图谱 · 周总结（2026-10-12—2026-10-18）
> 
> 本周的归位、阅读或历史成果核验，均按原记录的工作性质叙述；归档不等于本周新开展实验。
> 
> ## 目标
> 
> 保持师兄Sb–Te实测曲线与参考来源的可编辑、可追溯关系。
> 
> ## 完成结果
> 
> 本周先保存三份各7999点实测曲线的Origin原生图及论文图片数字化参考；18日新增NBS公开粉末表44行CSV、按Cu波长1.5405 Å筛选绘制29条参考线，三条实测不变，原生重开与数据回读通过。
> 
> 已核验的来源事实：
> 
> - "plotted_rows": 29
> - "native_origin_reopen_and_data_readback": "passed"
> - ICDD/JCPDS 00-015-0874 remains unacquired
> 
> ## 关键决策
> 
> 论文图数字化与NBS表分别标明来源；NBS不冒称ICDD/JCPDS 00-015-0874原卡，参考强度不与实测计数定量比较。
> 
> ## 验证与边界
> 
> 原卡未取得；先前数字化角度误差约0.12°。NBS版非阻断字体提示与页面可读性分开记录，不据此作相判定、精修或单相结论。 本周只覆盖已取得回执的6/7日；缺2026-10-12，不称全周完整覆盖。后续日期的新状态不在本周内，也不被本周记录回退。
> 
> ## 问题与改进
> 
> 初版参考棒线样式和原卡缺失已分别处置，仍不能把替代来源当原卡。
> 
> ## 待办与下一步
> 
> 继续编辑时用对应来源版本；需精确物相或定量时补可靠原峰表/晶体结构并另立版本。
> 
> ## 来源
> 
> 通过的项目日总结日期：2026-10-13、2026-10-18；完整定位及哈希见[Sb-Te实测XRD图谱 · 周总结来源摘录-2026-10-12至2026-10-18.md](<C:/Users/Administrator/Desktop/workspace/Projects/Project-0039-Sb-Te实测XRD图谱/04-过程文件/Sb-Te实测XRD图谱 · 周总结来源摘录-2026-10-12至2026-10-18.md>)。本周为来源复盘，没有新增实验或重做原应用验收。
> 
> 
> 工程周总结：[Sb-Te实测XRD图谱 · 周总结-2026-10-12至2026-10-18.md](<C:/Users/Administrator/Desktop/workspace/Projects/Project-0039-Sb-Te实测XRD图谱/07-复盘与日志/Sb-Te实测XRD图谱 · 周总结-2026-10-12至2026-10-18.md>)；SHA-256：`8a59fbfc6c2ab017a54177312d00bfd76641d5a422dc9567369d236f016f73e2`。授权：AUTH-20261013-016。
