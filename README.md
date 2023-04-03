# eslint-config-vue-standard

自定义 Vue2 eslint 配置。

## 使用

安装依赖：

```sh
yarn add @loongwoo/eslint-config-vue-standard -D
# or
npm install @loongwoo/eslint-config-vue-standard --save-dev
```

打开 `.eslintrc.js` 文件配置。修改 `extends` 选项，增加 `@loongwoo/vue-standard`：

```js
module.exports = {
  ...
  extends: [..., '@loongwoo/vue-standard']
}
```
