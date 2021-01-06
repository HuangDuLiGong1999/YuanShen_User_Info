This API can only query Chinese servers！！！

# YuanShen_User_Info
原神个人信息查询

写这玩意的原因的方便直接拆穿网图装x的sb

希望米哈游官方人员看到了也别和谐(

# cookie获取
- 复制以下代码

```
var cookie = document.cookie;
var ask = confirm('Cookie:' + cookie + '\n\n是否复制内容到剪切板？');
if (ask == true) {
    copy(cookie);
    msg = cookie;
} else {
    msg = 'Cancel';
}
```

- 按`F12`，打开`开发者工具`，找到`Console`并点击
- 命令行粘贴代码并运行，获得类似`Cookie:xxxxxx`的输出信息
- `xxxxxx`部分即为所需复制的`Cookie`，点击确定复制

# 感谢列表：

[Steesha](https://github.com/Steesha)：帮忙拿到了DS的算法
