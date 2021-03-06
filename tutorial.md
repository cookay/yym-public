# 痒痒猫帮助

## 账号

按账号的概念管理，每个账号的御魂池和配置是彼此独立的。不一定跟游戏账号一一对应。

### 创建

**所有账号**界面中，点击右下角`+`按钮，弹出新建对话框，输入新帐户名后，进入导入御魂页面。

#### 从藏宝阁导入

在**导入御魂**界面选择**藏宝阁**，粘贴藏宝阁链接即可导入。

> 藏宝阁链接获取指引：
> 1. 藏宝阁应用中登记游戏账号
> 2. 游戏内点击左侧灯笼确认登记
> 3. 一周之后登记完成，操作上架，上架时有半小时无法登陆游戏
> 4. 由于上架后24小时内为观察期，不可交易，不用担心账号被人买走。而且可以设置价格为100万。
> 5. 上架成功后，就可以直接下架了。下架且取回账号后才可以登陆游戏。藏宝阁应用中，自己上架的商品详情右上角分享可以获取藏宝阁链接。

优点:

- 网易官方渠道，无风险
- 全程手机操作，不需借助电脑等

缺点:

- 每次更新御魂数据都需要上架藏宝阁，需要一周时间，无法马上看到刚强化的御魂

#### 从**痒痒熊快照**导入

在**导入御魂**界面选择**痒痒熊快照**，然后用其他应用（比如文件管理器），找到快照文件，选择通过痒痒猫打开。

优点:

- 无需等待，可以随时获得最新的御魂数据

缺点:

- 必须借助电脑
- 非官方、闭源、管理员权限，考验你对作者的信任

#### 从**阴阳师OCR御魂导出器**导入

在**导入御魂**界面选择**阴阳师OCR御魂导出器**，然后用其他应用（比如文件管理器），找到快照文件，选择通过痒痒猫打开。

优点:

- 无需等待，可以随时获得最新的御魂数据

缺点:

- 必须借助电脑
- 非官方、闭源、管理员权限，考验你对作者的信任

### 删除

**所有账号**界面中，左滑待删除的账号，出现**删除**按钮。

### 重新导入御魂数据

**所有账号**界面中，左滑待导入御魂的账号，出现**导入御魂**按钮。

### 排序

**所有账号**界面中，长按任意账号后上下拖动排序。

### 重命名

**所有账号**界面中，左滑待重命名的账号，出现**重命名**按钮。

## 配置

御魂配置，包含了式神、 御魂条件限制，以及曾经计算出的结果。

### 创建

**所有配置**界面中，点击右下角`+`按钮，弹出配置模板对话框，选择需要的模板进行配置创建。

### 配置说明

- **配置名称**: 必填，此配置的名称，比如“散件一速”、“魂土茨林”
- **式神**： 必填，此配置所使用的式神
- **排除其他配置**： 不同配置可能需要同时出场，所以同一个御魂不能同时出现在两个配置中。 此时使用**排除其他配置**选项，排除关系为单向的。比如有两套配置“一速散件面灵气”和“二速招财镰鼬”，是需要优先保障一速的，因此需要在后者的配置中排除前者。
- **御魂两件套**： 成对的挑选御魂，比如“狂骨荒骷髅”是狂骨x4加荒骷髅x2，那么需要挑选两个狂骨两件套和一个荒骷髅两件套。尽可能指定满3个两件套。
- **2号位主属性**： 如你所见, 尽可能指定。
- **4号位主属性**： 如你所见, 尽可能指定。
- **6号位主属性**： 如你所见, 尽可能指定。
- **面板数值要求**： 式神加上六件御魂之后的面板属性，已考虑式神觉醒加成、式神基础属性、御魂两件套加成等。
- **极限属性要求**： 找到所有满足条件的御魂配置中，指定属性最大/最小的一个组合。如果未指定，则会将第一个满需所有条件的配置作为结果。

### 删除

**所有配置**界面中，左滑待删除的配置，出现**删除**按钮。

### 编辑

**所有配置**界面中，左滑待删除的配置，出现**编辑**按钮。

### 排序

**所有配置**界面中，长按任意配置后上下拖动排序。

## FAQ

### 式神数据是满级的么? 

所有式神数据均为六星满级。

### 为什么导入的御魂这么少？ 

导入御魂时只会六星满级御魂，减少计算量。 请设想一下上限6000个御魂，假如每个位置1000个，总共有1000的6次方种组合，双路至强算一天也算不出来。

### 式神和御魂数值有考虑小数么？

- 式神数据未考虑小数。最重要的暴击和速度，都是整数，无需考虑。其他数值比如攻击，即便忽略小数，考虑到爆伤和攻击加成，最大可能造成10以内的攻击乘爆伤误差，可以忽略不计了。
- 御魂数据都有小数，请放心食用。

### 计算时间太长了，怎么能加快计算？

请尽可能指定满3个御魂两件套，2、4、6号位主属性（如果计算最大化伤害，不知道6号位爆伤还是暴击，可以试试分别指定爆伤和暴击各算一次）。

### 面板数值的上下限是开区间还是闭区间？可以手动指定开闭么？比如希望速度>128, 而暴击>=100。

面板数值要求的上下限都是按开区间计算。 即便是闭区间，由于小数位的存在，也是几乎不可能凑出刚好100暴击、128速度之类的整数的。所及不用关心区间开闭。

### 阴阳师素材哪里有？

- [式神素材](https://yys.163.com/shishen/index.html)
- [御魂素材](https://cbg-yys.res.netease.com/game_res/suit/300030.png)（不同御魂图标需要调整URL中的御魂id）