# 我的世界服务器部分指令

> **由于指令很多 这里只写一些用处多的指令**

### 常用指令

<p class="warn">
<code>/gamerule doMobSpawning false</code>禁止该世界自动生成生物<br>
<code>/gamerule keepInventory true</code>开启该世界死亡不掉落<br>
<code>/gamerule mobGriefing false</code>开启该世界的防爆<br>
<code>/mv modify set pvp false</code>关闭该世界PVP斗殴 相反 设置为<code>true</code>则开启PVP<br>
<code>/difficulty 数字</code>设置该世界的难度 <code>0为和平</code> <code>1为简单</code> <code>2为和平</code> <code>3为困难</code> <br>
</p>

### 传送指令

<p class="warn">
<code>/tp 玩家</code> 传送到该玩家身边 只可用于管理员<code>/tpa 玩家</code>可用于玩家<br>
<code>/warp 地标名字</code> 传送至某某地标 可用<code>/warp</code> 来查看地标名字 只可用于管理员<br>
<code>/mv tp 世界名字</code> 传送至某世界 可在服务端的根目录查看每个世界的名字 文件夹名字就是世界名字 只可用于管理员<br>
</p>

### 封禁指令

<p class="warn">
<code>/ban 玩家 时间</code> 封禁该玩家多长时间 如不填写则是永久<br>
<code>/banip IP地址</code> 封禁该玩家的IP地址<br>
<code>/banlist</code> 显示封禁列表<br>
<code>/ban 玩家</code> 封禁该玩家<br>
<code>/kick 玩家 理由</code>从服务器踢出该玩家<br>
</p>

### 背包指令

<p class="warn">
<code>/invsee 玩家</code> 查看某玩家的背包<br>
<code>/clear 玩家</code> 清理某玩家的背包<br>
</p>

### 游戏模式

<p class="warn">
<code>/gamemode 1 玩家</code> 更改该玩家游戏模式为创造<br>
<code>/gamemode 0 玩家</code> 更改该玩家游戏模式为生存<br>
<code>/fly 玩家</code> 为该玩家开启飞行 再次输入关闭飞行<br>
</p>

### 时间/天气

<p class="warn">
<code>/time 时间</code> 设置该世界的时间<br>
<code>/day</code> 设置该世界变为白天 <code>/night</code> 设置该世界变为黑夜<br>
<code>/sun</code>设置该世界为晴天<code>/rain</code>设置该时间为雨天 雪天也是这个指令看是在高原开始平原了<br>
<code>/gamerule doDaylightCycle false</code>设置该世界时间禁止 改为<code>true</code>恢复时间流动<br>
</p>