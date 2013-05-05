#iMessage Sender

##用Alfred 2 给自己的iPhone发送常用信息

运行的Apple Script脚本如下：


tell application "Messages"
set myid to get id of first service
set theBuddy to buddy "输入你要发送的手机号" of service id myid
send "{query}" to theBuddy
end tell

使用方法：安装完成后请在脚本里输入你自己的手机号码，然后输入imessage 加短信内容即可。

详见我的博客：[http://v2ex.me/imessage-sender/](http://v2ex.me/imessage-sender/)