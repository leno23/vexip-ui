### Basis Usage

通过 `open` 方法打开一条纯文字的提示。

该方法可以接收一个字符串或对象，传入字符串时将作为提示内容，传入对象可以更细粒度地控制提示属性，具体可选属性参考 api 说明。

组件根据 `title` 和 `content` 属性有无的情况，会分别渲染成正常、仅标题和仅内容三重状态。
