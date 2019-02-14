# 项目介绍
第一个python ATM功能的测试，使用json作为序列化
# 目录和文件介绍
  * bin 主程序入口
    * main.py
  * db ATM购物车序列化文件购物车序列化文件
    * ATM和shop_car ATM序列化文件和
    * user_db.py 序列化文本路径控制
    * user_db.txt 序列化文本
    * user_db1.py 序列化文本路径控制
    * user_shop_car序列化文本
  * lib 各模块内容
    * ATM
      * cash_withdrawal.py提现模块
      * interface.py 银行给第三方调用接口
      * login.py 登陆功能模块
      * menu1.py 功能分发模块
      * query1.py 查询功能模块
      * repayment.py 还款模块
      * transfer.py 转账模块
      * user_registration.py 添加修改信用卡模块
    * shoping_car
      * add_user.py 购物车用户模块
      * car_list.py 列出购物车中的内容，并提供ATM接口结算
      * menu.py 购物车功能分发
      * shop_car_list.py 购物车购物功能
    * log
      * log.py 控制日志的结构信息
  * 日志内容
    * admin ATM机的后台操作日志
      * admini_log.txt 操作日志信息
      * log_path.py 日志路径控制
    * user ATM的前台操作日志
      * admini_log.txt 操作日志信息
      * log_path.py
# ATM和购物车账号信息
  * ATM账号信息
    * 后台帐号信息
      * 用户名 admin
      * 密码 123
    * 前台账号信息
      * 用户名 12345678901 12345678902
      * 密码 123456
   * 购物车账号信息
      * 购物车登陆
        * 用户1 2 3
        * 没密码
  
  
