风险警告：工具未开源 该工具由易语言编写 有可能会严重损坏你的PC

本工具仅支持组织帐号 不支持@outlook之类的个人账号


使用方法：

添加账号：
首先输入账号密码 然后点击添加账户

可以添加多个，添加之后直接点登录

ps：以后打开程序可以直接点登录

配置文件存放于C:\Users\XXXXX\AppData\Roaming\azure.txt


选择帐号：

选择你要管理的帐号


选择订阅：

选择你要管理的订阅

ps：如果只有一个订阅会自动进入 不用选取


选择资源组：

选择你要操作的资源组

ps：如果是新账号 请先创建资源组 然后点击左上的重新获取资源组 再选取


管理VM：

选择资源组之后获取VM列表按钮激活

如果没有VM 请先点击创建VM

ps：创建VM暂只支持香港（更多自定义内容等我写好API再弄 易语言太麻烦了）

点击获取VM列表 然后选择VM

选择之后点击获取指定VM信息

之后可以进行开机关机重新 更换IP等操作

ps：删除VM可能会有网卡之类的残留 待解决



向VM发送Shell命令：

在获取VM信息之后激活发送命令功能

ps:不支持中文命令 不支持双引号 不支持交互





末尾：

地址：https://github.com/caippx/AzurePortalPCE

开源的话 等我把所有功能完善了再说吧 最近写微信小程序版 写昏了

这个程序肯定一堆BUG 有什么问题 请带截图 触发原因 来询问

所有功能全部微软原生POST实现 没有其他联网项目（有个nslookup？

更多功能等我写好API再说吧 易语言因为不支持双引号做变量内容 只能用"+#引号+” 来代替

替换之后是如下的吊样

所以post JSON会很麻烦


下个版本预计会有创建其他地区VM 自定义用户数据的功能（可以直接开root登录运行脚本之类的）
