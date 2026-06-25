# AI Privacy Redaction Skill

这是一个中英双语 AI skill 仓库，目标是：帮助用户在把日志、会议记录、客服文本或提示词交给 AI 前，先识别并脱敏 secrets、PII 和敏感上下文。

## 安装 / Install

将本仓库克隆到你的本地 skill 目录，或复制 `SKILL.md` 到目标工具的 skill 目录。

```powershell
git clone https://github.com/TheAatroxking1/ai-privacy-redaction-skill.git
```

## 快速开始 / Quick Start

1. 打开你的 AI coding 工具。
2. 启用 `ai_privacy_redaction_skill` skill。
3. 提供你的目标、输入材料和希望输出的格式。
4. 让工具按 `SKILL.md` 中的流程完成任务。

## 适用场景

帮助用户在把日志、会议记录、客服文本或提示词交给 AI 前，先识别并脱敏 secrets、PII 和敏感上下文。

## 跨工具使用

- Codex：直接读取根目录 `SKILL.md`。
- Claude Code：查看 `claude-code/README.md`。
- OpenClaw：查看 `openclaw/README.md`。
- Generic CLI：查看 `generic-cli/README.md`。

## 资料来源

- [NIST Privacy Framework](https://www.nist.gov/privacy-framework)，可信度：0.90
- [Microsoft Presidio documentation](https://microsoft.github.io/presidio/)，可信度：0.85
- [GitHub secret scanning documentation](https://docs.github.com/en/code-security/secret-scanning)，可信度：0.90

## 标签

privacy, redaction, ai-safety, codex-skill

## 安全边界

本 skill 只做低风险辅助，不提供医疗诊断、法律结论、金融投资建议、网络攻击执行或平台规则规避。

## License

MIT
