## V2.0.5 Release

[Release v2.0.5 · go-kratos/kratos (github.com)](https://github.com/go-kratos/kratos/releases/tag/v2.0.5)

### 修复问题

- proto errors when swagger api import kratos errors ([#1348](https://github.com/go-kratos/kratos/pull/1348))
- 当ctx不是kratos的context，则app.Name()会导致panic ([#1338](https://github.com/go-kratos/kratos/pull/1338))
- 当使用 monorepo 目录结构时，使用 kratos run 命令，选择非最后一个服务启动时，执行目录错误([#1336](https://github.com/go-kratos/kratos/pull/1336))
- 在 config.yaml 支持冒号作为默认值 ([#1332](https://github.com/go-kratos/kratos/pull/1332))
- 修复config watcher的goroutine泄露([#1327](https://github.com/go-kratos/kratos/pull/1327))

### 优化

- 优化 polish watcher ([#1341](https://github.com/go-kratos/kratos/pull/1341))

### 其他

- 模板内使用tab代替空格 ([#1352](https://github.com/go-kratos/kratos/pull/1352))
- 优化代码和使用golangcli-lint检查错误 ([#1298](https://github.com/go-kratos/kratos/pull/1298))
- 添加metadata测试用例 ([#1324](https://github.com/go-kratos/kratos/pull/1324))

![](https://img2020.cnblogs.com/blog/2344773/202108/2344773-20210819095405541-1280125415.png)