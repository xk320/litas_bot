# litas_bot
LITAS项目挂机机器人

1、编辑配置文件如下所示：

[

  // 用户1信息
  
  {
  
    "user_name":"此处填写用户名1",
    
    "password":"此处填写密码1",
    
    "proxy_url": "此处填写代理1"
    
  },
  
  // 用户2信息
  
  {
    "user_name":"此处填写用户名2",
    
    "password":"此处填写密码2",
    
    "proxy_url": "此处填写代理2"
    
  },
  
]

多个用户在[]内增加以下是信息即可

  {
    "user_name":"此处填写用户名2",
    
    "password":"此处填写密码2",
    
    "proxy_url": "此处填写代理2"
    
  },
  
2、运行脚本

screen -S litas
# 进入脚本安装目录
cd litas_bot
# 运行脚本
./litas

3、退出会话程序后台运行
Ctrl+A然后按D键
4、相关命令
# 从新进入会话
screen -r litas
# 关闭会话
screen -X -S litas kill
