# BoardSecretary OpenClaw Marketplace

This repository hosts OpenClaw-compatible plugins for board secretary capital market workflows.

## Plugin

- `capital-market-project-orchestrator`: 上市总控，用于统筹新三板挂牌、股改、治理规范、尽调、披露、财务质量、同业对标、股权结构、北交所/创业板/IPO 准备和中介协调。

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

Then send:

```text
/plugin enable capital-market-project-orchestrator
```

## Test

```text
使用 上市总控，帮我生成新三板挂牌项目总控表。
```
