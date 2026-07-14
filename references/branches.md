# 分支详细步骤

> 被 SKILL.md 引用。SKILL.md 只保留分支索引，详细步骤在此。

## 分支 1：抑郁/情绪低落/低自尊

用户说"抑郁/难受/快感缺失/觉得自己很差/没希望了"。

**即时工具来源：** references/depression.md
**深度资料来源：** huberman/01, huberman/04, huberman/11, books/feeling-good.md, books/emotional-first-aid.md, books/The Better Brain.md, books/zebras.txt, books/dopamine-nation.md

步骤：
1. 安全确认：自杀念头？→ 走 crisis-resources.md
2. 定位认知扭曲：帮用户写出脑中自动冒出来的话 → 从 depression.md 的 10 种扭曲中匹配
3. 选工具：简版三栏技巧
4. 如果行动力归零：切到 attention.md 的最小行动法
5. 如涉及认可/爱/工作价值 → depression.md 的认可成瘾部分 → 完成标准：用户能区分"渴望"和"需要"
6. 完成标准：用户情绪下降 ≥ 2 分（0-10），或说"好一些了"

## 分支 2：反刍/侵入性思维/内疚/愤怒

用户说"停不下来/反复想同一件事/控制不住/内疚/气得不行"。

**即时工具来源：** references/rumination.md
**深度资料来源：** huberman/02, books/emotional-first-aid.md Ch5, books/feeling-good.md Ch7-8, books/mindful-way.txt, books/The Power of Now.md

步骤：
1. 评估情绪强度（0-10）：
   - ≥ 7 → 先去 rumination.md 的 5-4-3-2-1 或冷刺激
   - 4-7 → 定时担忧法或自离视角
   - < 4 → 反刍重构三问或正念接纳
2. 如果是愤怒反刍 → rumination.md 的愤怒部分
3. 如果是内疚 → rumination.md 的内疚部分
4. 完成标准：用户情绪下降 ≥ 1 分，或能说出一个反刍对应的认知扭曲

## 分支 3：注意力涣散/拖延/完美主义

用户说"集中不了/不想动/不知道做什么/做得不够好"。

**即时工具来源：** references/attention.md
**深度资料来源：** books/feeling-good.md Ch5, books/Atomic Habits.md, huberman/03, huberman/05, huberman/06

步骤：
1. 从 attention.md 选一个即时工具：
   - 完全不动 → 反拖延表（预测 vs 实际）
   - 有一点动力 → 碎步法（≤15 分钟）
   - 想系统改善 → 每日活动计划表
2. 如果是完美主义卡住 → attention.md 的反完美主义表 + 开心预测法
3. 完成标准：用户做了一件 ≥ 2 分钟的事，或定了一个可执行的最小行动

## 分支 4：失眠/作息乱

用户说"睡不着/睡不好/昼夜颠倒"。

**即时工具来源：** references/sleep.md
**深度资料来源：** huberman/08, huberman/09, huberman/10, huberman/11, books/The Better Brain.md

步骤：
1. sleep.md 选工具：
   - 今晚睡不着 → 黑暗环境 + 温度控制 + NSDR
   - 长期改善 → 早晨光照 + 睡眠一致性 + 咖啡因管理
2. 完成标准：用户今晚会做一件改善睡眠的事

## 分支 5：多巴胺成瘾/自慰/刷手机/游戏

用户说"控制不住自慰/一直刷手机/停不下来/需要找刺激"。

**即时工具来源：** references/dopamine.md
**深度资料来源：** books/Dopamine Nation.md, huberman/06, huberman/07, huberman/01, books/Atomic Habits.md

步骤：
1. 先不批判——这属于多巴胺调节问题，不是道德问题
2. 从 dopamine.md 选工具：
   - 即时 → 识别触发场景 + 准备替代行为
   - 短期 → 多巴胺斋戒（每天 1-4 小时无手机）
   - 长期 → 多巴胺菜单 + 冷暴露
3. 完成标准：用户制定了一个可执行的替代行为（"当 X 发生时，我做 Y"）

## 分支 6：社交创伤/被拒绝/孤独/批评敏感

用户说"被拒绝了/很孤独/怕被批评/社交焦虑"。

**即时工具来源：** references/social.md
**深度资料来源：** books/emotional-first-aid.md, books/feeling-good.md Ch6, huberman/04

步骤：
1. social.md 匹配问题类型
2. 执行对应急救方案
3. 完成标准：用户做了一件重新建立社交连接的事

## 分支 7：压力/焦虑

用户说"压力大/焦虑/心慌/绷得太紧"。

**即时工具来源：** references/stress-anxiety.md
**深度资料来源：** books/zebras.txt, huberman/19, huberman/04, books/The Power of Now.md, books/emotional-first-aid.md

步骤：
1. 如果焦虑发作 → 生理叹息（吸→再吸→慢呼）× 2-3 次，或冷水洗脸
2. stress-anxiety.md 选长期工具
3. 如果是丧失/创伤 → stress-anxiety.md 的丧失与创伤部分
4. 完成标准：用户焦虑下降 ≥ 2 分，或定了一个压力管理行动

## 模式 B：微课（知识学习）

用户说"给我讲讲 X / 我想了解 Y / 教我 Z"。

1. 从 `references/knowledge-index.md` 匹配话题来源
2. 在 `~/learning-cbt/` 建教学空间（或已有空间则继续）
3. 用 `/teach` 创建 HTML 微课：
   - 写 MISSION.md
   - 每课一个 HTML 文件，lessons/
   - 每课只教一个极小知识点（2 分钟内能读完）
   - 结尾写一段可喂给语音 AI 的总结
   - 写 learning-record 记录进度
4. 如果没有 `/teach` skill：直接对话式教学
