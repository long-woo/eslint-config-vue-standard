# eslint-config-vue-standard

自定义 Vue eslint 配置。

## 使用

安装依赖：

```sh
yarn add @longwoo/eslint-config-vue-standard -D
# or
npm install @longwoo/eslint-config-vue-standard --save-dev
```

打开 `.eslintrc.js` 文件配置。修改 `extends` 选项，增加 `@longwoo/vue-standard`：

```js
module.exports = {
  ...
  extends: [..., '@longwoo/vue-standard']
}
```
