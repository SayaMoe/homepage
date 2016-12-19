title: Decorations
category: 插件
time: 1481017871800
---
Decorations 整合了TFC Lanterns 插件，又在此基础上增加了一些其他的方块来增强装饰能力

![lanterns and gem block](../../static/decorations/lanterns-and-gem-block-preview.png)

# 增加的功能

## Lanterns （灯笼）

可以从 Tier 1 -  Tier 3 的金属以及合金制作多达12种灯笼。
Tier3及以上的金属或合金做成的灯笼有最大亮度，其余所有属性都是一样的。

空手Shift+右键 点击灯笼可以开关

灯笼的亮度等级可以在配置文件里编辑（目前使用默认配置）

### 制作方法：

需要先制作Lantern Core，Lantern Core使用任何 Tier 1 - 3 金属或合金在Anvil（铁砧）打造，打造方法如下图所示

Lantern Core制作好之后，需要酒精（任意一种酒）作为燃料填充，每个Lantern Core消耗2000ml酒精。

然后再使用棍子，绳子，和玻璃板加上Lantern Core Filled 制作成Lantern

![Lantern Core anvil recipe](../../static/decorations/anvil-lantern-core.png)


## Gem Blocks (宝石方块)

允许手持宝石右键点击任何固体方块的侧面将宝石镶嵌在方块上。

如果方块被摧毁，那么宝石将会掉落

附着的宝石可以被当作光源，亮度等级如下：

- Exquisite: 15

- Flawless: 14

- Normal: 13

- Flawed: 12

- Chipped: 11

亮度等级可以在配置文件里编辑（本服务器使用默认配置）

## Gypsum Mortar and Alabaster Blocks （石膏砂浆和雪花石膏方块）

可以从Gypsum（石膏）里制作Gypsum Powder（石膏粉）， 石膏粉可以被用于生产(Gypsum Plaster)石膏抹灰，石膏抹灰可以用来制作砂浆和雪花石膏方块。

雪花石膏方块有如下特点：

- 可以被染色
- 可以被Chisel（凿子）处理
- 但不能用于覆盖木炭坑（Charcoal Pit）

### 制作方法：

#### 制作Alabaster Block（雪花石膏方块）

使用锤子和Gypsum（石膏）其粉碎成Gypsum Powder

将Gypsum Powder置于淡水的桶（Barrel）中，每1块消耗500mB淡水，满满一桶淡水正好需要20块Gypsum Powder，得到了Gypsum Plaster（石膏抹灰），如果你有足够的gypsum powder这个过程是瞬间完成的。

再将Gypsum Powder置于Gypsum Plaster的桶里，每块Gypsum Powder需要50mB的Gypsum Plaster，然后Seal（封印）Barrel，下面显示输出为Alabaster Block，等待若干小时。
满满一桶Gypsum Plaster可以生产200个Alabaster Block。这个过程总共消耗200 + 20个Gypsum Powder

#### 制作Mortar（砂浆）

类似与Limewater（石灰水）制作砂浆的原理，将沙子（Sand）放入Gypsum Plaster里，seal即可。


### 给Alabaster Block染色

#### 制作刷子

#### 制作液体染料

#### 用液体染料填充刷子

#### 上色

<img src="../../static/decorations/gypsum-alabaster.png" alt="Gypsum and alabaster" style="width: 360px; max-height: inherit;">

## Mud Bricks (泥砖)

这些泥砖可以用于替代石砖，并在进入金属时代之前生产。

泥砖颜色取决于材料（主要是泥土的岩石种类）

泥砖有如下特点：

- 可以被凿子处理
- 不能用于覆盖木炭坑（Charcoal Pit）

### 制作泥砖

首先使用沙子，稻草，粘土合成潮湿的泥砖，然后将泥砖放在地面上，等待12小时，取回泥砖，此时得到了干燥的泥砖，将4个干燥的泥砖合成泥砖方块(Mud Brick Block)

![Mud Brick](../../static/decorations/mud-brick.png)
