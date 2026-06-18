# 大模型Token成本节约 · WorkBuddy Skill

"大模型 Token 成本节约工具。在请求到达大模型之前自动压缩 prompt 和上下文，减少 60-95% 的 token 消耗，直接降低 API 成本。支持 Claude/OpenAI/Gemini 等主流模型，提供代理模式、CLI 包装、Python SDK 和 MCP Server 四种接入方式。适用于所有需要降低大模型 API 开销的 Agent 和应用。基于开源项目 headroom（https://github.com/chopratejas/headroom，MIT License）封装，已注明来源与许可证。"

## 特性

- 请参考 SKILL.md 中的详细说明

## 安装

### WorkBuddy 技能市场（推荐）

在 WorkBuddy 中搜索「大模型Token成本节约」一键安装。

### 手动安装

```bash
git clone https://github.com/guipi888/workbuddy-llm-token-compressor.git \
  ~/.workbuddy/skills/llm-token-compressor
```

### 环境依赖

请参考 SKILL.md 中的环境要求章节

## 使用

```bash
python3 scripts/pipeline.py <参数>
```

详细参数请参考 SKILL.md

## 输出

请参考 SKILL.md

## 项目结构

```
.gitignore
LICENSE
SKILL.md
assets
references
references/api_reference.md
references/headroom_api.md
scripts
```

## 作者

**guipi888**



## License

MIT License — 详见 [LICENSE](./LICENSE)
