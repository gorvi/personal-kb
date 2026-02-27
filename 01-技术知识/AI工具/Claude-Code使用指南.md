# Claude Code 使用指南

> Cloudflare 工程师 Boris Tane 的高效 AI 编程工作流

## 原文来源
- **作者**: Boris Tane (Cloudflare 员工)
- **链接**: boristane.com/blog/how-i-use-claude-code
- **整理**: 小红书 @得嗯邓

---

## 六步工作流

### 1. Research 深入研究
深入阅读指定代码目录/模块，输出详细的 `research.md` 报告

**关键产出**: 
- 代码结构分析
- 依赖关系梳理
- 潜在问题识别

### 2. Planning 详细规划
基于 research，生成详细的 `plan.md` 文件

**关键产出**:
- 改造方案
- 技术选型
- 风险评估

### 3. Annotation Cycle 迭代注释
在 `plan.md` 中按照自己的需求直接写评论，让 CC 更新 plan 文件，直到满意

**核心技巧**:
- 像 Code Review 一样给 AI 提意见
- 多轮对话打磨方案
- 文档即对话载体

### 4. 生成 Todo List
根据 plan 生成可执行的任务清单

### 5. Implement 完整执行
AI 按规划完整执行代码修改

### 6. Feedback & Iterate 反馈迭代
用简单指令反馈，持续优化

---

## 核心洞察

> 其实很多 Agent 都可以使用同样的步骤来完成整个流程

这个六步工作流具有**通用性**，可迁移至其他 AI Agent 使用：
- 研究 → 规划 → 迭代 → 执行 → 反馈

---

## 实践建议

1. **文档化协作**: 用 markdown 文件作为人机协作的桥梁
2. **渐进式细化**: 不要期望一次到位，多轮迭代更可靠
3. **保留上下文**: research.md 和 plan.md 可随时回溯决策过程

---

*Source: 小红书 @得嗯邓 | 整理时间: 2026-02-28*
