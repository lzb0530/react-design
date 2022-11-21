### 项目组成
构建项目 pnpm + monorepo
核心技术 react + TypeScript
代码校验 ESLint

### 提交规范
`英文的冒号+空格+信息`
##### commit 提交规范如下
`type(scope): \<subject>`
| 类型     | 描述                                                   |
| :------- | :----------------------------------------------------- |
| build    | 打包                                                   |
| CI       | CI相关修改                                             |
| feat     | 新功能                                                 |
| fix      | 修复bug                                                |
| refactor | 代码重构                                               |
| perf     | 优化相关（性能、体验等等）                             |
| chore    | 改变构建流程、添加工程化脚本，或者增加依赖、库、工具等 |
| revert   | 回滚上一个版本                                         |
| docs     | 仅修改文档                                             |
| style    | 修改空格、缩进、符号等不影响功能                       |
| test     | 测试用例                                               |


例如：git commit -m 'feat: 新增了button按钮组件'