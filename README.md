# self-help-depression

抑郁与反刍思维循证自助 — 基于 CBT、正念、行为激活的 pi agent skill。

## 这是什么

一个 [pi coding agent](https://github.com/earendil-works/pi-coding-agent) skill，用于：

- **抑郁自助**：CBT 认知扭曲识别、三栏技巧、行为激活
- **反刍思维干预**：打断技术、视角切换、定时担忧法
- **每日练习**：8 个即用练习（≤15 分钟）
- **危机导引**：自杀念头时的行动清单和求助热线
- **书籍导航**：7 本经典自助书的核心方法速查

## 使用方法

### 安装

```bash
mkdir -p ~/.pi/agent/skills/
cd ~/.pi/agent/skills/
git clone https://github.com/tiancaijb/self-help-depression.git
```

pi agent 会自动发现这个 skill。当对话中出现抑郁、反刍、情绪低落相关话题时，agent 会加载它。

### 添加书籍全文（可选）

本 skill 不含书籍全文，方法总结已包含在 `references/books.md` 中。如需直接引用原文：

1. 购买正版电子书（epub 格式）
2. 转为 markdown：`pandoc book.epub -t markdown -o books/book-name.md --wrap=none`
3. 确保 `books/` 在 `.gitignore` 中，以防意外提交

### 手动调用

```
/skill:self-help-depression
```

## 结构

```
self-help-depression/
├── SKILL.md                  # 主入口 — 4 个分支 4 种工作流
├── state.md                  # 跨 session 状态记录
├── books/                    # [本地] 书籍全文，不入 git
├── references/
│   ├── books.md              # 7 本书核心方法速查
│   ├── rumination.md         # 反刍思维打断技术
│   ├── daily-exercises.md    # 每日自助练习
│   └── crisis-resources.md   # 危机资源与热线
└── .gitignore
```

## 推荐书目

1. 《伯恩斯新情绪疗法》— David D. Burns（CBT 基础）
2. 《蛤蟆先生去看心理医生》— Robert de Board（心理咨询入门）
3. 《也许你该找个人聊聊》— Lori Gottlieb（治疗师的故事）
4. 《穿越抑郁的正念之道》— Mark Williams 等（正念 MBCT）
5. 《情绪急救》— Guy Winch（心理伤口急救包）
6. 《当下的力量》— Eckhart Tolle（正念/临在）
7. 《原子习惯》— James Clear（抑郁期行为激活）

## 注意事项

- 本 skill 是**自助补充工具**，不能替代专业心理治疗
- 如果有自杀念头或自伤行为，请立即拨打心理热线（见 `references/crisis-resources.md`）
- 书籍全文需用户自行购买正版，本仓库仅包含方法总结和转述

## License

MIT
