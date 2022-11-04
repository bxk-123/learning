# demo

This template should help get you started developing with Vue 3 in Vite.

## Recommended IDE Setup

[VSCode](https://code.visualstudio.com/) + [Volar](https://marketplace.visualstudio.com/items?itemName=Vue.volar) (and disable Vetur) + [TypeScript Vue Plugin (Volar)](https://marketplace.visualstudio.com/items?itemName=Vue.vscode-typescript-vue-plugin).

## Type Support for `.vue` Imports in TS

TypeScript cannot handle type information for `.vue` imports by default, so we replace the `tsc` CLI with `vue-tsc` for type checking. In editors, we need [TypeScript Vue Plugin (Volar)](https://marketplace.visualstudio.com/items?itemName=Vue.vscode-typescript-vue-plugin) to make the TypeScript language service aware of `.vue` types.

If the standalone TypeScript plugin doesn't feel fast enough to you, Volar has also implemented a [Take Over Mode](https://github.com/johnsoncodehk/volar/discussions/471#discussioncomment-1361669) that is more performant. You can enable it by the following steps:

1. Disable the built-in TypeScript Extension
    1) Run `Extensions: Show Built-in Extensions` from VSCode's command palette
    2) Find `TypeScript and JavaScript Language Features`, right click and select `Disable (Workspace)`
2. Reload the VSCode window by running `Developer: Reload Window` from the command palette.

## Customize configuration

See [Vite Configuration Reference](https://vitejs.dev/config/).

## Project Setup

```sh
npm install
```

### Compile and Hot-Reload for Development

```sh
npm run dev
```

### Type-Check, Compile and Minify for Production

```sh
npm run build
```

### Lint with [ESLint](https://eslint.org/)

```sh
npm run lint
```

## 🧱 如何提交的代码
1、git add .
> 本项目使用 husky 来拦截不符合要求的 commit（纳入版本库使用npm run commit）: 
type（单选）（必填）
    feat 一个新的功能
    fix 修复了一个bug
    docs 仅仅是文档的变动
    style 样式的改动
    build 影响构建系统的改动，例如修改package， 打包配置文件等
    chore 不修改src目录以及test目录下的其他修改
    ci 更改ci配置文件和脚本
    perf 提高性能的代码更改
    refactor 既不修复错误也不添加功能的更改
    revert 回滚
    test 添加测试文件或者更改现有的测试文件
scope 此更改的范围是什么（例如组件或文件名）（选填）
subject 一个简短描述来说明此次更新（必填）
body 提供更为详细的描述信息（选填）
footer 可以是关闭的issue的id （选填）

最后git push origin (分支名)  完成提交

## 涉及相关技术说明

| 名称           | 地址                                         |
| -------------- | -------------------------------------------- |
| Vue3           | <https://vuejs.org/>                         |
| TypeScript     | <https://www.typescriptlang.org/>            |
| Vite           | <https://cn.vitejs.dev/>                     |
