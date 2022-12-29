[![npm](https://img.shields.io/npm/v/typescript-call-graph)](https://www.npmjs.com/package/typescript-call-graph)

# TypeScript Call Graph

该**CLI**将为TypeScript文件创建并生成所有的函数调用关系图。

⚠️ 这是一项正在进行的工作🚧 欢迎更多可视化贡献

![image](https://user-images.githubusercontent.com/17264277/85908941-62ba6d00-b7e5-11ea-8e50-2686990aa4f5.png)

## 如何使用

全局安装

```sh
npm install -g typescript-call-graph
```

在任何的文件目录，运行:

```sh
tcg
```
它将提醒你如何使用CLI: 您需要指定特定的文件或全局的（通配符路径）：

```sh
tcg myFile.ts folder/* anotherFolder/**/*
```

## 开发

克隆仓库. 编辑 `index.ts` 或者 `extract.ts` 然后执行 `npm start` 构建以生成更改, 执行 `npm test` 来对仓库中的文件运行CLI.

非常欢迎有关如何改进此CLI的建议或PR。

您还可以根据需要编辑此存储库，并使用`npm run global`安装自定义版本的`tcg`命令。

### 感谢

- [Matteo Abrate](https://observablehq.com/@nitaku/tangled-tree-visualization-ii) for the _tangled tree visualization_
- [Mike Bostock](https://observablehq.com/@d3/arc-diagram) for the _arc diagram_
- [GraphViz](https://graphviz.org/), [node-graphviz](https://github.com/glejeune/node-graphviz), and [d3-graphviz](https://github.com/magjac/d3-graphviz) for the simple graph
- [Mermaid-JS](https://github.com/mermaid-js/mermaid) for a way to create a graph
- [Tutorial](https://convincedcoder.com/2019/01/19/Processing-TypeScript-using-TypeScript/) and code for processing TypeScript (AST)
- [Tutorial](https://developer.okta.com/blog/2019/06/18/command-line-app-with-nodejs) for creating a *CLI*
- [TS-Call-Graph](https://github.com/Deskbot/TS-Call-Graph) for inspiration
