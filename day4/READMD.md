# 更有效率的处理单字符 &undo/redo

## 指令

* 1. 删除光标所在的字符  -> x
2. 删除光标前的字符    -> X
* 3. 删除当前光标的字符并进入 insert 模式 -> s
* 4. 删除当前光标所在行并进入 insert 模式 -> S
* 5. 替换一个字符 -> r
6. 替换多个字符 -> R

## undo 和 redo

```js
function testFor() {
  const obj = {}
}
```