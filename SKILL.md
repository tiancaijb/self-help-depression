---
name: self-help-depression
description: 抑郁与反刍思维循证自助。基于 CBT、正念、营养精神病学、神经科学的症状全覆盖。当用户说自己或他人抑郁/反刍/注意力涣散/失眠/多巴胺成瘾/社交创伤/压力焦虑/想学心理知识时使用。提供即时干预和系统知识教学双模式。
---

# 抑郁自助 · 反刍思维干预

## ⚠️ 隐私声明

`state.md` 包含用户隐私信息。绝不上传到任何公开平台。

## 跨 session 衔接

先读 `state.md` 了解历史状态。对话中实时更新。重新加载时先读状态再继续。

**如果用户有自杀念头或自伤行为，先走危机干预（`references/crisis-resources.md`），再做下面的。**

---

## 工作模式

本 skill 有两种模式：

**模式 A：症状 → 行动** — 用户说状态，匹配分支，提供即时可操作的工具
**模式 B：知识 → 学习** — 用户想学某个知识，用 `/teach` 建 HTML 课程

## 重要：如何使用所有资料

`references/` 下的文件是**精华摘要**（快速查工具用）。`books/` 和 `huberman/` 下的全文是**深度来源**。

**每个分支的通用规则：**
1. 用户说症状 → 先读对应的 reference 找工具
2. **同时**从对应的 huberman/ 或 books/ 中提取机制来解释"为什么"——用户需要知道"什么有用"和"为什么有用"
3. 如果用户追问细节→从对应全文摘录原文
4. 不要只给摘要——把书和播客的内容用你自己的话教给用户

## 模式 A：症状分支

### 1. 抑郁/情绪低落/低自尊

用户说"抑郁/难受/快感缺失/觉得自己很差/没希望了"。

**资料来源：**
- huberman/01（pleasure-pain balance, 多巴胺机制）
- huberman/04（六大支柱）
- huberman/11（光照与情绪）
- books/feeling-good.md（CBT 全本）
- books/emotional-first-aid.md（低自尊章）
- books/The Better Brain.md（营养角度）
- books/zebras.txt（压力神经科学）
- books/dopamine-nation.md（多巴胺失衡与抑郁）

步骤：
1. 安全确认：自杀念头？→ 走 crisis-resources.md
2. 定位认知扭曲：帮用户写出脑中自动冒出来的话 → 从 `references/depression.md` 的 10 种扭曲中匹配
3. 选工具：简版三栏技巧（用户写自动思维 → 你标扭曲 → 用户想理性回应）
4. 如果行动力归零：切到 attention.md 的最小行动法
5. 如涉及认可/爱/工作价值 → depression.md 的认可成瘾部分
6. 完成标准：用户情绪下降 ≥ 2 分（0-10），或说"好一些了"

### 2. 反刍/侵入性思维/内疚/愤怒

用户说"停不下来/反复想同一件事/控制不住/内疚/气得不行"。

**资料来源：**
- huberman/02（侵入性思维的神经回路、NSDR）
- books/emotional-first-aid.md Ch5（反刍章）
- books/feeling-good.md Ch7（愤怒）Ch8（内疚）
- books/mindful-way.txt（MBCT 正念）
- books/The Power of Now.md（临在观察）

步骤：
1. 评估情绪强度（0-10）：
   - ≥ 7 → 先去 `references/rumination.md` 的 5-4-3-2-1 或冷刺激
   - 4-7 → 定时担忧法或自离视角
   - < 4 → 反刍重构三问或正念接纳
2. 如果是愤怒反刍 → rumination.md 的愤怒部分
3. 如果是内疚 → rumination.md 的内疚部分
4. 完成标准：用户情绪下降 ≥ 1 分，或能说出一个反刍对应的认知扭曲

### 3. 注意力涣散/拖延/完美主义

用户说"集中不了/不想动/不知道做什么/做得不够好"。

**资料来源：**
- books/feeling-good.md Ch5（拖延全章）
- books/Atomic Habits.md（习惯）
- huberman/03（专注工具包）
- huberman/05（ADHD 机制）
- huberman/06（多巴胺与动机）

步骤：
1. 从 `references/attention.md` 选一个极小的工具：
   - 完全不动 → 反拖延表（预测 vs 实际）
   - 有一点动力 → 碎步法（≤15 分钟）
   - 想系统改善 → 每日活动计划表
2. 如果是完美主义卡住 → attention.md 的反完美主义表 + 开心预测法
3. 完成标准：用户做了一件 ≥ 2 分钟的事，或定了一个可执行的最小行动

### 4. 失眠/作息乱

用户说"睡不着/睡不好/昼夜颠倒"。

**资料来源：**
- huberman/08（睡眠大师，昼夜节律全解）
- huberman/09（睡眠工具包）
- huberman/10（光照/食物/运动的时序）
- huberman/11（黑暗与心理健康）
- books/The Better Brain.md（营养助眠）

步骤：
1. `references/sleep.md` 选工具：
   - 今晚睡不着 → 黑暗环境 + 温度控制 + NSDR
   - 长期改善 → 早晨光照 + 睡眠一致性 + 咖啡因管理
2. 完成标准：用户今晚会做一件改善睡眠的事（关灯时间提前/明天看日光/设固定起床时间）

### 5. 多巴胺成瘾/自慰/刷手机/游戏

用户说"控制不住自慰/一直刷手机/停不下来/需要找刺激"。

**资料来源：**
- books/Dopamine Nation.md（pleasure-pain balance 全书）
- huberman/06（多巴胺与动机）
- huberman/07（冷暴露与多巴胺重置）
- huberman/01（抑郁与多巴胺的关系）
- books/Atomic Habits.md（行为替代）

步骤：
1. 先不批判——这属于多巴胺调节问题，不是道德问题
2. 从 `references/dopamine.md` 选工具：
   - 即时 → 识别触发场景 + 准备替代行为
   - 短期 → 多巴胺斋戒（每天 1-4 小时无手机）
   - 长期 → 多巴胺菜单 + 冷暴露
3. 完成标准：用户识别了一个触发场景和对应的替代行为

### 6. 社交创伤/被拒绝/孤独/批评敏感

用户说"被拒绝了/很孤独/怕被批评/社交焦虑"。

**资料来源：**
- books/emotional-first-aid.md（拒绝、孤独章）
- books/feeling-good.md Ch6（语言柔道）
- huberman/04（社交连接与心理健康）

步骤：
1. `references/social.md` 匹配问题类型
2. 执行对应急救方案
3. 完成标准：用户做了一件重新建立社交连接的事（发消息给朋友/参加活动/用语言柔道应对了一个批评）

### 7. 压力/焦虑

用户说"压力大/焦虑/心慌/绷得太紧"。

**资料来源：**
- books/zebras.txt（压力神经科学全书）
- huberman/19（压力进食）
- huberman/04（心理健康六大支柱）
- books/The Power of Now.md（临在面对焦虑）
- books/emotional-first-aid.md（创伤章）

步骤：
1. 如果焦虑发作 → 生理叹息（吸→再吸→慢呼）× 2-3 次，或冷水洗脸
2. `references/stress-anxiety.md` 选长期工具
3. 如果是丧失/创伤 → stress-anxiety.md 的丧失与创伤部分
4. 完成标准：用户焦虑下降 ≥ 2 分，或定了一个压力管理行动

---

## 模式 B：知识学习

用户说"给我讲讲 X / 我想了解 Y / 教我 Z"。

步骤：
1. 从 `references/knowledge-index.md` 找到话题对应的资料来源
2. 在 `~/learning-cbt/` 建教学空间（或已有空间则继续）
3. 用 `/teach` 创建 HTML 课程：
   - 写 MISSION.md（用户想学什么 + 为什么）
   - 每课一个 HTML 文件，放在 lessons/
   - 每课只教一个极小的知识点（2 分钟内能读完）
   - 结尾写一段可喂给语音 AI 的总结
   - 写 learning-record 记录进度
4. 如果用户没有 `/teach` skill：直接对话式教学，一次教一点

---

## 核心工具速查

**三栏技巧：**
```
自动思维（原话） | 认知扭曲（哪种） | 理性回应（客观的话）
```

**反刍打断三问：**
- "这件事我还能改变什么？"
- "如果朋友遇到同样的事，我会怎么跟他说？"
- "一周后还重要吗？"

**生理叹息：** 深吸一口 → 再吸一口 → 缓慢呼出。一次见效。

**最小行动法：** 拆到 2 分钟以内能做完的事。做了就是赢了。

---

## 加新书流程

1. 全文转 markdown → `books/<书名>.md`
2. 在 `references/` 下补充话题（或更新已有）
3. 更新 `references/knowledge-index.md` 的知识索引
4. 更新 `COVERAGE.md`
5. `books/` 和 `state.md` 不入 git

## 藏书与资料

- `books/` — 书籍全文（本地）
- `huberman/` — 播客文字稿（本地）
- `references/` — 精华参考（公开）
