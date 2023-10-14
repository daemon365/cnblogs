## V2.0.4 Release
[Release v2.0.4 · go-kratos/kratos (github.com)](https://github.com/go-kratos/kratos/releases/tag/v2.0.4)
### 新的功能

- proto-gen-http 工具在生产代码时如果 POST/PUT 接口没有配置 body，或 GET/DELETE 接口配置了 body 时，抛出警告信息
- kratos 命令工具支持生成 proto stream 的 service 模板
- 增强 tracing 中间件
- 修改 grpc gateway 的引用路径 (#1295)
- 添加对 endpoint 的解析器 (#1273)
- kratos 命令行工具处理 proto 时支持指定 third_party 目录 (#1266)
- 添加 transport 的 tls 配置 (#1267)

### 修复问题

- etcd 版本小于 3.13 的阻塞问题 (#1317)
- 升级 etcd 版本 (#1302)
- 某些情况下的 config 功能 data race 问题 (#1316)
- 清理 config 代码 (#1311)
- config 包 Load 时没有设置 source 的 watcher (#1320)
- 修改 blog 示例的 Makefile (#1296)
- 使用测试库的临时目录 (#1289)
- endpoint panic 的问题 (#1291)

### 其他

- 升级示例的依赖版本 (#1314)
- 升级 grpc 版本到 v1.39.1 (#1312)
- 添加 appinfo 单元测试 (#1293)
- 添加 option 单元测试 (#1292)
- 添加 PR 模板 (#1280)
- 添加 selector 中间件的代码注释 (#1275)
- 添加 tls 服务发现的示例 (#1270)

![](https://img2020.cnblogs.com/blog/2344773/202108/2344773-20210819095405541-1280125415.png)
