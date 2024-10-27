# 类型 Type
类型是描述当前提交性质的枚举类型，含有以下的枚举值:
```
build: Changes that affect the build system or external dependencies (example scopes: gulp, broccoli, npm)
ci: Changes to our CI configuration files and scripts (example scopes: Travis, Circle, BrowserStack, SauceLabs)
docs: 文档相关
feat: 特性增加
fix: 异常修复
perf: 性能优化
refactor: 代码重构
style: 不影响代码含义的改动 (white-space, formatting, missing semi-colons, etc)
test: 对测试的增加或修复
merge: 分支合并（格式 -> orgin_branch into target_branch ）
```
