# Some Js for Miao-Yunzai
存放一些喵版云崽的Js插件，用别人写的插件魔改的，灵感来自群友的日常发言。

# 寻找主人
方法：@机器人，并且语句包含关键词“主人”   
例子：@迪奥娜 你的主人是谁？  
功能：召唤所有主人。  
备注：可在MasterID内配置需要通知的QQ号，保持默认值-1召唤所有主人。

# 设置倒计时
方法：#x小时x分钟后叫我  
例子：#2小时后叫我睡觉  
#10分钟后叫@迪奥娜 帮我打深渊  
功能：经过上述时间后@触发命令的人  
备注：有一定误差，重启机器人会打断倒计时。

# 护主  
方法：主人被禁言  
功能：机器人是管理员时，自动解禁主人

# dau
方法：自行在同目录创建`user_id.yaml`和`group_id.yaml`，发送`dau`即可查看近7日(可通过修改days变量调整统计期限)日活数据。
功能：腾讯官标群机器人后台日活数据缺失，使用该插件补足本该由腾讯官方完成的工作。

# MarryGuGuNiu
方法：`#下载咕咕牛图包`和`#更新咕咕牛图包`
功能：下载并应用自定义喵喵背景图包
备注：可自行修改下载时使用的`仓库地址`和`存放路径`

# b站卡片解析
方法：分享b站视频链接或卡片
功能：将分享链接解析成视频链接发送
备注：解析卡片需要`shamrock`适配器，配合`QAuxiliary`模块的`卡片消息文本化`功能

# 过滤官方机器人
功能：按号段为野生机器人屏蔽`@官标机器人`的消息
