# Koa2 & TypeScript2

> 这是一个基于Koa2和TypeScript的nodejs项目。

### todo

- [x] 实时监测
- [x] sourcemap debug
- [x] restful api
- [x] jade模版
- [x] logger
- [x] 路由自动匹配controller
- [x] 统一数据返回格式
- [ ] 自动完成api文档

### dev

```
npm i & typings i

# watch&build typescript
tsc

# server
npm run dev
```

### directory

```
.
├── build 转换后的js
├── node_modules
├── src ts目录
	├── controller 对应路由
	├── log 日志文件夹
	├── model mongoodb Schema
	├── util
├── static 静态代理文件夹
├── views jade模版
├── package.json
├── tsconfig.json ts配置文件
├── typings.json
└── README.md
```