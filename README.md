# job-fit-compass

岗位匹配度分析 + 求职机会匹配 + 简历优化（WorkBuddy 用户级 Skill）。

> 一个把"诊断能力差距 → 规划学习路线 → 搜靠谱岗位避坑 → 基于 JD 用 STAR 优化简历"串成闭环的求职全流程工具。名字取自 compass（指南针）：既帮你定位方向，也帮你避开坑。

## 简介 / Description

**中文**
job-fit-compass 是一款面向求职者的岗位匹配分析技能。输入简历后，它先定位合适的职位区间供你选择，再抓取真实 JD 做深度分析，生成交互式五页 HTML 报告：①职责×知识点匹配；②岗位知识全景；③提升建议（差距热力图＋真实学习资源）；④求职机会（反向验证真实链接、按匹配度/规模/截止时间排序、公司风险核查）；⑤STAR 法则简历优化。风险核查聚焦成立时间、社保人数、劳动仲裁及其他风险，数据缺失标注"待核"，全程不编造。

**English**
job-fit-compass is a job-fit analysis skill for job seekers. After you input your resume, it first locates a range of suitable positions for you to choose from, then fetches the real JD for in-depth analysis and produces an interactive 5-tab HTML report: ① duty×knowledge mapping; ② full knowledge landscape; ③ improvement plan (gap heatmap + real learning resources); ④ job opportunities (reverse-verified links, sorted by match/scale/deadline, company risk check); ⑤ STAR-based resume optimization. Risk checks focus on founding date, social-security headcount, labor arbitration and other risks; missing data is flagged as "Pending review", with no fabrication.

## 功能

输入 **JD + 背景**，或提供 **简历**，生成 5 页 Tab 式单文件 HTML 报告：

- **匹配**：职责 × 知识点映射（落到函数/动作级，不水），四色掌握度（已会/需补/加分/软技能）
- **知识**：岗位知识全景（6 张硬技能卡 + 5-6 张软技能卡，每张含"现在就能练"的学生场景）
- **提升**：两遍差距分析 → 差距优先热力图（Critical/High/Medium/Low）→ 带真实学习资源的学习计划 → 学习顺序表 → 3 个月路线图
- **求职**：基于简历搜持牌平台岗位（反向验证只放官网/BOSS/智联等真实链接、按匹配度/规模/截止时间排序、公司风险聚焦成立时间/社保人数/劳动仲裁/其他风险并尽力核查）
- **简历**：基于 JD 用 STAR 法则重写经历，输出可一键复制的优化版简历（缺口诚实占位、量化不编造）

## 两种模式

- **JD + 背景模式**：直接发岗位职责 + 你的专业/课程/技能/证书/经历，一步出报告。
- **简历模式（交互式两段）**：发简历 + 意向方向/城市 → 先搜出"职位区间"让你挑 → 你选定岗位后，再拉该岗位真实 JD 出深度报告与 STAR 优化简历。

## 安装

把本目录复制到：

- 用户级（推荐）：`~/.workbuddy/skills/job-fit-compass/`
- 或项目级：`<项目>/.workbuddy/skills/job-fit-compass/`

## 依赖

- 解析 `.docx` 简历需 `pip install python-docx`
- 搜岗位 / 风险核查 / 查学习资源需联网（WebSearch）

## 免责声明

风险数据来自公开渠道（企查查/天眼查/裁判文书网等），可能滞后或不全，仅作辅助判断；简历优化模块不伪造经历或量化数据。
