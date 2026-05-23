# BoardSecretary OpenClaw Marketplace

This repository hosts the OpenClaw-compatible board secretary capital market workflow plugin.

## Plugin

- `capital-market-project-orchestrator`: 上市总控入口，内置完整董秘体系能力，包含上市总控、人力资源专员、证券事务代表、合规专员、北交所适配、公告信披、财务质量、同业对标、股权治理和三表模型等能力。

## Install

```bash
openclaw plugins install capital-market-project-orchestrator --marketplace https://github.com/guanzigong-agent/openclaw-boardsecretary-marketplace
openclaw plugins enable capital-market-project-orchestrator
```

## WeChat Command

If OpenClaw is connected to WeChat and plugin commands are enabled, send:

```text
/plugin install capital-market-project-orchestrator --marketplace https://github.com/guanzigong-agent/openclaw-boardsecretary-marketplace
```

Then, if needed, send:

```text
/plugin enable capital-market-project-orchestrator
```

## Test

```text
使用 上市总控，帮我生成新三板挂牌项目总控表。
```