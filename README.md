这里是**C++/C# CLANNAD**群成员互换网站友链用仓库

网站友链数据存放在`friend-sites.json`文件中，该JSON文件顶层结构为`array`，以`[`开头，`array`中包含多个`site`对象，`site`对象格式如下：

```json
{
    "url": "网站URL",
    "title": "网站标题",
    "owner": "站长昵称",
    "introduction": "可选的简介"
}
```

其中`url`、`title`、`owner`字段必须存在，`introduction`为可选字段，同时允许添加除以上字段外其它任意字段

`friend-sites.json`文件示例：

```json
[
    {
        "url": "https://github.com/CPP-CLANNAD",
        "title": "我们的GITHUB主页",
        "owner": "CLANNAD"
    }, {
        // ...
    }, {
        // ...
    }
]
```