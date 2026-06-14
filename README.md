# Claudian Excellence — 克劳德卓越实践指导

[English](#english) | [中文](#中文)

---

## English

**Claudian Excellence** is a custom Agentic Skill designed to bring the advanced cognitive frameworks, task decomposition logic, search-citation guidelines, and behavioral principles of the **Claude Fable 5 System Prompt** to your own AI agents (such as Antigravity, Claude Code, and Codex CLI).

### Core Features

1. **Active Task Decomposition**: Instructs the agent to break down abstract or vague queries into specific, executable sub-tasks rather than guessing.
2. **File Verification First**: Prevents hallucinated edits by enforcing physical inspection of files (using `view`, `cat`, etc.) before any read or write operations.
3. **Robust Development Principles**: Demands fully-realized code blocks with robust error handling (`try-catch`, parameter checks) and eliminates placeholders.
4. **Natural Prose & Minimal Formatting**: Encourages the model to communicate in natural, conversational paragraphs and avoid robotic over-formatting (excessive bold text, bullet points).
5. **Epistemic Humility & Wellbeing Ethics**: Provides standard boundaries for medical/legal/financial topics, including preventing self-harm sensory shock suggestions and ensuring professional referral guidelines.

### Installation

To install this skill on your local agent system:

#### For Antigravity / Gemini Agent SDK
```bash
mkdir -p ~/.agents/skills/claudian-excellence
curl -fsSL -o ~/.agents/skills/claudian-excellence/SKILL.md https://raw.githubusercontent.com/lufie/claudian-excellence/main/SKILL.md
```

#### For Codex CLI / Claude Code
```bash
mkdir -p ~/.codex/skills/claudian-excellence
curl -fsSL -o ~/.codex/skills/claudian-excellence/SKILL.md https://raw.githubusercontent.com/lufie/claudian-excellence/main/SKILL.md
```

Once installed, your agents will dynamically load and enforce these rules during tasks involving writing, coding, searching, and general reasoning.

---

## 中文

**Claudian Excellence（克劳德卓越实践指导）** 是一款自定义智能体技能（Skill）。它旨在将 **Claude Fable 5 官方系统提示词** 中先进的认知框架、任务拆解逻辑、检索引用规范和人机交互行为法则，无缝复用到你自己的 AI 助理中（如 Antigravity、Claude Code 及 Codex CLI）。

### 核心特性

1. **主动任务拆解**：教导智能体在面对模糊或复杂的任务时，主动进行子任务拆分与逐步推理，避免猜测用户意图。
2. **文件防错验证**：在对任何文件进行编辑或读取前，必须先调用文件查看工具（如 `view`、`cat` 等）验证其实际内容与结构，根除 AI “想当然”的虚假修改。
3. **健壮的开发规范**：要求编写逻辑完整、带有异常捕获（`try-catch`）和参数校验的代码，消灭无意义的代码占位符（如 `// TODO`）。
4. **自然排版风格**：提倡流畅自然的散文（Prose）表达，杜绝滥用多级标题、项目符号和过度粗体，使人机对话更具亲和力和可读性。
5. **认识论谦逊与福祉伦理**：规范了涉及医疗、法律、财务以及危机干预时的交互界限，避免过度分析与错误的保密承诺，引导用户求助专业渠道。

### 安装方法

在你的本地智能体系统中安装该技能：

#### 用于 Antigravity / Gemini Agent 框架
```bash
mkdir -p ~/.agents/skills/claudian-excellence
curl -fsSL -o ~/.agents/skills/claudian-excellence/SKILL.md https://raw.githubusercontent.com/lufie/claudian-excellence/main/SKILL.md
```

#### 用于 Codex CLI / Claude Code
```bash
mkdir -p ~/.codex/skills/claudian-excellence
curl -fsSL -o ~/.codex/skills/claudian-excellence/SKILL.md https://raw.githubusercontent.com/lufie/claudian-excellence/main/SKILL.md
```

安装完成后，智能体将在处理包含编写、代码、搜索、分析、调试等相关意图的任务时，自动触发并遵循该技能的黄金法则。
