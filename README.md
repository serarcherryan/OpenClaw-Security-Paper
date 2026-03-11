# OpenClaw Security Paper Collection

AI Agent Security 相关论文总结集合 - 2026 年以来

---

## 📄 论文 1：MiniAppBench - 评估 LLM 驱动助手的交互式 HTML 响应

| 项目 | 内容 |
|------|------|
| 标题 | MiniAppBench: Evaluating the Shift from Text to Interactive HTML Responses in LLM-Powered Assistants |
| 作者 | Zuhao Zhang, Chengyue Yu, Yuante Li, Chenyi Zhuang, Linjian Mo, Shuai Li |
| 发表日期 | 2026-03-10 |
| 代码仓 | 暂无 |
| PDF 链接 | https://arxiv.org/pdf/2603.09652v1 |

**论文总结**
- **采用方法**：提出 MiniAppBench 评估框架，测试 LLM 从静态文本响应向动态交互式 HTML 应用生成的能力转变
- **解决问题**：评估 AI 助手在生成可交互 Web 应用时的安全性、功能性和用户体验
- **优势**：
  - 首个针对 LLM 生成交互式应用的系统化评估基准
  - 涵盖安全性、功能性、可用性多维度评估
- **不足**：
  - 未深入讨论生成代码的安全漏洞问题
  - 评估范围主要限于前端交互
- **未来方向**：扩展至全栈应用生成的安全评估

---

## 📄 论文 2：MM-tau-p² - 多模态 Agent 评估的人格自适应提示

| 项目 | 内容 |
|------|------|
| 标题 | MM-tau-p²: Persona-Adaptive Prompting for Robust Multi-Modal Agent Evaluation in Dual-Control Settings |
| 作者 | Anupam Purwar, Aditya Choudhary |
| 发表日期 | 2026-03-10 |
| 代码仓 | 暂无 |
| PDF 链接 | https://arxiv.org/pdf/2603.09643v1 |

**论文总结**
- **采用方法**：提出人格自适应提示框架，在双控制设置下评估多模态 LLM Agent
- **解决问题**：现有评估框架不向 Agent 暴露用户人格特征，导致用户无关的评估偏差
- **优势**：
  - 引入用户人格感知，提升评估的真实性
  - 双控制设置增强评估的鲁棒性
- **不足**：
  - 未充分讨论人格信息可能带来的隐私泄露风险
  - 多模态安全性评估覆盖不足
- **未来方向**：将方法扩展到隐私保护的人格自适应评估

---

## 📄 论文 3：PRECEPT - LLM Agent 的测试时适应统一框架

| 项目 | 内容 |
|------|------|
| 标题 | PRECEPT: Planning Resilience via Experience, Context Engineering & Probing Trajectories |
| 作者 | Arash Shahmansoori |
| 发表日期 | 2026-03-10 |
| 代码仓 | 暂无 |
| PDF 链接 | https://arxiv.org/pdf/2603.09641v1 |

**论文总结**
- **采用方法**：提出统一框架，结合组合规则学习和 Pareto 引导的提示进化，实现测试时适应
- **解决问题**：LLM Agent 以自然语言存储知识时，随条件数量增加检索性能急剧下降，难以可靠组合学习规则
- **优势**：
  - 明确的测试时适应机制
  - Pareto 引导的提示进化提升鲁棒性
- **不足**：
  - 未提供代码仓库，可复现性待验证
  - 计算开销可能较大
- **未来方向**：探索更高效的检索和规则组合机制

---

## 📄 论文 4：Context Engineering - 从提示到企业级多 Agent 架构

| 项目 | 内容 |
|------|------|
| 标题 | Context Engineering: From Prompts to Corporate Multi-Agent Architecture |
| 作者 | Vera V. Vishnyakova |
| 发表日期 | 2026-03-10 |
| 代码仓 | 暂无 |
| PDF 链接 | https://arxiv.org/pdf/2603.09619v1 |

**论文总结**
- **采用方法**：提出上下文工程框架，从单一提示设计扩展到企业级多 Agent 架构
- **解决问题**：传统提示工程不足以支持自主多步 Agent 和企业级部署的复杂性
- **优势**：
  - 系统化的多 Agent 架构设计方法
  - 考虑企业级部署的实际需求
- **不足**：
  - 安全性讨论较为有限
  - 缺乏具体的安全边界和隔离机制
- **未来方向**：加强多 Agent 系统的安全隔离和权限管理

---

## 📊 总体观察

**2026 年 AI Agent 安全研究趋势：**
1. 🔍 **评估框架** - 多篇论文聚焦于 Agent 评估基准
2. 🏢 **企业级应用** - 多 Agent 架构成为热点
3. ⚠️ **安全关注不足** - 多数论文侧重功能性，安全性讨论有限

---

*最后更新：2026-03-11*
*搜索主题：AI Agent Security*
*时间范围：2026 年以来*
*论文数量：4 篇精选*
