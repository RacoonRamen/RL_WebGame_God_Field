# RL WebGame God Field
![image](https://user-images.githubusercontent.com/75330475/205007923-33abe68f-c01c-484b-89e3-cc593afa4c41.png)

# GYM Custom Enviroment
## 遊戲元素條件:
### 卡牌類型
* 交易->價錢
* 武器->攻擊力/價錢/效果
* 防禦->防禦力/價錢/效果
* 商品->加減血量/價錢/效果
* 奇蹟->攻擊/損耗魔力/效果
### 卡片元素
* 火 克 水
* 水 克 火
* 木 克 石
* 石 克 木
* 光 克 所有屬性
* 暗 未防禦直接死亡
### Observation Space
* +atk/-def : 卡片攻擊力或防禦力，大於0的時候為攻擊力小於0的時候為防禦力
* price : 卡片的價格
* element : 卡片的元素
* +hp/-mp :卡片大於0增加血量，小於0實為增加魔力
* costMP : 消耗的魔力
* php : 玩家的血量
* pmp : 玩家的魔力
* pmy : 玩家的金錢 
* ehp : 敵人的血量 
* emp : 敵人的魔力
* emy : 敵人的金錢
* my_atk : 敵人的攻擊力
### Action Space
* Play(出牌)
* Pass(跳過)
* 

