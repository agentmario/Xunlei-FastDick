迅雷快鸟
===
一个可以运行在路由器的迅雷快鸟(diǎo)客户端

# 怎么play
* 买买买 http://pay.vip.xunlei.com/baijin.html
* $ git clone git@github.com:fffonion/Xunlei-FastDick.git && cd Xunlei-FastDick
* 新建 __swjsq.account.txt__，填入`用户名,密码`，如`ahaha,123456`，并保存
* Python 2.x or Python3.x
* $ nohup python ./swjsq.py &

# 说明
* 明文存储的密码将会在第一次登陆成功后保存为数字ID和密码的MD5，明文文件将会删除
* 会员权限及月加速流量等详见[这里](http://swjsq.xunlei.com)
* 自带[这里抄的](https://github.com/mengskysama/XunLeiCrystalMinesMakeDie/blob/master/run.py)纯python实现RSA加密，可选安装pycrypto加快(首次)运算速度
* 登陆成功后会生成`swjsq_wget.sh`以及一个ipk包，可用于直接调用或者安装后运行 __/bin/swjsq__

# TODO
* session过期时间
* web前端
