# vuln-scan-orchestrator

WorkBuddy skill：多引擎漏洞扫描编排（密钥泄漏 / 依赖 SCA / IaC 配置），含引擎选型矩阵、集成指南、triage playbook 与 DAST 授权门禁。

- 引擎矩阵与实测经验：[references/scanner-matrix.md](references/scanner-matrix.md) / [integration-guide.md](references/integration-guide.md)
- 结果处置：[triage-playbook.md](references/triage-playbook.md)
- 授权门禁：[authorization-gate.md](references/authorization-gate.md)

**配套系统**：[zhentong520/vulnscan](https://github.com/zhentong520/vulnscan) —— 基于本 skill 实测管线构建的 Web 漏洞扫描服务（本 skill 的 tools 已 vendor 进该系统的 `tools/`）。
