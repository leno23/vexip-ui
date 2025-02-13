### Textarea Props

| Name             | Type                                             | Description                                 | Default              | Since |
| ---------------- | ------------------------------------------------ | ------------------------------------------- | -------------------- | ----- |
| state            | `'default' \| 'success' \| 'error' \| 'warning'` | 输入框的状态                                | `'default'`          | -    |
| value            | `string`                                         | 设置输入框的值                              | `''`                 | -    |
| placeholder      | `string`                                         | 设置输入框的占位                            | `locale.placeholder` | -    |
| rows             | `number`                                         | 设置输入框的默认行数                        | `2`                  | -    |
| no-resize        | `boolean`                                         | 是否禁用缩放功能                            | `false`              | -    |
| autofocus        | `boolean`                                        | 设置输入框的自动聚焦                        | `false`              | -    |
| spellcheck       | `boolean`                                        | 设置输入框的拼写检查                        | `false`              | -    |
| autocomplete     | `boolean`                                        | 设置输入框的自动完成                        | `false`              | -    |
| readonly         | `boolean`                                        | 设置输入框的只读属性                        | `false`              | -    |
| disabled         | `boolean`                                        | 设置是否禁用输入框                          | `false`              | -    |
| debounce         | `boolean`                                        | 开启防抖，当快速输入时只触发一次 `input` 事 | `false`              | -    |
| max-length       | `number`                                         | 设置输入内容的最大长度，值为 `0` 时不限     | `0`                  | -    |
| disable-validate | `boolean`                                        | 是否禁用触发表单字段验                      | `false`              | -    |

### Textarea Events

| Name      | Description                                  | Parameters                                  | Since |
| --------- | -------------------------------------------- | ------------------------------------------- | ----- |
| focus     | 输入框聚焦时触发，返回事件对象               | `(event: FocusEvent)`                       | -     |
| blur      | 输入框失去焦点时触发，返回事件对象           | `(event: FocusEvent)`                       | -     |
| change    | 当输入框值改变时触发，返回读取后的值和原始值 | `(accessedValue: any, originValue: string)` | -     |
| input     | 当键入了值时触发，返回读取后的值和原始值     | `(accessedValue: any, originValue: string)` | -     |
| enter     | 当键入回车时触发，返回按键事件               | `(event: KeyboardEvent)`                    | -     |
| key-down  | 当键按下时触发，返回按键事件                 | `(event: KeyboardEvent)`                    | -     |
| key-press | 当键按住时触发，返回按键事件                 | `(event: KeyboardEvent)`                    | -     |
| key-up    | 当键松开时触发，返回按键事件                 | `(event: KeyboardEvent)`                    | -     |
| clear     | 当通过清除按钮清空值时触发，无返回值         | -                                           | -     |
