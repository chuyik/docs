---
title: "API: layout 属性"
description: layouts 根目录下的所有文件都属于个性化布局文件，可以在页面组件中利用 layout 属性来引用。
---

# layout 属性

> `layouts` *根*目录下的所有文件都属于个性化布局文件，可以在页面组件中利用 `layout` 属性来引用。

- **类型：** `String` (默认值： `'default'`)

使用 `layout` 属性来为页面指定使用哪一个布局文件：

```js
export default {
  layout: 'blog'
}
```

在上面的例子中， Nuxt.js 会使用 `layouts/blog.vue` 作为当前页面组件的布局文件。

看下 [示例视频](https://www.youtube.com/watch?v=YOKnSTp7d38) 立刻体验下。

想进一步了解页面布局在 Nuxt.js 里面是如何运作的话，请参考 [布局文档](/guide/views#布局)。
