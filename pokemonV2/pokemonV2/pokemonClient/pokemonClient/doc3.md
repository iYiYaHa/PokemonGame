# 题目三：游戏对战的设计
- [ ] 已经登录的在线用户可以和服务器进行虚拟决斗，决斗分两种：升级赛和决斗赛，两种比赛都能增长宠物经验值。服务器上有一个虚拟精灵的列表，用户可以挑选其中任意一个进行比赛（升级赛或者决斗赛）。另外决斗赛中用户胜出可以直接获得该战胜的的精灵，失败则系统从用户的精灵中随机选三个（不够三个精灵的情况就选择他所有的精灵），然后由用户选一个送出。
      升级赛 只是用户用来增加精灵经验值，规则开发者自定；
      - [x] 累积多少经验值升一级，规则开发者自定；
      - [ ] 决斗赛的上述规则同升级赛，只是额外还可以赢得宠物一个。
      - [ ] 用户如果没有精灵（比如总是失败，已经全部送出去），则系统会随机放给给他一个初级精灵。
- [ ] 请让你的系统自动模拟每场比赛的每次出招。另外，为了增加不确定性，可以加入概率闪避攻击和暴击伤害机制
      比赛的过程和结果由系统根据上述规则自动模拟完成，要求结果具有一定的随机性。
      - [x] 用户增加新功能，可以查看某个用户的胜率
      - [ ] 用户增加新属性，为宠物个数徽章（金银铜）和高级宠物徽章（金银铜），分别根据拥有的宠物个数的多少和拥有高级宠物（15级）个数的多少颁发
      - [ ] 如有界面设计可酌情加分，如有新颖设计可酌情加分
      - [ ] 题目考察点：客户端与服务器数据交互（可采用多进程或异步通信或其他方法均可），并发请求处理，类的方法设计，伤害计算方法设计。

