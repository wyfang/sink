# Sink

完全运行在 Cloudflare 上的短链接服务，提供自定义路径、有效期与访问分析。

[在线演示](https://sink.cool/dashboard) · [上游项目](https://github.com/ccbikai/Sink)

## 功能

- 创建短链接并自定义大小写敏感路径
- 设置链接有效期
- 查看访问统计与分析维度
- 使用 AI 生成短路径
- 通过 OpenAPI 接入自动化工具

## 开始

需要 Node.js 20.11+ 与 pnpm 10：

```bash
pnpm install
pnpm dev
```

项目支持 [Cloudflare Workers](./docs/deployment/workers.md) 与 [Cloudflare Pages](./docs/deployment/pages.md)，Workers 为推荐方案。部署前按[配置文档](./docs/configuration.md)设置站点 Token、KV、Analytics Engine 与可选服务密钥；不要提交真实 Token。

## 版权说明

本项目是 [miantiao-me/Sink](https://github.com/miantiao-me/Sink) 的 Fork，原项目为 [ccbikai/Sink](https://github.com/ccbikai/Sink)，依据 [GNU Affero General Public License v3.0](./LICENSE) 发布。上游版权归原作者及贡献者所有；个人品牌和素材不在许可范围内。
