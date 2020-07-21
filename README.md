### 京东薅羊毛工具（活动入口：京东app->我的->游戏与互动->查看更多）

1.  京东水果([jd_fruit.js](https://gitee.com/lxk0301/scripts/raw/master/jd_fruit.js))
2.  东东萌宠([jd_pet.js](https://gitee.com/lxk0301/scripts/raw/master/jd_pet.js))
3.  宠汪汪([jd_joy.js](https://gitee.com/lxk0301/scripts/raw/master/jd_joy.js))
4.  种豆得豆([jd_plantBean.js](https://gitee.com/lxk0301/scripts/raw/master/jd_plantBean.js))
5.  天天加速([jd_speed.js](https://gitee.com/lxk0301/scripts/raw/master/jd_speed.js))
6.  摇钱树([jd_moneyTree.js](https://gitee.com/lxk0301/scripts/raw/master/jd_moneyTree.js))

#### 使用说明

脚本兼容: QuantumultX, Surge, Loon, JSBox, Node.js 

注：如果使用Node.js, 需自行安装'got'模块. 例: npm install got -g

# 【boxjs简单说明】

使用box可以实现远程订阅助力好友。

box使用请查看[chavy频道](https://t.me/chavyscripts)

目前京东活动中以下三个脚本可以使用box功能

【1】京东水果

【2】京东萌宠

【3】京东种豆

【用box订阅的好处】

 1、脚本也可以远程挂载。京东活动助力功能的分享码只需在box里面填写。以后只需远程更新就行。

 2、所有脚本的cookie都可以备份，方便你迁移到其他支持box的软件。

 3、box可以支持多账号
 
 [京东活动的box订阅链接](https://gitee.com/lxk0301/scripts/raw/master/lxk0301.boxjs.json)

```

//示例：2个京东账号的Qumutumult X cron设置(5分钟为间隔)
[task_local]
#切换会话
30,59 1-23 * * * https://raw.githubusercontent.com/chavyleung/scripts/master/box/switcher/box.switcher.js, tag=切换会话, img-url=https://raw.githubusercontent.com/znz1992/Gallery/master/BOXJS.png, enabled=true
#京东摇钱树
25,56 */2 * * * https://gitee.com/lxk0301/scripts/raw/master/jd_moneyTree.js, tag=京东摇钱树, img-url=https://raw.githubusercontent.com/znz1992/Gallery/master/moneyTree.png, enabled=true
#京东宠汪汪
20,51 */3 * * * https://gitee.com/lxk0301/scripts/raw/master/jd_joy.js, tag=京东宠汪汪, img-url=https://raw.githubusercontent.com/znz1992/Gallery/master/jdww.png, enabled=true
#京东天天加速
15,46 */4 * * * https://gitee.com/lxk0301/scripts/raw/master/jd_speed.js, tag=京东天天加速, img-url=https://raw.githubusercontent.com/znz1992/Gallery/master/jdttjs.png, enabled=true
#东东农场
10,41 7-19/6 * * * https://gitee.com/lxk0301/scripts/raw/master/jd_fruit.js, tag=东东农场, img-url=https://raw.githubusercontent.com/znz1992/Gallery/master/jdsg.png, enabled=true
#京东萌宠
5,36 6-18/6 * * * https://gitee.com/lxk0301/scripts/raw/master/jd_pet.js, tag=京东萌宠, img-url=https://raw.githubusercontent.com/znz1992/Gallery/master/jdmc.png, enabled=true
#种豆得豆
0,31 6-23/2 * * * https://gitee.com/lxk0301/scripts/raw/master/jd_plantBean.js, tag=种豆得豆, img-url=https://raw.githubusercontent.com/znz1992/Gallery/master/jdzd.png, enabled=true

```