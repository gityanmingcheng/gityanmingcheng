1. github状态信息-api

1.1 账户信息统计 
![GitHub账户信息统计](https://github-stats.ubrong.com/api?username=ubrong&show_icons=true&theme=tokyonight)

参数说明：
username [必填] (string) 被统计信息的github用户名
show_icons [可选] (boolean) false不显示图标,true显示图标
theme [可选] (string) 主题（可用值：default, dark, radical, merko, gruvbox, tokyonight, onedark, cobalt, synthwave, highcontrast, dracula）
账户信息统计

1.2 最常用语言
![GitHub账户最常用语言](https://github-stats.ubrong.com/api/top-langs/?username=ubrong&layout=compact&theme=tokyonight)

参数说明：
layout [可选] (string) 布局（可用值：default, compact）
最常用语言

1.3 repo卡片
![GitHub仓库信息卡片](https://github-stats.ubrong.com/api/pin/?username=ubrong&repo=phoneweb-base&theme=dark)

参数说明：
repo [必选] (string) 仓库名称
repo卡片


2.  社交统计
![github统计](https://stats.justsong.cn/api/github?username=ubrong&theme=dark&lang=zh-CN)
![B站统计](https://stats.justsong.cn/api/bilibili/?id=1643462710&theme=dark)

支持平台与链接示例：
GitHub：https://stats.justsong.cn/api/github?username={username:string}
知乎：https://stats.justsong.cn/api/zhihu?username={username:string}
B 站：https://stats.justsong.cn/api/bilibili/?id={uid:int}
LeetCode 英文站：https://stats.justsong.cn/api/leetcode/?username={username:string}
LeetCode 中文站：https://stats.justsong.cn/api/leetcode?username={username:string}&cn=true
LeetCode 中文站英文站双修：https://stats.justsong.cn/api/leetcode?username={username:string}&={cn_username:string}
掘金：https://stats.justsong.cn/api/juejin?id={uid:int}
CSDN：https://stats.justsong.cn/api/csdn?id={uid:string}
牛客：https://stats.justsong.cn/api/nowcoder?id={uid:int}
社交统计

3. 统计访问次数

![Visitor Count](https://profile-counter.glitch.me/{ubrong}/count.svg)
说明：
{ubrong}替换为自己的标记，建议使用 github用户名。注意这个值可以是任意的，因为它仅是一个标记。
统计访问次数

4. 徽标

![tip](https://badgen.net/badge/php/8.1/orange?icon=php)
![tip](https://badgen.net/badge/python/3.1.6/green?icon=packagephobia)

badgen的url格式说明：
https://badgen.net/badge/{subject}/{status}/{color}?icon=github
subject (string) 徽标左侧文字，如：node  
status (string) 徽标右侧文案，如：16.0.1  
color (string) 徽标右侧背景色，如：red,green等  
icon (string) 图标，如：git,github,wiki等  
徽标
