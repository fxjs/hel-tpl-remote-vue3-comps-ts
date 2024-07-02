# hel-tpl-remote-vue3-comps-ts
A simple remote vue3 comp template(typescript、dev with vite or webpack, build with webpack )

## 环境准备
```text
node >= 16.14.0 (推荐：16、18)
pnpm 8.15.8 （推荐使用`pnpm`包管理工具）
@vue/cli 5.0.8 （安装：pnpm i @vue/cli -g）
```

## 启动项目
- vite 开发
```bash
pnpm run start:vite
```

- webpack 开发
```bash
pnpm run start
```

- 打包与发布

**先修改版本号**，再执行打包与发布命令（这点很重要，顺序不能弄反为：先构建再修改版本号），基于webpack构建：
```
pnpm run build
npm publish
```

---

