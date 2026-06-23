# AI 协作总则

适用于 ChatGPT、Claude、Codex、OpenClaw、DeepSeek 及其他参与本项目的 AI 或自动化代理。

## 唯一责任人

产品负责人：罗松涛。

只有产品负责人可以最终批准：

- 产品定位与 MVP 范围变化；
- 核心架构、Unity 大版本、存档和联机协议破坏性变更；
- 商业化、正式发布、数据删除和不可逆操作。

## 开工前必读

1. `AGENTS.md`
2. `docs/product/PRODUCT_MASTER_PLAN.md`
3. `docs/product/MVP_SCOPE.md`
4. `docs/product/NON_GOALS.md`
5. `docs/management/CHANGE_HANDOFF_LOG.md`
6. 当前 GitHub Issue
7. 相关模块文档与测试

冲突优先级：

产品负责人明确指令 > 产品总方案 > MVP 范围 > ADR > 模块文档 > Issue > 代码注释。

## 无 Issue 不开工

每项任务必须有 Issue，并写明背景、目标、范围、非范围、验收、测试和风险。

## 单一主要执行者

同一任务、同一模块、同一时间只有一个主要执行代理。

建议职责：

- ChatGPT：产品设计、任务拆解、美术需求和产品验收；
- Claude：架构方案与高级代码审查；
- Codex：代码实现、测试、修复和局部重构；
- OpenClaw：调度、构建、测试、日志和状态报告；
- 罗松涛：范围决定、试玩、最终验收和合并。

## Git 工作流

禁止直接强推或重写 `main` 历史。

分支：

- `feature/issue-<id>-<name>`
- `fix/issue-<id>-<name>`
- `docs/issue-<id>-<name>`
- `refactor/issue-<id>-<name>`
- `art/issue-<id>-<name>`

一个 PR 原则上只解决一个 Issue。

## 禁止事项

- 提交密钥、Token、密码和真实用户数据；
- 使用未授权商业游戏素材、代码、音乐、角色、Logo 或文本；
- 绕过测试宣称完成；
- 未经批准清库、发版、付费、生产部署；
- 伪造构建、测试、截图或日志；
- 擅自扩大功能范围。

## 完成要求

PR 必须说明：

- 完成与未完成内容；
- 修改模块；
- 自动测试与构建结果；
- 手工验证步骤；
- 已知风险与回滚方式；
- 交接记录。

详见 `docs/management/DEFINITION_OF_DONE.md`。
