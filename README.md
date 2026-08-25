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

## 来源与许可

本仓库是 [miantiao-me/Sink](https://github.com/miantiao-me/Sink) 的 Fork，其源项目为 [ccbikai/Sink](https://github.com/ccbikai/Sink)。项目依据 [GNU Affero General Public License v3.0](./LICENSE) 发布，部署修改版时应按许可证要求向网络用户提供对应源码。

上游版权归 Sink 原作者及贡献者所有。该 Fork 继续受 AGPL-3.0 约束，Fork 关系不会把上游版权转移给仓库所有者。

完整归属与适用范围见 [NOTICE](./NOTICE) 与 [LICENSE_SCOPE.md](./LICENSE_SCOPE.md)。
