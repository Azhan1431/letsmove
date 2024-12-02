## 需求
### place
- 配置
  - 设置手续费比例、赔率、管理员、手续费接收人和奖池。
- 功能
  - 创建place
  - 给奖池注资
  - 更新palace配置
  - 静态方法
### game
- 规则
  - 石头 > 剪刀 > 布 > 石头
  - 如果用户没有获胜，计算手续费，手续费转给手续费接收人，剩余入金并入奖池。
  - 如果用户获胜，计算奖金，如果奖池足够支付奖金，按照赔率赔付用户；否则，从奖池中扣除手续费后赔付用户。