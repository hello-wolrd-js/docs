# 什么是 Hello-World-Js?

Hello-World-Js(以下简称 hwj)是一个用于构建 iframe-like 内容平台的框架

hwj 维护一个 web 应用内容平台(就像应用商店一样!),并提供 API 用于开发可嵌入平台的 web 应用(以下简称为世界)

例如:

你可以将你用 Vuejs 编写的一个 web 应用,通过特定的构建流程嵌入至 hwj 内

## Syntax Highlighting

VitePress provides Syntax Highlighting powered by [Shiki](https://github.com/shikijs/shiki), with additional features like line-highlighting:

**Input**

````
```js{4}
export default {
  data () {
    return {
      msg: 'Highlighted!'
    }
  }
}
```
````

**Output**

```js{4}
export default {
  data () {
    return {
      msg: 'Highlighted!'
    }
  }
}
```

## Custom Containers

**Input**

```md
::: info
This is an info box.
:::

::: tip
This is a tip.
:::

::: warning
This is a warning.
:::

::: danger
This is a dangerous warning.
:::

::: details
This is a details block.
:::
```

**Output**

::: info
This is an info box.
:::

::: tip
This is a tip.
:::

::: warning
This is a warning.
:::

::: danger
This is a dangerous warning.
:::

::: details
This is a details block.
:::

## More

Check out the documentation for the [full list of markdown extensions](https://vitepress.dev/guide/markdown).
