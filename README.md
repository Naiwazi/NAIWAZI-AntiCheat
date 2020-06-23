# NAIWAZI-AntiCheat For 7DTD A18.4 && NAIWAZI-反作弊 支持 七日杀A18.4
---
This is an Anti-Cheat MOD for 7 Days to Die Dedicated Server, [Download](https://github.com/Naiwazi/NAIWAZI-AntiCheat/releases/download/v1.0.0/Naiwazi_AntiCheat.zip)<br />
这是一款用于七日杀服务器端的反作弊插件, [点此下载](https://github.com/Naiwazi/NAIWAZI-AntiCheat/releases/download/v1.1.0/Naiwazi_AntiCheat.zip)<br />
<br />
v1.1.0 Updates<br />
v1.1.0 更新内容<br />
1.Single block damage checking<br />
1.单物块伤害检测<br />
2.Single entity damage checking<br />
2.实体伤害检测<br />
3.Multiple blocks removement checking, it can prevent buildings or blocks from being removed by "k KEY" or the tool "meleeToolBlockReplaceTool" in the NETWORK LAYER<br />
3.多物块消除检测，完全免疫替换扳手和K键拆家，当K键拆家时，会拒绝相应的同步请求。<br />
4.prevent players or entities from being killed by the 'kill' or 'killall' command excuted by local console<br />
4.屏蔽本地执行'kill'或者'killall'杀死实体或者玩家<br />
5.checking for player's attribute including health, level, jump strength, speed and so on<br />
5.人物属性包括血量，等级，跳跃高度，速度检测<br />
checking for skill points<br />
6.技能点检测<br />
NOTE: any details of the configuration refers to the config file(XML). If any warnings about HOOK appeared, that is means the related method is hooked by other mods, the option will not be effected.<br />
详细说明请参照配置文件，载入时如果有黄字关于HOOK的错误，说明已经有MOD进行了相关函数的HOOK，相关功能就不能生效了<br />

 <br />
`It not only can check players' inventory but also can check the loots on map`<br />
`它不仅可以检测玩家的背包物品，还可以检测地图上的储物容器，包括储物箱，上锁储物箱，熔炉工作台等等`<br />
<br />
GOD mode and INVISIBLE mode detection is also supported<br />
支持 上帝模式 和 隐身模式 的实时检测<br />
<br />
Stack Overflow can be checked to prevent server from crashing!<br />
可以检测人物档和储物箱熔炉等地图容器中的物品超叠,支持自动删除问题物品,防止超叠引起的服务器崩溃及红字。<br />
<br />
Paramters can be set by yourself, and log files will show you the details of what happend, Additionally, Console command is also supported (command: naiwazi_anticheat), any server tools or manage tools can get infomation through Telnet or web console.<br />
可自由设置反作弊的各种参数, 日志文件会记录下每一个细节, 另外还提供后台命令API方式(后台命令naiwazi_anticheat)，通过可登录TELNET的服主工具或者自用工具拉取信息。<br />
<br />
Do not need any depends<br />
不需要任何服主工具，GPS等插件的支持。<br />
<br />
<br />
`Usage:`<br />
`使用方法: `<br />
<br />
将`Naiwazi_AntiCheat`文件夹拷贝进服务端根目录的Mods文件夹, 运行服务端即可，第一次运行会在`存档根目录`生成 `naiwazi_anticheat_xxx.xml` 配置文件, 请参照配置文件中的注释耐心配置, 默认的日志文件也会在同文件夹下生成, 任何对设置的改动，除注释中有说明外，其余均实时生效，无需重启服务端。<br />
注意：国内服主首次运行请仔细配置文件，配置文件中有详细说明，白名单一定要配置好，语言改成cn，不然出来的任何提示全是英文。
<br /><br />
Copy the folder `Naiwazi_AntiCheat` to GameFolder/Mods, then run the server. `naiwazi_anticheat_xxx.xml` will be generated in `GAME SAVING FOLDER` when you first run the mod. Please edit it carefully according to the comment. log files will also be generated in the same folder by default. Any change of the xml file do not need to restart the server.<br />
<br />
<br />
`Base Features:`<br />
`主要功能: `<br />
<br />
1.Check players' bag, inventory and equipment, you can set the items as you wish.<br />
1.检测人物背包，腰带及装备栏，可自定义设置检查物品。<br />
<br />
2.Check loots ( including boxes, secure boxes, forge workstations and so on ) around players, you can set the items as you wish.<br />
2.检测人物周围储物容器(包括箱子、上锁安全箱、熔炉工作台等等), 检测物品可自定义。<br />
<br />
3.God buff detection<br />
3.检测上帝模式。<br /><br />
4.Invisible mode detection<br />
4.检测隐身模式。<br />
<br />
5.check stack overflow of items in players' profile and loots  <br />
5.检测人物档案中的物品超叠和地图储物容器中的物品超叠。<br />
<br />
6.The action for anti-cheat contains BAN and WARN(just log it), for stack overflow, it can be set to destory the items <br />
6.检测后行为分为记录及BAN两种,超叠储物箱可设置销毁物品。<br />
<br />
注意：<br />
隐身模式检测需要作弊者开启后载入下一个chunk即可被检测到，飞行模式检测还在测试中，这个版本请勿使用。<br />
<br />
NOTE:<br />
Invisible mode detection required cheaters loading a new chunk. Fly mode detection is in testing, do not enable it in this version.<br />
<br />
联系方式: shyerzone@gmail.com <br />
Contact: shyerzone@gmail.com <br />
