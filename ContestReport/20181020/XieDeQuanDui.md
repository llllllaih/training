### info
* XieDeQuanDui
* 苗芸芸 
* 张斯宇
* 薛建杭

### 比赛地址
http://codeforces.com/contest/1070
### 做出来的题目

#### D

* 题意
+ 有n天，每天产生ai千克垃圾，你有容量为k的垃圾袋，尽可能的节省垃圾袋来清理垃圾，最少需要多少个垃圾袋（第i天产生的垃圾，第i+1天之前必须扔掉）

* 思路

每天要用的垃圾袋的容量为ai减掉昨天没装满的垃圾袋的剩余容量，然后算出每天要用的垃圾袋的数量即可

#### F

* 题意
+ 有n个可选的投票人，每个人都会为两个候选人投票，并且每个人都有一个影响力值，投票为1,不投为0,A.B两个候选人每人得到的票数的2倍必须都大于或等于选择的投票人的人数。求最大影响力。

* 思路
投票情况为11的人一定会成为投票人，人数为s1,把这些影响力加到ans上，然后分别记录投票情况01,10中A，B得到的总票数s2,s3，按照影响力分别对10,01 sort一下，取s2,s3中较小的一个数记为min1，在排好序的10,01中分别加上前min1个影响力，再把剩下的没有加上的sort一下，加上剩下的需要的个数。



### 补的题目

#### B

* 题意
balablal~~

* 思路
balablal~~~

...


