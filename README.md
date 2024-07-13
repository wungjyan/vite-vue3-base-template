# 说明

目前是基于 Vite5、Vue3 和 TypeScript 搭建的基础开发模板。主要做了以下配置：

- 集成 `eslint@9` 和 `prettier`，实现代码检查以及代码保存时自动格式化；
- 集成 `husky` 搭配 `lint-staged`，实现代码提交前的语法检查；
- 集成 `commitlint` 结合 `husky`，实现提交信息的检查，规范 git commit 描述信息；
- 集成 `czg`，实现终端可视化生成 git commit 描述信息。

更多的功能可以根据具体项目添加。
