# BoardSecretary OpenClaw Marketplace

This repository hosts OpenClaw-compatible plugins for board secretary capital market workflows.

## Recommended Plugin

- `boardsecretary-full-suite`: 董秘完整体系，包含上市总控、人力资源专员、证券事务代表、合规专员、北交所适配、公告信披、财务质量、同业对标、股权治理和三表模型等能力。

## Optional Single Plugin

- `capital-market-project-orchestrator`: 上市总控，用于统筹新三板挂牌、股改、治理规范、尽调、披露、财务质量、同业对标、股权结构、北交所/创业板/IPO 准备和中介协调。

## Install Full Suite

```bash
openclaw plugins install boardsecretary-full-suite --marketplace https://github.com/guanzigong-agent/openclaw-boardsecretary-marketplace
openclaw plugins enable boardsecretary-full-suite
```

## WeChat Command

If OpenClaw is connected to WeChat and plugin commands are enabled, send:

```text
/plugin install boardsecretary-full-suite --marketplace https://github.com/guanzigong-agent/openclaw-boardsecretary-marketplace
```

Then, if needed, send:

```text
/plugin enable boardsecretary-full-suite
```

## Test

```text
使用 上市总控，帮我生成新三板挂牌项目总控表。
```