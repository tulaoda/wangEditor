# @mlamp/editor

### fork from wangEditor

![build badge](https://github.com/wangeditor-team/wangEditor/workflows/build/badge.svg)

轻量级 web 富文本编辑器，配置方便，使用简单。

- 官网 [www.wangEditor.com](http://www.wangeditor.com/)
- 文档 [www.wangEditor.com/doc](http://www.wangeditor.com/doc/)

![](./docs/imgs/demo.png)

当前是 `v4` 版本。想继续使用 `v3` 版本看[这里](http://www.wangeditor.com/doc/pages/01-%E5%BC%80%E5%A7%8B%E4%BD%BF%E7%94%A8/08-%E4%BD%BF%E7%94%A8V3%E7%89%88%E6%9C%AC.html)。

## 浏览器兼容性

兼容常见的 PC 浏览器：Chrome，Firefox，Safar，Edge，QQ 浏览器，IE11 。

不支持移动端。

## 基本使用

npm 安装 `npm i @mlamp/editor --save` ，几行代码即可创建一个编辑器

```js
import E from "@mlamp/editor";
const editor = new E("#div1");
editor.create();
```

更多使用方法，可参考[文档](http://www.wangeditor.com/doc/)。
