1. 尽管`acousticness`（人声）和`instrument`(乐器)貌似有冲突，但实际上应该没有，其和最大为1.99左右，最小为0
2. `liveness`与`speechiness`可能有重合，`liveness`-`speechiness`最大为0.96，最小仅为-0.85
3. `popularity`与发行时间关系密切，越近发行（2020）可能便越受欢迎
4. `release_date`至少包含2种形式：1/30/2001   2001
5. 普遍存在同一个name,但不同id的情况，如Death
6. 有的同一个name但不同id，但事实上就是数据错误，如第916个数据，1416，id为7位数
7. 在influence第6646行（第6644个记录，从0开始），显然是存在了数据问题（从The Kills到The Kills）第29381个记录同理。37697个记录同理

