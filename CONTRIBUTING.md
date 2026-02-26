# 贡献指南

感谢你帮助改进 k-neco-lab 的项目。

## 开始之前
- 在新建 Issue 或 PR 前，先搜索是否已有相关内容。
- 保持改动聚焦：避免把无关重构与功能变更混在同一个 PR 里。

## Issue（问题反馈）
我们使用 Issue 表单收集排查与修复问题所需的信息。
请避免提交任何敏感信息（密钥/凭据）或用户隐私数据。

## Pull Request（PR）
### 标题
PR 标题使用 Conventional Commits：

`type(scope): subject`

允许的类型：
- feat, fix, refactor, chore, docs, build, ci, test, perf

示例：
- `fix(api): handle empty token response`
- `feat(cli): add dry-run option`

### 合并策略
部分仓库可能仅允许 squash merge。此时：
- squash 后的提交标题将来自 PR 标题。
- 保持 PR 描述有信息量：它可能会作为 squash commit 的提交信息。

### 测试
- 需要时添加或更新测试。
- 在 PR 描述中写明你运行过的命令（或说明为什么不适用测试）。

## 安全
安全漏洞不要通过公开 Issue 披露。
