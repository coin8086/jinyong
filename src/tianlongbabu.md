# 天龙八部主要人物、关系

```mermaid
graph LR

subgraph 大理国
direction LR
duanyu(((段誉))) ---|兄妹| zhongling((钟灵))
duanyu ---|兄妹| muwanqing((木婉清))
duanyu ---|兄妹| azhu((阿朱))
duanyu ---|兄妹| azi((阿紫))
duanyu ---|兄妹| wangyuyan(((王语嫣)))
duanyu ----|父子| duanzhengchun((段正淳))
duanyu ----|母子| daobaifeng((刀白凤))
zhongling ---|母女| zhongfuren((钟夫人))
muwanqing ---|母女| qinhongmian((秦红棉))
azhu ---|母女| ruanxingzhu((阮星竹))
azi ---|母女| ruanxingzhu
wangyuyan ---|母女| wangfuren((王夫人))
daobaifeng ---|原配| duanzhengchun
zhongfuren ---|情人| duanzhengchun
qinhongmian ---|情人| duanzhengchun
ruanxingzhu ---|情人| duanzhengchun
wangfuren ---|情人| duanzhengchun
end

subgraph 四大恶人
direction TB
duanyanqing((老大 段延庆)) -->|属下| yeerniang((老二 叶二娘))
duanyanqing -->|属下| nanhaieshen((老三 南海鳄神))
duanyanqing -->|属下| yunzhonghe((老四 云中鹤))
duanyanqing ---|兄弟| duanzhengchun
nanhaieshen ---|师徒| duanyu
duanyanqing -.- daobaifeng
duanyanqing -.- duanyu
end

subgraph 逍遥派
direction LR
wuyazi((无涯子)) ---|师兄妹 + 伴侣| liqiushui((李秋水))
wuyazi ---|师兄妹| tianshantonglao((天山童姥))
wuyazi ----|师徒| suxinghe((苏星河))
wuyazi ----|师徒| xingxiulaoguai((星宿老怪))
suxinghe ---|仇敌| xingxiulaoguai
liqiushui ---|情敌| tianshantonglao
liqiushui ---|母女| wangfuren
duanyu -.->|仰慕| liqiushui
end

subgraph 丐帮
direction LR
xiaofeng(((萧峰))) ---|义兄弟| duanyu
xiaofeng ---|伴侣| azhu
xiaofeng ---|照料| azi
xiaofeng ---|父子| xiaoyuanshan((萧远山))
xiaofeng --- baishijing((白世镜))
xiaofeng ---|杀父之仇| youtanzhi((游坦之))
youtanzhi -->|爱慕| azi
youtanzhi -->|受制于| xingxiulaoguai
baishijing -.- mafuren((马夫人))
mafuren ---|情人| duanzhengchun
end

subgraph 少林
direction LR
xuzhu(((虚竹))) ---|义兄弟| duanyu
xuzhu -->|师承| wuyazi
xuzhu -->|继灵鹫宫主人| tianshantonglao
xuzhu -.- yeerniang
xuanci((玄慈)) -.- xuzhu
xuanci -.- xiaoyuanshan
xuanku((玄苦)) ---|师徒| xiaofeng
end

subgraph 慕容家
direction LR
murongfu(((慕容复))) ---|表兄妹| wangyuyan
murongfu ---|舅妈| wangfuren
murongfu ---|主仆| azhu
murongfu ---|父子| murongbo((慕容博))
murongbo -.- xiaoyuanshan
end

subgraph 吐蕃国
direction LR
jiumozhi((鸠摩智)) -->|要挟| duanyu
jiumozhi ---|好友| murongbo
end

subgraph 辽国
yelvhongji((耶律洪基)) ---|"义兄弟、君臣"| xiaofeng
end
```

图例：

* 双环圈示重点人物
* 实线表示两个人物的一般关系
* 虚线表示两个人物的“隐藏”关系
* 带箭头的线表示一种单向关系

此外：

* 人物大致按所属或所关联的主要门派、家族归类，但同时也考虑到绘图效果，故此个别人物的归类可能不是特别合适。比如“萧远山”，他是辽国人，不属于丐帮，但考虑到他跟“萧峰”与“丐帮”的重大关联，以及绘图的效果，把他放在了“丐帮”下面，而不是“辽国”；又比如“段正淳”的情人们，如“王夫人”，并非都是大理人或在大理居住，但考虑到他们与大理段氏的关系，都归于“大理国”下。
* 大部分人物之间只标识出了一种主要关系，如“父子”、“师徒”等，没有包括其他的复杂关系（如有）——比如“慕容复”跟“王夫人”之间，不是只有“外甥-舅妈”的关系，更有十分复杂的利害关系。
* 有些人物之间没有标明关系，或是为了减少“剧透”，如“段誉”与“段延庆”的关系，或是因为人物之间的关系比较复杂、无法简单概括，比如“萧峰”与“白世镜”。
* 考虑到绘图效果，个别推动剧情的重要人物并未出现，如少林“扫地僧”，但不影响主要人物关系。

最后，关系图由Mermaid Flow Chart绘制，作者在此表示感谢。但由于该软件本身只是用于绘制流程图而非人物关系图，故此效果欠佳，请读者包涵。如读者知道用于Markdown的更合适的绘图软件，请不吝示之。
