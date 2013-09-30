EverEdit支持丰富的自动完成样式，不仅可以完成预定义关键字、上下文出现过的单词、snippet的触发字，还可以通过插件扩展显示更多的内容。

##显示样式
自动完成出现的每个单词都有明确的意义和分组。EverEdit默认的自动完成器的意义如下:

```
*:表示这是一个关键字
-:表示这是一个上下文出现过的单词
@:表示这是一个snippet
~:文件名称
#:ctags生产的关键字
```

##快速选取
使用箭头进行上下选区，默认的选定快捷键是回车。可以在选项里面更改，设置→常规→编辑→自动完成→触发键。同时还可以使用Alt+1~Alt+9进行迅速选取。

##设置显示顺序(3.0以上支持)
EverEdit支持调整自动完成中出现的单词的优先级，设置→常规→编辑→自动完成→显示顺序。您可以根据自己的喜好设置显示顺序，比如把本文中出现的单词设置为最高等。

##添加词汇至自动完成
一般的情况下，用户如果需要显示单词到自动完成中的话，可以修改或者增加关联的snippet，或者修改语法文件中由CreateWord创建的单词表。具体请参考语法着色。
