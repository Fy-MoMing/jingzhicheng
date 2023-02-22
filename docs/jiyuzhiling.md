# 给予指令

> **现在我们来了解服务器中的给予指令**

### 给予管理员指令

> **此指令要在后台输入 不需要带 /**

<p class="warn">
<code>op 玩家</code> 给予玩家管理员身份<br>
<code>deop 玩家</code> 移除玩家的管理员身份<br>
</p>

### 金币指令 Vault

<p class="warn">
<code>/eco give 玩家 数量</code> 给予该玩家的金币<br>
<code>/eco take 玩家 数量</code> 减少该玩家的金币<br>
<code>/eco set 玩家 数量</code> 设置该玩家的金币<br>
<code>/eco reset 玩家 数量</code> 将该玩家的金币清零<br>
</p>

### 点券指令 Points

<p class="warn">
<code>/points give 玩家 数量</code> 给予该玩家的点券<br>
<code>/points giveall 数量</code> 给予全部玩家点券<br>
<code>/points take 玩家 数量</code> 减少该玩家的点券<br>
<code>/points pay 玩家 数量</code> 将点券支付给该玩家<br>
<code>/points look 玩家</code> 查询某玩家的点券<br>
<code>/points lead </code> 点券排行榜<br>
<code>/points set 玩家 数量 </code> 设置该玩家的点券数量<br>
<code>/points reset 玩家 </code> 将该玩家的点券清零<br>
<code>/points me </code>查看自己的点券数量<br>
可以缩写为: <code>/p 命令</code>
</p>

### 武器装备和物品指令 SX-Attribute MythicMobs

> **原版给予指令**
<p class="warn">
<code>/give 玩家 物品id或英文名 数量</code> 这是给予玩家原版物品的指令
</p>

> **SX-Attribute物品的给予方式**

<p class="warn">
<code>/sx give 物品内部名字 玩家 数量</code> 给予玩家该物品<br>
也可以省略数量 默认1个<br>
如大家不知道物品的内部名字<br>
可以在后台配置文件plugins/SX-Attribute/item文件夹里查看<br>
或者使用<code>/sx give</code>来查看部分物品的内部名字<br>
快捷查询方式可以这样子 比如: <code>/sx give 破境</code> 搜索出来的就是带破境的武器装备或物品 点击名字即可获取<br>
</p>

> **MythicMobs物品的给予方式**

<p class="warn">
<code>/mm i give 物品内部名字 玩家 数量</code> 给予玩家该物品<br>
这条指令已经是简写的方式了<br>
如果我们不知道物品内部名字怎么办呢？<br>
可以在后台配置文件plugins/Mythicmobs/items文件夹里查看<br>
当然也可以使用指令<code>/mm i list</code>来查看部分物品的内部名字<br>
</p>