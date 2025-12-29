#  Awesome LLM Prompts Collection | 全能 LLM 提示词库

[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](CONTRIBUTING.md)
[![Maintenance](https://img.shields.io/badge/Maintained%3F-yes-green.svg)](https://github.com/yourusername/repo)

> **解锁大语言模型的无限潜能。**
>
> 本仓库致力于收集、整理和分享适用于 ChatGPT, Claude, Gemini, Llama 等主流 LLM 的高质量提示词（Prompts）。无论你是开发者、内容创作者还是 AI 爱好者，都能在这里找到提升效率的钥匙。

---

## 📖 目录 (Table of Contents)

- [🌟 项目介绍](#-项目介绍)
- [📂 提示词分类](#-提示词分类)
- [🛠 使用指南](#-使用指南)
- [🧠 Prompt 编写技巧](#-prompt-编写技巧)

---

## 🌟 项目介绍

随着大语言模型（LLM）的爆发，**Prompt Engineering (提示工程)** 成为了一项核心技能。一个优秀的 Prompt 可以让 AI 的输出从“平平无奇”变为“惊艳全场”。

本仓库的目标是：
1.  **汇集精品**：拒绝低质量的水词，只收录经过验证的高效 Prompt。
2.  **分类清晰**：按照应用场景和职业角色进行分类，方便查找。
3.  **多语言支持**：涵盖中文和英文的高质量提示词。

---

## 📂 提示词分类

我们按照应用场景将 Prompt 整理在不同的文件夹中：

| 分类                | 描述                                         | 路径                              |
| :------------------ | :------------------------------------------- | :-------------------------------- |
| **💻 编程与开发**    | 代码生成、Bug 修复、代码解释、架构设计       | [`/coding`](./coding)             |
| **📝 写作与内容**    | 博客撰写、SEO 优化、文案润色、剧本创作       | [`/writing`](./writing)           |
| **🎓 学术与教育**    | 论文润色、知识点总结、苏格拉底式教学         | [`/academic`](./academic)         |
| **📊 职场与生产力**  | 邮件回复、会议纪要、Excel 公式生成、PPT 大纲 | [`/productivity`](./productivity) |
| **🎨 角色扮演**      | 模拟面试官、心理咨询师、Linux 终端           | [`/roleplay`](./roleplay)         |
| **🤖 AI 越狱与调试** | (仅供研究) 思维链 (CoT)、对抗性测试          | [`/jailbreak`](./jailbreak)       |

*(点击路径即可查看对应类别的详细 Prompt 列表)*

---

## 🛠 使用指南

1. **浏览分类**：根据你的需求进入相应的文件夹。
2. **复制 Prompt**：找到你需要的提示词，复制内容。
3. **替换变量**：如果 Prompt 中包含 `[中括号]` 包裹的内容（例如 `[请输入你的主题]`），请将其替换为你的实际内容。
4. **迭代优化**：如果 AI 的第一次回答不完美，尝试在原有 Prompt 基础上增加更多上下文或约束条件。

**示例：**

> **原始 Prompt:**
> "作为一名资深 Python 工程师，请解释一下 `[技术概念]`，并给出一个简单的代码示例。"
>
> **使用时:**
> "作为一名资深 Python 工程师，请解释一下 `Python 装饰器`，并给出一个简单的代码示例。"

---

## 🧠 Prompt 编写技巧

授人以鱼不如授人以渔，这里分享一些编写高质量 Prompt 的核心框架（参考 CRISPE 框架）：

* **C (Capacity/Role)**: 设定角色（例如：你是一名资深律师...）
* **R (Request)**: 具体的任务（例如：帮我起草一份合同...）
* **I (Insight/Context)**: 背景信息（例如：合同针对的是软件外包服务...）
* **S (Statement)**: 具体的指令步骤（例如：首先列出条款，然后...）
* **P (Personality)**: 语气风格（例如：专业、严谨、简洁...）
* **E (Experiment)**: 示例/输出格式（例如：请用 Markdown 表格形式输出...）
