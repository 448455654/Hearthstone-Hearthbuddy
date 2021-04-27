# Hearthstone-Hearthbuddy
Hearthstone 炉石传说  
Hearthbuddy 炉石兄弟  

## 存储炉石兄弟 Store Hearthstone Hearthbuddy
搜索此项目，Github搜索Hearthbuddy或者炉石兄弟  
github search for Hearthbuddy or 炉石兄弟  

[点我进入压缩包下载页面releases download](https://github.com/lesuixin/Hearthstone-Hearthbuddy/releases)

## ✔可以使用的版本 can use versions --suixin
```diff
+ 怒风3.27版Hearthbuddy，Stormrage 3.27 Hearthbuddy version
+ 怒风版Hearthbuddy_04.11V版，Stormrage Hearthbuddy_04.11V version
第一次使用方法：下载解压缩打开Hearthbuddy.exe，提示长时间没用过期，随便输入q确认，再次打开，解压缩的目录下有个HB机器码.txt文件打开，用注册机KeyGen，复制转换，输入弹出框里，DefaultBot对战模式选自动，修改卡组名称点start
怒风旧版提示下载更新，需要修改时间到2021年4月25日

The first time instructions: Download unzip open Hearthbuddy.exe, prompt expired ,just enter q confirm, open again ,under unzip contents have HB机器码.txt open it,use KeyGen, copy machine code click transform, copy activation code , DefaultBot battle mode choose 自动, modify卡组名称 click start
Stormrage version prompt update, need change time to 2021-4-25

+ 卡卡版HB限酒馆战旗，kaka version only Tavern Chess
使用方法：复制机器码转换，输入激活码，配置-版本-游戏模式-玩家对战模式，修改游戏模式为战旗模式，点开始
Instructions: copy machine code click transform, enter activation code, 配置-版本-游戏模式-玩家对战模式，change game mode to Tavern Chess mode, click 开始

+ 多版本机器码注册机KeyGen，左边选项从上到下折腾贴吧版，云骋版，卡卡版，怒风版 中间上面机器码，下面激活码  
Multi-version machine code registrar , Left option from top to bottom 折腾版，云骋版，kaka,Stormrage, Above machine code and below activation code  
使用方法：使用需要码的版本，复制机器码点转换，输入激活码，确定。use need code version, copy machine code click transform, copy activation code ,sure.  
注册机KeyGen修改时间到2021年4月15日 KeyGen change time to 2021-4-15

不要连续使用太长时间，会被检测到，虽然通常会掉线。Don't use it for too long continuously, it will be detected, although it usually leaves game.
曾经在这游戏里互相投降就是互相胜利。Once in this game mutual surrender is mutual victory.
在游戏之外打牌。Play card outside of the game.
```

### 修改文件时间 change file time
```diff
+ 启动器.bat starter.bat 修改文件时间 change file time
+ 怒风旧版需要修改时间到2021年4月25日，注册机KeyGen修改时间到2021年4月15日
Stormrage version need change time to 2021-4-25, KeyGen change time to 2021-4-15

在文件目录下新建文件文本文档.txt，复制粘贴以下内容，改后缀.bat保存运行
under contents new a .txt file, copy and paste, change to .bat save and run

@echo off
set d=%date%
cd /d %~dp0
::此处通常设置为兄弟版本后一天
date 2021-4-25
::此处后面注意添加%1 %2用以传递自动开始的参数
start Hearthbuddy.exe %1 %2
ping 127.0.0.1 -n 5 >nul
date %d%
exit
```

### 版本相关问题 version related questions
```
怒风版3.27版改时间一样可以用，4.17新版本不能用注册机的旧码
怒风版类似整合版，怒风版的策略不在Routines里，策略打包在程序里没法换，Silverfish\cards下没有卡牌信息，留牌策略还在

Stormrage 3.27 version change time can use , new 4.17 version can't use KeyGen code
Stormrage versions like integrated version, Stormrage versions tactics in .exe file can't change ,no card in Silverfish\cards, reserved Cards tactics exist

来自ptoken
怒风3.27版本的基本可以在绳子出现前结束回合 
怒风3.27版，打开后会有一个弹窗，目前来看改时间需要到3.27比较合适，但是还是会出现一个无伤大雅的弹窗，使用火绒或者其他弹窗拦截软件标记两次就可以了。

Stormrage 3.27 version basically before the rope appeared end round
Stormrage 3.27 version open and have a Pop-up window, change start Hearthbuddy time to 2021.3.27

修改ai计算操作间隔，修改Main里MsBetweenTicks计算间隔到15或以下，InputEventMsDelay操作间隔到30或以下
Change ai calculation interval, modify Main MsBetweenTicks to less 15, InputEventMsDelay to less 30

云骋版旧版本要改时间，被要求更新，新版本能用注册机的旧码
云骋版 old versions need change time, are asked for update , new version can use KeyGen code
```

## 🚫不建议使用的版本 Not suggested to use versions --suixin
```diff
- 2021.4.1折腾版，炉石兄弟贴吧，需要激活码 2021.4.1 version Use machine code
- 2021.4.1折腾版需要覆盖20210109折腾版，need use 2021.4.1 version over 20210109 version
- 20210401折腾版，炉石兄弟贴吧，20210401 version，相当于完整2021.4.1折腾版，不需要覆盖，需要激活码 like complete 2021.4.1 version, no need over and use machine code

- 贴吧版本被关闭，提示版本关停，不可用 tieba 2021.4.1 version closed, prompt version shutdown,unavailable
- 原本ai计算就全在本地运算，贴吧版的多了云端验证
- 打开兄弟时会访问gitee上预留的一个json文件。共2个值，一个控制是否进入，一个控制显示公告。抓个包就能看到。

- Original ai calculate locally, tieba 2021.4.1 version use cloud verification
- When open 2021.4.1 version Hearthbuddy will check a .json file in gitee.com. Two values, one value control can or can not enter, the other control show announcement.

2021-04-22 来自贴吧忽然之间 4.1折腾版绕过验证正常使用的方法 2021.4.1 version instructions
首先要去下一个Fiddler用来调试抓包，主要用的是它一个自动响应的功能。简单点来说就把发向服务器的请求直接拦截替换成你想给的回复。
GET https://gitee.com/yl-hb/check_hb/raw/master/%2020210401check.json 内容是{"state": "0", "tips": "版本关停"}
从图中可以看到失败的请求，把这个请求替换成我们想要的返回内容{"state": "1", "tips": ""}
每次用都要抓包。设置好规则保存，每次开兄弟前把抓包软件启动即可。
```

### 整体策略 total tactics
```
策略添加，删除复制粘贴Routines文件夹 copy and paste Routines
插件在Plugins文件夹

小小不哭的故事的2021.1.1 Routines新
小小不哭的故事的2020.12.18 Routines旧
2021.1.1 Routines新奥秘法会用非公平游戏和同时期的卡，DefaultBehavior选rush，2021.1.1 Routines新 Secret Mage can use unfair game and same period card, DefaultBehavior choose rush

留牌策略 Reserved Cards tactics
留牌策略是在Routines\DefaultRoutine\Silverfish\behavior\要调整的策略文件夹\_mulligan.txt
```

### 旧版本 old versions
```
20210109折腾版，炉石兄弟贴吧，20210109 version
炉石兄弟修复版2020-5-17，需要输入地址对应验证，2020-5-17 version
奥秘法2020.1.17，Secret Mage 2020.1.17 version
整合版2020.10[3.2.7601.15205]，使用策略需要码，Integrated version 2020.10[3.2.7601.15205] version

可能的新版本 maybe new versions
2019.8.17（无壳），来自maxiori，没有DNGuard壳 No DNGuard Shell，可以反编译，Can be decompiled 需要更新，need to be updated
github搜索maxioriv，github search for maxioriv
```

### 旧版本修改建议来自别人 old versions modify suggestions from others
旧版本运行“开始”就会闪退，总的来说有三个地方要改。  
一是卡组的信息，原来有个isWild字段表示卡组是否为狂野卡组，现在改成了一个枚举类型，有经典 狂野 标准三种值  
二是游戏模式定义，以前也是一个bool值表示是否为狂野，另外还有一个bool值表示是否为休闲模式。现在同样改成了一个枚举值，有经典 狂野 标准 休闲四个值。  
三是卡牌信息对应的EntityBase类里有个GetSpellPower的函数没了，因为现在的法术强度有了不同属性，所以获取法术强度的函数也做了相应的变更  

#### 2021年4月炉石传说退环境更新经典模式，修改了模式选择，无法继续使用旧版本
#### April 2021 Hearthstone: Forged in the Barrens. Modified mode selection. No longer available old versions

### 其它方法 Other methods
如果没有炉石兄弟，没有备用办法？安卓模拟器，模拟点击，硬件宏软件宏，ahk，代挂等等  
If have not Hearthbuddy, no plan b? Android simulator, simulate click ,Hardware macro Software macro, ahk, proxy run etc.  

### 参与
提交issue You can open [issue](https://github.com/lesuixin/Hearthstone-Hearthbuddy/issues/new)
