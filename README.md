# 嗨，这是你的痒痒猫！

## 版本发布地址

- [国内地址](https://gitee.com/c4evil/yym-public/releases), 速度较快但下载需要登录。
- [国外地址](https://github.com/cookay/yym-public/releases), 下载无需登录，但下载速度较慢。

## 痒痒猫教程

[地址](tutorial.md)

## 式神数据

[数据定义](shishen_data.json)

- 式神数据全部为**六星**、**满级**、**觉醒**状态。
- 式神属性数值仅**速度**、**暴击**是精准的整数，其余属性不关注小数部分，如果你觉得必要，可以给我PR。
- 式神属性的`bonusAttribute`为觉醒属性加成。
- 所有游戏中带有百分号的属性，比如暴击、爆伤、xx加成，这里都用百分数表示，比如`"暴击": 10`代表10%暴击。

数据示例：

```json
  {
  	"id":217,
    "name": "大天狗",
    "level": 60,
    "rarity": "SSR",
    "bonusAttribute": {
      "type": "攻击加成",
      "value": 10
    },
    "attributes": {
      "攻击": 3135.6,
      "生命": 10025.96,
      "防御": 418.95,
      "速度": 110,
      "暴击": 10,
      "暴击伤害": 150
    }
  }
```

## 御魂数据

[数据定义](yuhun_type.json)

常规御魂示例：

```json
  {
    "id": 300048,
    "name": "狂骨",
    "dualSuiteBonusType": "攻击加成",
    "dualSuiteBonusValue": 15
  }
```

首领御魂没有两件套属性奖励，示例：

```json

  {
    "id": 300077,
    "name": "鬼灵歌伎",
    "dualSuiteBonusType": null,
    "dualSuiteBonusValue": null
  }
```