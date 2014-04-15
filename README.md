说明
================
    1 在当前的SDK版本(3.2.2)里, listview还不支持scroll/scrollend事件(相信后续会添加),带来了一些不便. 官方提供的setMarker比较弱,很多功能不能实现.
    2 由于listview和tableview在原生平台下实现都是一样的, 所以可以将tableview的相关实现移植到listview


使用
================
    1 备份sdk目录中原来的TiUIListView.m实现. 换成这个版本. clean原来的工程, 重新编译. listview就会触发scroll/scrollend事件.
    2 目前版本基于sdk 3.2.2, 其它版本未测试过. 可以参考本代码修改.
    3 安卓版本后续再提供
    4 mac下sdk文件位置为 ~/Library/Application Support/Titanium/mobilesdk/osx/3.2.2.GA/iphone/Classes
