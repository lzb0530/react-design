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

### ESLint
`主要有以下特点：`
默认规则包含所有 JSLint、JSHint 中存在的规则，易迁移；
规则可配置性高：可设置「警告」(warning)、「错误」(error)两个 error 等级，或者直接禁用；
包含代码风格检测的规则（可以丢掉 JSCS 了）；
支持插件扩展、自定义规则。
ESLint配置方式，可以通过以下三种方式配置 ESLint:
使用 .eslintrc 文件（支持 JSON 和 YAML 两种语法）；
在 package.json 中添加 eslintConfig 配置块；
直接在代码文件中定义。
我们选择使用 .eslintrc 文件方式！！！
`规则的严重性(rule severity)`
"off"
or 0 - turn the rule off 不验证 "warn"
or 1 - turn the rule on as a warning(doesn’ t affect exit code) 警告 "error"
or 2 - turn the rule on as an error(exit code is 1 when triggered) 错误（ 如有） 规则的选项(additional options)  "quotes": [2, "double"]
