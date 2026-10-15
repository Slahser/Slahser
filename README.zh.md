# S1ahs3r

[中文](README.zh.md) · [English](README.md)

软件工程师。公开代码在 [GitHub](https://github.com/Slahser)，主要在 [RetiredPhysicist](https://github.com/RetiredPhysicist) 和 [RealAlexandreAI](https://github.com/RealAlexandreAI)。网站：[slahser.com](https://slahser.com)。

## 联系

| | |
| --- | --- |
| GitHub | [github.com/Slahser](https://github.com/Slahser) |
| 网站 | [slahser.com](https://slahser.com) |
| LinkedIn | [linkedin.com/in/slahser](https://www.linkedin.com/in/slahser/) |
| X | [@S1ahs3r](https://x.com/S1ahs3r) |
| Medium | [medium.com/@S1ahs3r](https://medium.com/@S1ahs3r/) |

## 工作

```text
agents
  Claude Code   RetiredPhysicist/cc-plugins
  Codex         RetiredPhysicist/openai-plugins
  Pi            RetiredPhysicist/pi-plugins
  DeepSeek      RetiredPhysicist/dsh-plugins
  skills        RealAlexandreAI/public-skills

libraries
  Go            json-repair · featuregate · io-sankey
  CLI           shannon-statusline（已归档）
```

### Agent 插件

| 仓库 | 是什么 |
| --- | --- |
| [RetiredPhysicist/cc-plugins](https://github.com/RetiredPhysicist/cc-plugins) | Claude Code 插件市场：状态行、进程内任务控制、会话地图、Atuin 历史 |
| [RetiredPhysicist/openai-plugins](https://github.com/RetiredPhysicist/openai-plugins) | Codex 与 ChatGPT 插件：网页搜索、记忆客户端、ASCII 线框编辑器、Things 3 工作区 |
| [RetiredPhysicist/pi-plugins](https://github.com/RetiredPhysicist/pi-plugins) | Pi 扩展，每个包按自己的 tag 发布到 npm |
| [RetiredPhysicist/dsh-plugins](https://github.com/RetiredPhysicist/dsh-plugins) | DeepSeek Harness 扩展，发布方式与 Pi 仓库相同 |
| [RealAlexandreAI/public-skills](https://github.com/RealAlexandreAI/public-skills) | 四个可携带的 agent skill：`bash-first`、`no-slop`、`cn-mirror`、`win-powershell` |

### 库

| 模块 | 最新版本 | 许可证 | 是什么 |
| --- | --- | --- | --- |
| [github.com/RealAlexandreAI/json-repair](https://github.com/RealAlexandreAI/json-repair) | v0.0.18 | GPL-3.0 | 修复格式错误的 JSON，包括语言模型的输出。命令行通过 [Homebrew tap](https://github.com/RealAlexandreAI/homebrew-tap-jsonrepair) 安装 |
| [github.com/RealAlexandreAI/featuregate](https://github.com/RealAlexandreAI/featuregate) | v0.0.1 | Apache-2.0 | 按名字开关的功能开关，从 [mosn/mosn](https://github.com/mosn/mosn) 的 `pkg/featuregate` 拆出 |
| [github.com/RealAlexandreAI/io-sankey](https://github.com/RealAlexandreAI/io-sankey) | v0.0.4 | GPL-3.0 | 用表达式把一个 JSON 值映射成另一个，再校验结果 |
| [RealAlexandreAI/shannon-statusline](https://github.com/RealAlexandreAI/shannon-statusline) | 已归档 | MIT | Claude Code 的 ANSI 状态行。仓库已归档，npm 包已不再发布 |

上表版本是 2026-10-15 在公开 Go 模块代理（`proxy.golang.org`）上查到的最新 tag。
