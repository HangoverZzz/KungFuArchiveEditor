# 绝世好武功存档修改器

本程序使用.net开发，编译后的程序需要 **.net 6.0** 运行库。

程序使用 **Avalonia** 作为ui库，如果你需要修改这个程序，推荐你先安装Avalonia的相关插件。

当前程序还比较简单，只能修改一些简单的数据。

此外物品名称也不太全，所以修改器看到的有些物品可能是显示未知物品。

如果你知道物品id和名称，欢迎你来提交PR修改。

目前游戏的物品名称使用 [metadata.json](KungFuArchiveEditor/metadata.json) 文件来记录，加载存档时会从这个文件查询物品名称。