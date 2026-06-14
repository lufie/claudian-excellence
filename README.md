# Claudian Excellence — 克劳德卓越实践指导

[English](#english) | [中文](#中文)

---

## English

**Claudian Excellence** is a custom Agentic Skill designed to bring the advanced cognitive frameworks, task-handling strategies, search-citation rules, and behavioral guidelines from the official **Claude Fable 5 System Prompt** to your own AI agents (such as Antigravity, Claude Code, and Codex CLI).

* **Original System Prompt Source**: [elder-plinius/CL4R1T4S (CLAUDE-FABLE-5.md)](https://github.com/elder-plinius/CL4R1T4S/blob/main/ANTHROPIC/CLAUDE-FABLE-5.md)

---

### How it Works (Principles)

System prompts are the "neural constitution" of LLMs. By injecting these rules as an agentic skill, we enforce structured cognitive strategies:

1. **Active Task Decomposition (Chain of Thought)**: AI models perform significantly better when they decompose complex, abstract, or vague requests into explicit, sequential sub-steps. This skill eliminates guesswork and forces logical planning.
2. **Physical Verification Before Action (Anti-Hallucination)**: LLMs often guess file paths or assume code states. The "verification first" rule requires the agent to check the physical directory/file using `view` or read tools before doing any edits, eliminating hallucination loop-errors.
3. **Robust Development Enforcement**: Eliminates lazy placeholders (e.g. `// TODO`) and requires strict, self-contained exception handling (`try-catch`, parameter checks), forcing the model to write production-grade code.
4. **Natural Prose & Noise Reduction**: By restricting excessive bolding, nested lists, and bullet points, the model focuses its attention mechanism on core semantic reasoning and writes clean, cohesive prose.
5. **Epistemic Humility & Ethics**: Instructs the agent to remain balanced, factual, and legally/ethically compliant without hallucinating diagnostic assertions or false promises.

---

### Installation & Configuration

This skill is designed for agents that support directory-based natural language triggering.

#### 1. For Antigravity / Gemini Agent SDK
Install to the global agent skills directory:
```bash
mkdir -p ~/.agents/skills/claudian-excellence
curl -fsSL -o ~/.agents/skills/claudian-excellence/SKILL.md https://raw.githubusercontent.com/lufie/claudian-excellence/main/SKILL.md
```

#### 2. For Codex CLI / Claude Code
Install to the local Codex CLI skills folder:
```bash
mkdir -p ~/.codex/skills/claudian-excellence
curl -fsSL -o ~/.codex/skills/claudian-excellence/SKILL.md https://raw.githubusercontent.com/lufie/claudian-excellence/main/SKILL.md
```

#### 3. Project-Level Instructions (`CLAUDE.md`)
You can also append these rules directly to your project's local developer instruction file (`CLAUDE.md` at the project root) for project-specific compliance.

---

## 中文

**Claudian Excellence（克劳德卓越实践指导）** 是一款自定义智能体技能（Skill）。它旨在将 **Claude Fable 5 官方系统提示词** 中先进的认知框架、任务拆解逻辑、检索引用规范和人机交互行为法则，无缝复用到你自己的 AI 助理中（如 Antigravity、Claude Code 及 Codex CLI）。

* **系统提示词原文件地址**：[elder-plinius/CL4R1T4S (CLAUDE-FABLE-5.md)](https://github.com/elder-plinius/CL4R1T4S/blob/main/ANTHROPIC/CLAUDE-FABLE-5.md)

---

### 运行原理与为什么它会变好

系统提示词是控制大语言模型（LLM）行为的“运行宪法”。将这些规则作为 Skill 挂载到 Agent 中，可以让 AI 自动遵循以下科学的认知改进方法：

1. **主动任务拆解（思维链提升）**：当遇到复杂、含糊的任务时，AI 往往容易迷失。本技能强制 AI 将任务细化为具体、可执行的子步骤，极大地提高了复杂业务逻辑的准确度。
2. **物理防错验证（消除幻觉）**：AI 常会凭空猜测本地文件结构或内容。本技能规定在对文件进行任何读取/修改操作之前，必须“亲眼确认”文件内容。这种物理级别的检查彻底切断了 AI 幻觉和盲目修改的恶性循环。
3. **强制代码健壮性**：限制 AI 编写不完整的代码，消灭诸如 `// TODO` 或空占位符等偷懒行为，并强制加入 `try-catch` 等异常捕获逻辑，产出即用型的高质量生产代码。
4. **自然排版与注意力降噪**：过多的小标题、粗体和项目符号会分散大模型的注意力权重（Attention Span）。通过规范自然散文（Prose）的输出，逼迫大模型把算力用在最核心的语义组织和逻辑推导上。
5. **认识论谦逊与伦理安全**：防止智能体在遇到心理健康、法律或财务敏感问题时越界做出武断诊断或虚假承诺，确保交付安全、客观的回答。

---

### 设置与安装方法

本技能兼容支持目录结构和自然语言触发机制的 Agent 系统。

#### 1. 用于 Antigravity / Gemini Agent 框架
在你的全局智能体技能目录下创建并下载技能：
```bash
mkdir -p ~/.agents/skills/claudian-excellence
curl -fsSL -o ~/.agents/skills/claudian-excellence/SKILL.md https://raw.githubusercontent.com/lufie/claudian-excellence/main/SKILL.md
```

#### 2. 用于 Codex CLI / Claude Code
将技能保存至你本地的 Codex CLI 配置中：
```bash
mkdir -p ~/.codex/skills/claudian-excellence
curl -fsSL -o ~/.codex/skills/claudian-excellence/SKILL.md https://raw.githubusercontent.com/lufie/claudian-excellence/main/SKILL.md
```

#### 3. 项目级规范 (`CLAUDE.md`)
如果你希望某一特定项目完全遵循该规范，只需将核心要点直接追加到该项目根目录的 `CLAUDE.md` 文件中，智能体在进入该项目时会自动加载。
